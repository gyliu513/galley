package(default_visibility = ["//cmd:__subpackages__"])

load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = ["print.go"],
    visibility = ["//visibility:public"],
    deps = [
        "//pkg/version:go_default_library",
        "@com_github_spf13_cobra//:go_default_library",
    ],
)
