load("@rules_proto_grpc//java:defs.bzl", "java_grpc_library")

proto_library(
    name = "greeter_grpc",
    srcs = [
        "greeter.proto",
    ]
)

java_grpc_library(
    name = "greeter_java_library",
    deps = [":greeter_grpc"],
    visibility = ["//visibility:public"],
)
