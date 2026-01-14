# Rustlings Exercises: Turbin3 Accelerated Task Completion

This repository tracks the completion of core Rust fundamentals as part of the **Turbin3 Accelerated Program**. The exercises involve interactive debugging and problem-solving to master the language's safety and performance features. Each completion is mapped to specific chapters in the official Rust Book.

## Turbin3 Accelerated Curriculum Overview

The following core modules have been completed as part of the accelerated learning track:

- **Variables & Functions:** Mastering immutability, shadowing, and type signatures.
- **Control Flow & Primitives:** Implementing logic with `if` expressions and working with basic data types like arrays and slices.
- **Memory Management:** Understanding Ownership, Borrowing, and Move Semantics.
- **Data Structures:** Organizing data using Structs, Enums, Strings, and Hash Maps.
- **Error Handling:** Using `Option` for optional values and `Result` for recoverable errors.
- **Advanced Patterns:** Implementing Generics, Traits, and Lifetimes to create flexible, safe code.
- **System Tools:** Utilizing Smart Pointers (`Box`, `Rc`, `Arc`), Concurrency with Threads, and Metaprogramming with Macros.

## Program Structure

- **/exercises:** Starter files with intentional compiler errors or missing logic provided as primary learning tasks.
- **/solutions:** Verified implementations that are automatically populated upon successful exercise completion.
- **/quizzes:** Integrated knowledge checks used to verify cross-module competency.

## How to Verify Completion

This project is a standard Rust workspace managed by Cargo. Task completion is verified through the `rustlings` tool or by running the following command to check all exercises in the workspace:

```bash
cargo test
```
