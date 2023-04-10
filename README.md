# tetris-edge-rs

### Build
`cargo build --target wasm32-unknown-unknown`

### Compile to wasm to js
`wasm-bindgen --target=web ./target/wasm32-unknown-unknown/debug/tetris_edge_rs.wasm --out-dir=pkg`

### Run locally
`npx serve .`
