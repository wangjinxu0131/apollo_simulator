load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "tools",
    includes = ["include"],
    hdrs = glob(["include/**/*"]),
    srcs = glob(["lib/**/*.so*"]),
    include_prefix = "modules/tools",
    strip_include_prefix = "include",
    visibility = ["//visibility:public"],
)