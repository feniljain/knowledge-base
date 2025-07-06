<h2 align="center">Compilers</h2>

## Websites:

- Convert codes from various languages into assembly: https://godbolt.org/
- https://www.craftinginterpreters.com/
- https://www.gnu.org/software/bison/
- IR overview: https://llvm.org/docs/LangRef.html#overview
- http://ellcc.org/demo/index.cgi
- https://llvm.org/docs/GettingStartedTutorials.html
- https://bertrandbev.github.io/dlox/#/
- https://zerovector.space/poor-mans-compiler-explorer
- Compiler Resources: https://theworld.com/~compres/crilogo.html
- http://aosabook.org/en/llvm.html
- Book on everything GCs: http://gchandbook.org/
- https://astexplorer.net/
- https://papl.cs.brown.edu/
- https://papl.cs.brown.edu/2020/index.html
- List of companies working on things realted to compiler: https://mgaudet.github.io/CompilerJobs/
- QBE is a compiler backend that aims to provide 70% of the performance of industrial optimizing compilers in 10% of the code: https://c9x.me/compile/
- understanding register allocation via graph coloring: https://rsms.me/projects/chaitin
- libFirm is a C library that provides a graph-based intermediate representation, optimizations, and assembly code generation suitable for use in compilers: https://pp.ipd.kit.edu/firm/
- https://compileroptimizations.com/index.html

## Blogs and articles:

### Tutorials:

- Building a WASM compiler in rust: https://www.bitfalter.com/blog
- Writing a C compiler: https://norasandler.com/2017/11/29/Write-a-Compiler.html
- https://medium.com/trendyol-tech/contributing-the-go-compiler-adding-new-tilde-operator-f66d0c6cff7
- https://ceronman.com/2021/07/22/my-experience-crafting-an-interpreter-with-rust/
- How to write your own compiler: https://llvm.org/ProjectsWithLLVM/#compilerwrite
- Brainfuck compiler: https://www.wilfred.me.uk/blog/2015/08/29/an-optimising-bf-compiler/
- Brainfuck compiler: https://www.wilfred.me.uk/blog/2015/10/18/even-more-bf-optimisations/
- Brainfuck compiler: https://www.wilfred.me.uk/blog/2016/02/07/an-industrial-grade-bf-compiler/
- https://luctielen.com/posts/how-to-lower-an-ir/
- Building an interpreter in Rust: https://blog.subnetzero.io/post/building-language-vm-part-00/
- https://mukulrathi.com/create-your-own-programming-language/intro-to-type-checking/
- https://m-peko.github.io/craft-cpp/posts/writing-a-compiler-part-1/
- Hindley-Damas-Milner tutorial: https://github.com/quchen/articles/tree/master/hindley-milner
- How to write your own LR(1) parsing tables (and generate them): https://boxbase.org/entries/2019/oct/14/lr1-parsing-tables/
- PEG Parsing Series Overview by Guido van Rossum ( creator of python ): https://medium.com/@gvanrossum_83706/peg-parsing-series-de5d41b2ed60
- Formally Verified Native Code Generation in an Effectful JIT or: Turning the CompCert Backend into a Formally Verified JIT Compiler: https://people.irisa.fr/Aurele.Barriere/papers/fmjit.pdf
- https://apaz-cli.github.io/blog/How_to_Write_a_Compiler_Without_Going_Insane.html
- Small little recursive descent parser + pratt parsing: https://gist.github.com/elucent/473dcacba79371ec647d43e7c58babbd
- How compiler actually produces dynamic libraries/static libraries, ELFs, etc. Something away from typical compiler stuff which should help everyone understand compiler/linker errors around common scenarios: https://fabiensanglard.net/dc/
- Nice list of resources on learning more about modern compilers: https://lobste.rs/s/zqa4cc/learning_modern_compilers
- Compiler Hacking: https://yangdanny97.github.io/blog/2020/05/29/chocopy-typechecker
- MLIR Tutorial for beginners: https://github.com/j2kun/mlir-tutorial
- Write your own retro compiler: http://t3x.org/t3x/0/book.html
- Writing a very simple JIT Compiler in about 1000 lines of C: https://kuterdinel.com/writing-a-very-simple-jit-compiler-in-about-1000-lines-of-c.html

