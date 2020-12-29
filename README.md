# rust-webassembly
Playing with Rust and WebAssembly

## How to use Rust to compile to WebAssembly?

### Add a WebAssembly target

Assuming that Rust is installed, we must install a _target_ for WebAssembly. A _target_ is a possible architecture that we can build a Rust program for. In our case, we want to install the WebAssembly target, by running `rustup target add wasm32-unknown-unknown`

### Use Cargo to compile Rust into a WebAssembly module

We want to run this command to convert our Rust project into a WebAssembly module:

```cargo build --target wasm32-unknown-unknown```


