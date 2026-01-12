```uv python pin 3.12```
```uv init```
```uv venv```
```uv add grpcio-tools```

python3 -m grpc-tools.protoc -I protos --python_out=. --grpc_python_out=. protos/<file-name> # usually server-name.proto