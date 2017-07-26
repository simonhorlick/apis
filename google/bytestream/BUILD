package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load("@grpc_java//:java_grpc_library.bzl", "java_grpc_library")

proto_library(
    name = "bytestream_proto",
    srcs = ["bytestream.proto"],
    deps = [
        "//google/api:annotations_proto",
        "//google/protobuf:wrappers_proto",
    ],
)

java_proto_library(
    name = "bytestream_java_proto",
    deps = [":bytestream_proto"],
)

java_grpc_library(
    name = "bytestream_java_grpc",
    srcs = [":bytestream_proto"],
    deps = [":bytestream_java_proto"],
)
