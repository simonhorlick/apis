package(default_visibility = ["//visibility:public"])

licenses(["notice"])

proto_library(
    name = "date_proto",
    srcs = ["date.proto"],
)

proto_library(
    name = "dayofweek_proto",
    srcs = ["dayofweek.proto"],
)

proto_library(
    name = "latlng_proto",
    srcs = ["latlng.proto"],
)

proto_library(
    name = "money_proto",
    srcs = ["money.proto"],
)

java_proto_library(
    name = "money_java_proto",
    deps = [":money_proto"],
)

proto_library(
    name = "postal_address_proto",
    srcs = ["postal_address.proto"],
)

proto_library(
    name = "timeofday_proto",
    srcs = ["timeofday.proto"],
)