### Others:

- https://huonw.github.io/blog/2016/04/myths-and-legends-about-integer-overflow-in-rust/
- https://blog.llvm.org/
- https://en.wikipedia.org/wiki/Static_single_assignment_form
- https://go.googlesource.com/gollvm
- https://cfallin.org/blog/2021/03/15/cranelift-isel-3/
- https://secret.club/2021/04/09/std-clamp.html
- Incrementalized Pointer and Escape Analysis, Compiler optimization technique: https://people.csail.mit.edu/rinard/paper/pldi01.pdf
- Making dynamically typed language's compilation faster: https://mozilla.github.io/pdf.js/web/viewer.html
- https://cfallin.org/blog/2020/09/18/cranelift-isel-1/
- Yet another compiler visualizer: https://ashutoshbsathe.github.io/yacv/
- https://towardsdatascience.com/understanding-compilers-for-humans-version-2-157f0edb02dd
- https://medium.com/young-coder/how-i-wrote-a-lexer-39f4f79d2980
- https://weliveindetail.github.io/blog/post/2021/05/28/debian-llvm-quick-install.html
- https://medium.com/@thelukaswils/understanding-compilers-for-humans-ba970e045877
- https://medium.com/@thelukaswils/making-a-brainf-ck-to-c-compiler-in-rust-10f0c01a282d
- https://en.wikipedia.org/wiki/Shunting-yard_algorithm
- https://medium.datadriveninvestor.com/whats-llvm-4c0c3ed43a72
- https://www.npopov.com/2021/06/02/Design-issues-in-LLVM-IR.html
- List of passes for the SSA compiler step: https://github.com/golang/go/blob/6c1c055d1ea417d050503efe92c1eead0da68cef/src/cmd/compile/internal/ssa/compile.go#L431-L486
- Generating better machine code with SSA in go compiler: https://www.youtube.com/watch?v=uTMvKVma5ms
- https://stackoverflow.com/questions/1669/learning-to-write-a-compiler
- https://joshvarty.com/2015/09/18/learn-roslyn-now-part-13-keeping-track-of-syntax-nodes-with-syntax-annotations/
- https://blog.matthieud.me/2020/exploring-clang-llvm-optimization-on-programming-horror/
- https://rust-analyzer.github.io/blog/2019/11/13/find-usages.html
- https://bellmar.medium.com/learning-almost-nothing-about-llvm-e6aea9b243d9
- LLVM no more has any fullform, its just LLVM lol: https://lists.llvm.org/pipermail/llvm-dev/2011-December/046445.html
- https://tratt.net/laurie/blog/entries/which_parsing_approach.html
- https://cpp4arduino.com/2018/10/23/what-is-string-interning.html
- https://matklad.github.io/2020/03/22/fast-simple-rust-interner.html
- https://www.javatpoint.com/compiler-passes
- https://www.apollographql.com/blog/announcement/tooling/apollo-rs-graphql-tools-in-rust/
- Pratt Parsing Index and Updates(Collection of blogs regarding pratt parsing): https://www.oilshell.org/blog/2017/03/31.html
- https://stackfull.dev/trie-in-javascript-the-data-structure-behind-autocomplete
- https://lowlevelbits.org/how-to-learn-compilers-llvm-edition/
- https://blog.methodscript.com/2021/10/05/compiling-methodscript-to-llvm/
- https://www.i-programmer.info/news/149-security/15004-latest-vulnerability-suggests-compilers-should-learn-unicode.html
- https://simonbyrne.github.io/notes/fastmath/
- https://dev.to/aruna/abstract-syntax-trees-theyre-used-everywhere-but-what-are-they-jh6
- https://matt.might.net/articles/by-example-continuation-passing-style/
- https://gcc.gnu.org/onlinedocs/gccint/GIMPLE.html
- https://gcc.gnu.org/onlinedocs/gccint/RTL.html
- https://richardstartin.github.io/posts/loop-fission
- Lexical Analysis of python documentation: https://docs.python.org/3/reference/lexical_analysis.html
- Scope Graphs, a theory of name resolution(used in github code search): https://pl.ewi.tudelft.nl/research/projects/scope-graphs/
- https://releases.llvm.org/3.0/docs/SegmentedStacks.html
- https://gcc.gnu.org/wiki/SplitStacks
- https://depth-first.com/articles/2021/12/16/a-beginners-guide-to-parsing-in-rust/
- An incremental approach to compiler construction: http://scheme2006.cs.uchicago.edu/11-ghuloum.pdf
- https://slightknack.dev/passerine/type-inference/
- https://www.quora.com/What-are-the-best-universities-in-the-world-for-pursuing-a-Masters-PhD-degree-in-Computer-Science-with-specialization-in-Compilers
- https://www.bexxmodd.com/log/llvm-infrastrucutre-and-rust/7
- https://www.geeksforgeeks.org/structure-member-alignment-padding-and-data-packing/
- https://llvm.org/doxygen/classllvm_1_1Value.html
- https://medium.com/@vishwajit.patil19/compilers-for-distributed-systems-464e6651aa4d
- PGO: https://en.wikipedia.org/wiki/Profile-guided_optimization
- https://wiki.mozilla.org/Abstract_Interpretation
- https://en.wikipedia.org/wiki/Threaded_code
- https://en.wikipedia.org/wiki/Branch_table
- https://eli.thegreenplace.net/2012/07/12/computed-goto-for-efficient-dispatch-tables
- https://en.wikipedia.org/wiki/Register_allocation
- Top Down Operator Precedence: http://crockford.com/javascript/tdop/tdop.html
- Pratt parsing made easy: http://journal.stuffwithstuff.com/2011/03/19/pratt-parsers-expression-parsing-made-easy/
- Criticisms on BNF and Pratt Parsing in rust(Using binding power concept which is different than mainstream single power assigning methods): https://matklad.github.io/2020/04/13/simple-but-powerful-pratt-parsing.html
- CFGs: http://nlab-pages.s3.us-east-2.amazonaws.com/nlab/show/context-free+grammar
- A Tour of Safe Tracing GC Designs in Rust: https://manishearth.github.io/blog/2021/04/05/a-tour-of-safe-tracing-gc-designs-in-rust/
- Devirtualization in LLVM: https://dl.acm.org/doi/10.1145/3135932.3135947
- When can the C++ compiler devirtualize a call? : https://quuxplusone.github.io/blog/2021/02/15/devirtualization/
- The Power of devirtualization: https://marcofoco.com/the-power-of-devirtualization/
- EBNF: https://www.gimtec.io/articles/ebnf/
- Stack Frames: https://stackoverflow.com/questions/10057443/explain-the-concept-of-a-stack-frame-in-a-nutshell
- Chomsky hierarchy: https://www.geeksforgeeks.org/chomsky-hierarchy-in-theory-of-computation/
- Closure Conversion: https://matt.might.net/articles/closure-conversion/
- Lambda Lifting: https://stackoverflow.com/questions/592584/what-is-lambda-lifting
- Abstract vs Concrete Syntax Trees: https://eli.thegreenplace.net/2009/02/16/abstract-vs-concrete-syntax-trees/
- Type Inference : https://papl.cs.brown.edu/2020/Type_Inference.html
- Parametric Polymorphism: https://papl.cs.brown.edu/2020/para-poly.html
- TypeScript / How the compiler compiles: https://www.huy.rocks/everyday/04-01-2022-typescript-how-the-compiler-compiles
- https://towardsdev.com/rust-techniques-for-compiler-engineers-9a5368f7037b
- https://sunfishcode.github.io/blog/2018/10/22/Canonicalization.html
- Branch/cmove and compiler optimizations: https://kristerw.github.io/2022/05/24/branchless/
- Cranelift, Part 4: A New Register Allocator: https://cfallin.org/blog/2022/06/09/cranelift-regalloc2/
- Immix collection algorithm for GCs: https://wingolog.org/archives/2022/06/15/defragmentation
- https://wiki.nikiv.dev/compilers/
- Compiler Adventures, part 1: No-op Instructions: https://medium.com/@predrag.gruevski/compiler-adventures-part-1-no-op-instructions-c084358c7864
- Rambles around computer science: https://www.humprog.org/~stephen/blog/2022/08/03/#elf-symbol-wrapping-via-replacement
- Parent links in Go ASTs: https://eli.thegreenplace.net/2022/parent-links-in-go-asts/
- Dora: Implementing a JIT-compiler with Rust: https://dinfuehr.github.io/blog/dora-implementing-a-jit-compiler-with-rust/
- Tracing JIT: https://en.wikipedia.org/wiki/Tracing_just-in-time_compilation
- Understanding JIT Optimizations by Decompilation: https://www.infoq.com/presentations/jit-optimize-decompile-shopify/
- Understand the Trade-offs of Using Compilers for Java Applications: https://www.infoq.com/presentations/tradeoffs-java-compilers/
- The Solid-State Register Allocator: https://www.mattkeeter.com/blog/2022-10-04-ssra/
- Reverse Linear Scan Allocation is probably a good idea: http://brrt-to-the-future.blogspot.com/2019/03/reverse-linear-scan-allocation-is.html
- Zig Compiler Internals: https://mitchellh.com/zig
- Syntax Design: https://cs.lmu.edu/~ray/notes/syntaxdesign/
- When is JIT Faster Than A Compiler?: https://shopify.engineering/when-jit-faster-than-compiler
- Incremental parsing in go: https://dev-nonsense.com/posts/incremental-parsing-in-go/
- Syntax Design: https://cs.lmu.edu/~ray/notes/syntaxdesign/
- Building the fastest Lua interpreter.. automatically!: https://sillycross.github.io/2022/11/22/2022-11-22/ ( HN Thread: https://news.ycombinator.com/item?id=33711583 )
- Parsing Protobuf at 2+GB/s: How I Learned To Love Tail Calls in C: https://blog.reverberate.org/2021/04/21/musttail-efficient-interpreters.html
- How different compiler optimizations work: https://predr.ag/tags/compiler-adventures/
- Mark and sweep Boehm Collector!: https://hboehm.info/gc/
- Faster virtual machines: Speeding up programming language execution: https://mort.coffee/home/fast-interpreters/
- Adding For Loops to an Interpreter: https://healeycodes.com/adding-for-loops-to-an-interpreter
- Why We Need to Know LR and Recursive Descent Parsing Techniques: https://tratt.net/laurie/blog/2023/why_we_need_to_know_lr_and_recursive_descent_parsing_techniques.html
- Really nice read on different optimizations and challenges in C# compiler: http://joeduffyblog.com/2015/12/19/safe-native-code/
- Includes explanation of 3-staged compilers: https://jyn.dev/2023/01/12/Bootstrapping-Rust-in-2023.html
- A deep dive into interpreter instruction dispatching techniques: https://www.jonathanmueller.dev/talk/meetingcpp2022/
- Distinguishing an Interpreter from a Compiler: https://tratt.net/laurie/blog/2023/distinguishing_an_interpreter_from_a_compiler.html
- A really nice read on JITting/speculation in js core: https://webkit.org/blog/10308/speculation-in-javascriptcore/
- Type Inference based on Hindley-Milner ( HM from implementation perspective ): https://veera.app/type_inference.html
- Top Down LR Parsing: https://pavpanchekha.com/blog/top-down-lr.html
- Valiant's Parser: https://rahul.gopinath.org/post/2023/03/16/valiant-parser/
- A collection of PL Resources: https://bernsteinbear.com/pl-resources/
- Constructing human grade parsers, how to handle errors nicely in parsers: https://duriansoftware.com/joe/constructing-human-grade-parsers
- Resilient LL Parsing Tutorial: https://matklad.github.io/2023/05/21/resilient-ll-parsing-tutorial.html
- Writing a linux debugger: https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/
- The AST Typing Problem: http://blog.ezyang.com/2013/05/the-ast-typing-problem/
- On Leaning Compilers and Programming Languages: https://www.craigstuntz.com/posts/2023-10-13-learning-compilers-and-programming-languages.html
- Interesting read on how to leverage LLVM IR to hunt those corner optimizations!: https://tigerbeetle.com/blog/2023-07-26-copy-hunting/
- Core of JIT, just this: https://bpa.st/6XIA
- Scanner-Driven Parser Development: https://depth-first.com/articles/2019/01/22/scanner-driven-parser-development/
- Building a high performance JSON parser: https://dave.cheney.net/paste/gophercon-sg-2023.html
- Nice intro understanding to terms in LTO and what it is: https://convolv.es/guides/lto/
- Compiler Resources: https://gist.github.com/RealNeGate/d0d45b74d7352872d4cf2470a600fbbb
- How JIT Compilers are Implemented and Fast: Pypy, LuaJIT, Graal and More: https://kipp.ly/jits-impls/

