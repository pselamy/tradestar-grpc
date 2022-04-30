load("@rules_proto_grpc//java:defs.bzl", "java_grpc_library")

java_grpc_library(
    name = "backtest_service_java_grpc",
    visibility = ["//visibility:public"],
    protos = ["@tradestar_protos//:backtest_service_proto"],
    deps = [
        "@tradestar_protos//:backtesting_java_proto",
    ],
)

java_grpc_library(
    name = "candle_service_java_grpc",
    visibility = ["//visibility:public"],
    protos = ["@tradestar_protos//:candle_service_proto"],
    deps = [
        "@tradestar_protos//:candles_java_proto",
        "@tradestar_protos//:indicators_java_proto",
        "@tradestar_protos//:instruments_java_proto",
        "@tradestar_protos//:time_java_proto",
    ],
)
