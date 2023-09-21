# A simple Spin HTTP component in Python

The py2wasm plugin needs to be updated to the canary version in order for this to work. For simplicity, it's included under `./py2wasm-canary` and you can install it using the following command:

```shell
spin plugins install -f ./py2wasm-canary/py2wasm.json
```

To run this sample ensure you have installed the `llama2-chat` to the `.spin/ai-models` directory.

In one shell start the application:

```shell
spin build --up
```

In a second shell make a request:

```shell
curl -X POST --data '{"sentence":"Everything is awesome!"}' http://127.0.0.1:3000
```
