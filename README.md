# Conway's Game of Life
Exploring [WebAssembly][wasm] by building [Conway's Game of Life][gol].

<div align="center">
  <img src="https://github.com/asher-gh/conways_game_of_life_wasm/assets/74317567/9afbf808-719c-49c0-8947-8a4c3cf90ea0"
    width=400px>
</div>

[wasm]: https://webassembly.org/
[gol]: https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

## 🚴 Usage

1. Install [`wasm-pack`](https://rustwasm.github.io/wasm-pack/installer/) if not installed already.

```sh
cargo install wasm-pack
```

1. Use `wasm-pack` to compile `wasm` and generate JS bindings

```sh
# ./$CARGO_ROOT
wasm-pack build
```

1. Install npm dependencies (from `./www` directory)

```sh
# ./$CARGO_ROOT/www
npm i
```

1. Start the dev server

```sh
# ./$CARGO_ROOT/www
npm run start
```
