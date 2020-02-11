load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

swift_library(
    name = "App",
    srcs = glob(["*.swift"]),
    module_name = "App",
    visibility = ["//visibility:public"],
    deps = [
        "//ios-app/Source/Modules/Core",
    ],
)