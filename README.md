# rust-office-kernel

This is the kernel lib of [Rust-Office](https://github.com/rustytsuki/rust-office), written in pure Rust programming language. Due to lack of a stable ABI in Rust lib, I've had to export the library to a standard C library and provide a C header file. Additionally, there's a wasm lib with a JavaScript/TypeScript interface, allowing for browser-based utilization. The pros is: you can integrate the kernel not only with Rust but also with almost any other programming languages.

How to use the lib? see [Rust-Office](https://github.com/rustytsuki/rust-office), it shows you how to integrated with the lib.

