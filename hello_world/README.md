This is a simple rust program which prints the text "Hello World" to the screen.

For such simple applications, we can have a single rust source file although it is recommended to use 'cargo' tool to large projects.

The steps to run this program includes compiling it (using `rustc main.rs`) and running it (using `./main`).

Every executable rust program has a main function from where the execution starts.

The `println!` is a rust macro, which takes care of everything to print something to the screen. It is important to notice that it's a macro not a function. As per the docs, macros don't necessarily follows the same rules as functions.