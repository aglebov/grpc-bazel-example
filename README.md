# grpc-example

Adapted from the example in https://github.com/grpc/grpc-java using the rules-proto-grpc library (https://rules-proto-grpc.github.io/rules_proto_grpc).

To compile, run the following commands from the root directory of the checkout:
```
bazel build //src/main/java:server
bazel build //src/main/java:client
```

Start the server:
```
bazel build //src/main/java:server
```

From a different terminal, run the client:
```
bazel build //src/main/java:client Artem
```
