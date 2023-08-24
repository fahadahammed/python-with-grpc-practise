# python-with-grpc-practise

## How?

```bash
cd ../../example/helloworld
python -m grpc_tools.protoc -I../../example/helloworld/protos --python_out=. --pyi_out=. --grpc_python_out=. ../../example/helloworld/protos/helloworld.proto
```