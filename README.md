## ⚙️🦀 Rust-WASM Boilerplate
Using the [Rust and WebAssembly Working Group](https://github.com/rustwasm)'s `wasm-pack` crate, which lets you compile rust code into WASM, and provides an interface with JavaScript.

📖 Project built from this [Mozilla Developer Documentation Tutorial](https://developer.mozilla.org/en-US/docs/WebAssembly/Rust_to_Wasm)

### Getting Started

1. Clone the Repo:
   ```
   git clone https://github.com/jwhogg/rust-wasm-boilerplate
   ```
2. Build for web using a bundler:
   in the main dir:
   ```
   wasm-pack build --target bundler
   ```
3. Install webpack:
   ```
   npm i -D webpack@5 webpack-cli@5 webpack-dev-server@4 copy-webpack-plugin@11
   ```
4. Serve the site:
   ```
   cd site
   ```
   ```
   npm run serve
   ```
5. All done! Navigate to `http://localhost:8080`, and you should see a pop-up: `Hello, WebAssembly with npm!`
