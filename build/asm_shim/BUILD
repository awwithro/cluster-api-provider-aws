package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "c.go",
        "textflag.h",
    ],
    cgo = True,
    importpath = "sigs.k8s.io/cluster-api-provider-aws/build/asm_shim",
    visibility = ["//visibility:public"],
)