## Blog series/Articles collection:

- https://dev.to/cad97/crafting-ide-ready-compilers-500o
- LLVM Internals: https://blog.yossarian.net/2021/09/14/LLVM-internals-part-3-from-bitcode-to-IR
- https://eli.thegreenplace.net/
- https://blog.regehr.org/
- https://kristerw.blogspot.com/
- http://lambda-the-ultimate.org/
- https://blog.regehr.org/archives/category/compilers
- https://lowlevelbits.org/
- https://jesper.sikanda.be/blog.html
- https://blog.regehr.org/
- Let's build a compiler: https://compilers.iecc.com/crenshaw/
- The GNU C Preprocessor Internals: https://gcc.gnu.org/onlinedocs/cppinternals/

## Reddit and twitter threads:

- https://www.reddit.com/r/learnprogramming/comments/5hwo3x/whats_the_best_resource_to_walk_me_through_making/
- Good compiler books: https://news.ycombinator.com/item?id=136875
- https://www.reddit.com/r/rust/comments/q0ttgx/where_would_i_start_making_a_compiler_in_rust/
- https://www.reddit.com/r/LLVM/comments/qly49y/how_to_build_a_compiler_with_llvm_and_mlir_12/
- https://www.reddit.com/r/programming/comments/qn8qqb/how_to_learn_compilers_llvm_edition/
- The web archive of the comp.compilers newsgroup, under the same management since 1986: https://twitter.com/compcompilers
- https://www.reddit.com/r/ProgrammingLanguages/comments/qm41w2/anybody_have_tips_for_writing_a_recursive_descent/
- https://www.reddit.com/r/LLVM/comments/nfmalh/llvm_backend_for_custom_target/
- Good books to start writing compilers: https://www.reddit.com/r/Compilers/comments/sxgvxo/good_books_to_start_writing_compilers/
- Where can I learn how code formatters are written?: https://www.reddit.com/r/Compilers/comments/u6scwd/where_can_i_learn_how_code_formatters_are_written/
- Min. requirements for a Self-Hosting Compilers: https://www.reddit.com/r/Compilers/comments/u8vzsy/selfhosting_compilers/
- Resources for building a type-checker: https://www.reddit.com/r/ProgrammingLanguages/comments/v5zwlw/resources_for_building_a_typechecker/
- Benefits of `nop` in a VM instruction set: https://www.reddit.com/r/ProgrammingLanguages/comments/xw75mw/are_there_any_benefits_to_defining_an_explicit/
- Where can I find resources and guides on how to build compiler backends?: https://www.reddit.com/r/ProgrammingLanguages/comments/1079qgm/where_can_i_find_resources_and_guides_on_how_to/

