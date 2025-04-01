# Fibonacci Memoization Algorithm with Rust

For my **introduction to Rust**, I decided to develop an algorithm to **find the n-th term of the Fibonacci sequence** using the language.

This project is planned to be my first **self-guided code** to better understand key concepts of Rust, such as **ownership and borrowing**, as well as **fundamental programming concepts**, like functions, loops and control flow.

It is also a great way to gain **hands-on experience** with some libraries, standard methods, and tools while learning how to use Rust alongside a version control system, like *GitHub*.

## Main Features:
Being this project a simple introduction study to the language, features are fairly basics: a ***memoization* module that allow to optimize the algorithm** saving previous numbers founded in the sequence and a **timed log associated with the process duration**, allowing to notice the time to end the process.

## How to Run:

If you **copied** the code, you will need Rust installed on your machine, which includes **Cargo**: Rust tool to manage projects and handle libraries.

With Cargo, write in your terminal:

- `cargo run`: to compile and execute the code, or

- `cargo build`: to just compile the code, both can have the optional flag `--release`, that will generate an optimized executable of the code
Instead, if you choosed to just **install or copy the source code**, you can use **rustc** (default compiler for Rust) to compile your code directly, or use **Cargo** again to initiate a standardized project over the source code and then compile or run.

For the **rustc** option:

- Use the `rustc code_full_path.rs` command to compile the code in an executable

- If you are on **Windows** write `.\code_path.exe`, or `./code_path` in other OS's to run the executable

For **Cargo** option:

- In your favorite terminal, write `cargo init` to iniate the project using Cargo

- With your project created, use the previous introduced commands, *cargo run* or *cargo build* to compile and/or run your project
