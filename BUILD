load("@bazel_skylib//rules:native_binary.bzl", "native_binary")

[native_binary(
    name = f.replace("/", "__"),
    src = f,
    visibility = ["//visibility:public"],
) for f in glob(["**/*_plugin"])]
