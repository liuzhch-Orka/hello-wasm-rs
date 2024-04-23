```shell
cargo install wasm-pack
wasm-pack build --target web
```
Now host the html
```shell
python -m http.server 8001
```
Go to http://localhost:8001