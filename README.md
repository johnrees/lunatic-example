## install [cargo wasi](https://bytecodealliance.github.io/cargo-wasi)

`curl https://wasmtime.dev/install.sh -sSf | bash`

`cargo install cargo-wasi`

## install [lunatic](https://lunatic.solutions/)

`brew tap lunatic-solutions/lunatic`

`brew install lunatic`

## create rust app

`cargo new example`

`cargo build --release --target=wasm32-wasi`

## run with lunatic

`lunatic target/wasm32-wasi/release/example.wasm`


