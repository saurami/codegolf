+ Run tests in top-level file with `cargo`

  By default, `cargo` runs tests only in default files (`main.rs` / `lib.rs`). If tests are present in another file, it has to be referenced as a module in either of the default files. Cargo will not compile any file(s) in the source (`./src`) directory.
