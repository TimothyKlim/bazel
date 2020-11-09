load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:utils.bzl", "maybe")
load("@bazel_tools//tools/cpp:cc_configure.bzl", "cc_configure")

# rules_cc is used in @bazel_tools//tools/cpp, so must be loaded here.
maybe(
    http_archive,
    "rules_cc",
    sha256 = "c855aad5f1d125104cfa8e8e7590205bc35c5e8418771ffd2cfde0922ef31775",
    strip_prefix = "rules_cc-7bd0e49cfb2237086df89dca9e6ba7a5a5dfb36d",
    urls = [
        "https://mirror.bazel.build/github.com/bazelbuild/rules_cc/archive/7bd0e49cfb2237086df89dca9e6ba7a5a5dfb36d.zip",
        "https://github.com/bazelbuild/rules_cc/archive/7bd0e49cfb2237086df89dca9e6ba7a5a5dfb36d.zip",
    ],
)

cc_configure()
