# eset-rs

A simple library for flags like enums.

Unlike crates like `enumset` or `bitflags`,
this crate relies entirely on rust's type system to function,
with no derive macros required.

This crate does not provide derive functionalities but instead rely on
the user to implement the `ReprEnum` trait. The user can choose to use
crates like `num_enum` and
`strum` to provide additional functionalities.
