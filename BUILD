load("@rules_proto_grpc//java:defs.bzl", "java_grpc_library")

java_grpc_library(
    name = "candle_service_java_grpc",
    protos = ["@tradestar_protos//:candle_service_proto"],
    deps = [
        "@tradestar_protos//:candles_java_proto",
        "@tradestar_protos//:instruments_java_proto",
    ],
)