## Repos:

- https://github.com/aalhour/awesome-compilers
- https://github.com/vtudose/Let-s-build-a-compiler
- https://github.com/returntocorp/semgrep
- A miniature model of the Typescript compiler, intended to teach the structure of the real Typescript compiler: https://github.com/sandersn/mini-typescript
- LR(1) parser generator for Rust: https://github.com/lalrpop/lalrpop
- An incremental programming language: https://github.com/vmware/differential-datalog
- https://github.com/antonmedv/ultra-tiny-compiler
- The Witchcraft Compiler Collection: https://github.com/endrazine/wcc
- It's a New Kind of Wrapper for Exposing LLVM (Safely): https://github.com/TheDan64/inkwell
- https://github.com/TimelyDataflow/differential-dataflow
- https://github.com/vmware/differential-datalog
- https://github.com/softdevteam/grmtools
- https://github.com/llvm/llvm-project
- LLVM IR in natural Rust data structures: https://github.com/cdisselkoen/llvm-ir
- All LLVM's analysis and transform passes: https://github.com/llvm/llvm-project/blob/main/llvm/docs/Passes.rst
- A massively parallel, optimal functional runtime in Rust : https://github.com/Kindelia/HVM
- A parser library for humans with powerful error recovery: https://github.com/zesterer/chumsky
- ISLE: Instruction Selection/Lowering Expressions DSL: https://github.com/bytecodealliance/wasmtime/tree/main/cranelift/isle
- A curated list of static analysis (SAST) tools for all programming languages, config files, build tools, and more. The focus is on tools which improve code quality: https://github.com/analysis-tools-dev/static-analysis
- A curated list of dynamic analysis tools for all programming languages, binaries, and more: https://github.com/analysis-tools-dev/dynamic-analysis
- Distributed compiler with a central scheduler to share build load: https://github.com/icecc/icecream
- Compiler optimizer for arbitrary control flow based on equality saturation: https://github.com/jameysharp/optir
- A massively parallel, optimal functional runtime in Rust: https://github.com/Kindelia/HVM
- Create ridiculously fast Lexers: https://github.com/maciejhirsz/logos
- A Compiler writing journey: https://github.com/DoctorWkt/acwj/
- A lightweight LLVM python binding for writing JIT compilers: https://github.com/numba/llvmlite
- Graph based intermediate representation and backend for optimising compilers: https://github.com/libfirm/libfirm
- A self-hosting and educational C optimizing compiler: https://github.com/sysprog21/shecc
- https://github.com/wdv4758h/awesome-jit
- A list of dead JIT compiler projects for CPython: https://github.com/markshannon/JIT_graveyard
- Open deep learning compiler stack for cpu, gpu and specialized accelerators: https://github.com/apache/tvm/

