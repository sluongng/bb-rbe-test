load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_buildbuddy_buildbuddy_toolchain",
    sha256 = "b12273608db627eb14051eb75f8a2134590172cd69392086d392e25f3954ea6e",
    strip_prefix = "buildbuddy-toolchain-8d5d18373adfca9d8e33b4812915abc9b132f1ee",
    urls = ["https://github.com/buildbuddy-io/buildbuddy-toolchain/archive/8d5d18373adfca9d8e33b4812915abc9b132f1ee.tar.gz"],
)

load("@io_buildbuddy_buildbuddy_toolchain//:deps.bzl", "buildbuddy_deps")

buildbuddy_deps()

load("@io_buildbuddy_buildbuddy_toolchain//:rules.bzl", "buildbuddy")

buildbuddy(name = "buildbuddy_toolchain")
