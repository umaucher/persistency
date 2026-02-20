load("@rules_cc//cc:defs.bzl", "cc_binary")

cc_binary(
    name = "hello_kvs_world",
    srcs = ["main.cpp"],
    deps = [
        "@score_persistency//:kvs_cpp",
        "@score_baselibs//score/mw/log:console_only_backend",
    ],
)