## Grammars:

- http://marvin.cs.uidaho.edu/Teaching/CS445/c-Grammar.pdf

## Tools:

- Generating scanners from regexs: http://dinosaur.compilertools.net/lex/
- Generating scanners from regexs: https://github.com/westes/flex
- https://llvm.org/docs/Bugpoint.html

## Videos:

- The Golden Age of Compiler Design in an Era of HW/SW Co-design by Dr. Chris Lattner
  : https://www.youtube.com/watch?v=4HgShra-KnY
- Chris Lattner: Compilers, LLVM, Swift, TPU, and ML Accelerators | Lex Fridman Podcast #21: https://www.youtube.com/watch?v=yCd3CzGSte8
- CppCon 2019: Matt Godbolt “Compiler Explorer: Behind The Scenes”: https://www.youtube.com/watch?v=kIoZDUd5DKw&t=192s
- Cliff Click is famous for writing the original hot-spot JIT compiler for the Java programming language. He is a compiler guru, and conducts a weekly compiler club that is open to anyone who wants to join. This is great opportunity to learn from someone who really knows a thing or two about compilers and how to implement them: https://www.youtube.com/channel/UCbutMk6cKrH8q4sJyQHGPVQ
- https://www.snsystems.com/technology/tech-blog/improving-debug-variable-location-coverage-by-using-even-more-ssa
- Ownership SSA: https://www.youtube.com/watch?v=qy3iZPHZ88o
- What is bytecode?: https://www.youtube.com/watch?v=mgRXdgPcYc0
- Challenges In Analyzing and Optimizing Parallel Programs: https://www.youtube.com/watch?v=UdxZ8YqJlBE
- Making a Compiler for fun, from scratch: https://www.youtube.com/playlist?list=PLysa8wRFCssxGKj_RxBWr3rwmjEYlJIpa
- Programming Language with LLVM: https://www.youtube.com/watch?v=Lvc8qx8ukOI

