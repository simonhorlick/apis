package(default_visibility = ["//visibility:public"])

licenses(["notice"])

proto_library(
    name = "http_proto",
    srcs = ["http.proto"],
)

proto_library(
    name = "annotations_proto",
    srcs = ["annotations.proto"],
    deps = [
        ":http_proto",
        "//google/protobuf:descriptor_proto",
    ],
)
