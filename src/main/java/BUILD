java_binary(
    name = "server",
    srcs = glob(["**/*.java"]),
    main_class = "io.grpc.examples.helloworld.HelloWorldServer",
    deps = [
        "//src/main/proto:greeter_java_library",
    ],
)

java_binary(
    name = "client",
    srcs = glob(["**/*.java"]),
    main_class = "io.grpc.examples.helloworld.HelloWorldClient",
    deps = [
        "//src/main/proto:greeter_java_library",
    ],
)
