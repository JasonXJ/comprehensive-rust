# Fearless Concurrency

Rust has great support for concurrency and its powerful type system is able to
prevent many concurrency bugs at compile time. This is often referred to as
_fearless concurrency_ since you can rely on the compiler to ensure correctness
at runtime.

<details>

- Rust lets us access OS concurrency primitives such as threads and mutexes.
- We will see how the type system gives prevents certain kinds of concurrency
  bugs when using multiple threads.

</details>