# programmingRust
Learning Rust ...Should be fun!

##install rust and cargo on unix
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Then run 
```
rustup update
```
Cargo is the Package manager and build-tool for the rust language.

build your project with 
```
cargo build
```
run your project with 
```
cargo run
```
test your project with 
```
cargo test
```
build documentation for your project with 
```
cargo doc
```
publish a library to crates.io with 
```
cargo publish
```

### Create new rust project
```
cargo new hello-rust
```

This will generate a new directory called hello-rust with the following files:

hello-rust
|- Cargo.toml
|- src
  |- main.rs
Cargo.toml is the manifest file for Rust. It’s where you keep metadata for your project, as well as dependencies.

src/main.rs is the entry point for your application code.
