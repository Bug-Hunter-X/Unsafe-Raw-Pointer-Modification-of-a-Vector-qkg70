# Rust Raw Pointer Vector Modification Bug

This repository demonstrates a common error in Rust when using raw pointers to manipulate vectors.  Directly manipulating a vector's memory via a raw pointer without proper synchronization or bounds checking can result in data corruption or program crashes.

The `bug.rs` file showcases the problematic code, and `bugSolution.rs` provides a safer alternative using safe Rust techniques.

This example highlights the importance of carefully considering memory safety and using Rust's ownership and borrowing system to avoid these types of issues.