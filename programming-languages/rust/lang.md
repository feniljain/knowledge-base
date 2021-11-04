# Macros

- Rust has two types of macros:

  - Declarative: defining new syntax in a higher-level, declarative way(is less restrictive, you can do anything)
  - Procedural: defining function-like macros, custom derives and custom attributes using functions on token streams
    - Point to note how matklad was referring to his misconception of macros on token stream i/ps and o/ps

- I used to think macros of something which reduces random repeated code, but I was wrong, while reading the reference I realized there's a big difference between using it for reusability and its original purpose, it is mainly used for metaprogramming, in simple words(from rust reference): it is used to extend _*functionality*_ and _syntax_ of language