## Videos collection:

- Tim Morgan's yt channel: https://www.youtube.com/c/TimMorgan/videos
- Video resources to learn about writing compilers/interpreters: https://www.reddit.com/r/Compilers/comments/wlm23e/video_resources_to_help_learn/

## Courses:

- Awesome course: https://www.cs.cornell.edu/courses/cs6120/2020fa/self-guided/
- https://suif.stanford.edu/dragonbook/
- https://iucompilercourse.github.io/IU-P423-P523-E313-E513-Fall-2020/
- https://iucompilercourse.github.io/tutorial-web-page/
- Compiler Design (Theory) course with video lectures?: https://www.reddit.com/r/Compilers/comments/10dpnky/compiler_design_theory_course_with_video_lectures/

## Books:

- https://www.cs.princeton.edu/~appel/modern/ml/
- https://gcc.gnu.org/wiki/ListOfCompilerBooks
- https://cglab.ca/~michiel/TheoryOfComputation/TheoryOfComputation.pdf
- Writing compiler in Go: https://compilerbook.com/
- Writing interpreter in Go: https://interpreterbook.com/
- PRACTICAL COMPILER CONSTRUCTION: A No-nonsense Tour through a C Compiler: http://t3x.org/reload/
- https://www3.nd.edu/~dthain/compilerbook/
- Compiling to assembly from scratch: https://keleshev.com/compiling-to-assembly-from-scratch/
- Static Program Analysis: https://cs.au.dk/~amoeller/spa/
- Writing Interpreters in Rust: a Guide: https://rust-hosted-langs.github.io/book/introduction.html
- Understanding and Writing Compilers: A do-it-yourself guide: https://www.amazon.com/Understanding-Writing-Compilers-do-yourself/dp/0333217322
- Static Program Analysis: https://cs.au.dk/~amoeller/spa/
- https://shop.elsevier.com/books/engineering-a-compiler/cooper/978-0-12-088478-0
- A book about compiling Racket and Python to x86-64 assembly: https://github.com/IUCompilerCourse/Essentials-of-Compilation

## Interesting rust-analyzer issues:

- Investigate node tracking: https://github.com/rust-analyzer/rust-analyzer/issues/9649

## Podcasts:

- Cliff Click's podcast: https://player.fm/series/programming-and-performance-with-cliff-click-1549714

I am a PL enthusiast, have been hanging around in PL communities for a while. Compilers and their internals peak my interest the most, also one of the reasons, I started contributing to various upstream rust tooling projects, they are their own compiler implementations but somehow lesser complex :P
