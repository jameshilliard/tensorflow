load("//tensorflow/core/platform:rules_cc.bzl", "cc_library")

package(
    # copybara:uncomment default_applicable_licenses = ["//tensorflow:license"],
    default_visibility = [
        "//tensorflow:internal",
    ],
    licenses = ["notice"],
)

cc_library(
    name = "grpc_coordination_client",
    hdrs = ["grpc_coordination_client.h"],
    deps = [
        "//tensorflow/tsl/distributed_runtime/rpc/coordination:grpc_coordination_client",
    ],
)

cc_library(
    name = "grpc_coordination_service_impl",
    hdrs = ["grpc_coordination_service_impl.h"],
    deps = [
        "//tensorflow/tsl/distributed_runtime/rpc/coordination:grpc_coordination_service_impl",
    ],
)
