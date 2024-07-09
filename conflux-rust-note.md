# Note about conflux-rust

For the code under a specified path, we are aware that it contains a substantial amount of unsafe code, which leads to undefined behavior. Since Conflux has extensive test code, we do not consider it a bug, when code that might cause undefined behavior in future Rust versions but does not lead to unexpected behavior currently.

Therefore, a bug is only considered if it meets all the following conditions:

1. In actual operation, the input might not fulfill the unsafe function's required conditions.
2. In Rust 1.77, the compiler actually optimizes the illegal input into an unexpected behavior.

For example, `std::slice::from_raw_parts(data, len)` requires that `data` must not be a null pointer, even if `len` is zero. However, before Rust 1.52, the compiler did not optimize the input where `data` is a null pointer and `len` is zero into a different behavior.
