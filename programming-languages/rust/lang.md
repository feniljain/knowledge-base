# Macros

- Rust has two types of macros:

  - Declarative: defining new syntax in a higher-level, declarative way(is less restrictive, you can do anything)
  - Procedural: defining function-like macros, custom derives and custom attributes using functions on token streams
    - Point to note how matklad was referring to his misconception of macros on token stream i/ps and o/ps

- I used to think macros of something which reduces random repeated code, but I was wrong, while reading the reference I realized there's a big difference between using it for reusability and its original purpose, it is mainly used for metaprogramming, in simple words(from rust reference): it is used to extend _*functionality*_ and _syntax_ of language

# Lifetimes:

- The compiler uses three rules to figure out what lifetimes references have when there aren’t explicit annotations. The first rule applies to input lifetimes, and the second and third rules apply to output lifetimes. If the compiler gets to the end of the three rules and there are still references for which it can’t figure out lifetimes, the compiler will stop with an error. These rules apply to fn definitions as well as impl blocks.

The first rule is that each parameter that is a reference gets its own lifetime parameter. In other words, a function with one parameter gets one lifetime parameter: fn foo<'a>(x: &'a i32); a function with two parameters gets two separate lifetime parameters: fn foo<'a, 'b>(x: &'a i32, y: &'b i32); and so on.

The second rule is if there is exactly one input lifetime parameter, that lifetime is assigned to all output lifetime parameters: fn foo<'a>(x: &'a i32) -> &'a i32.

The third rule is if there are multiple input lifetime parameters, but one of them is &self or &mut self because this is a method, the lifetime of self is assigned to all output lifetime parameters. This third rule makes methods much nicer to read and write because fewer symbols are necessary.

# Fat vs Smart Pointers:

- Both are pointers with additional information.

The smart pointer has additional information compile-time, i e, the type of smart pointer tells the compiler what can be done with the information behind the pointer, if the compiler should insert some code when the pointer goes out of scope, etc.

The fat pointer has additional information run-time, so it can e g check the length of a slice before accessing it, or invoke some method where the compiler cannot deduce which method it is, it has to be determined run-time.

There are also thin pointers, where this additional information is run-time, but at the location pointed to rather than following the pointer itself. These are common in other languages but not so much in Rust (there are crates though).
