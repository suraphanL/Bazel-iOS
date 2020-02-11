load("@build_bazel_rules_apple//apple:ios.bzl", "ios_application")
load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

BUNDLE_ID = "com.rawd.bazel.main"

ios_application(
    name = "ios-app",
    bundle_id = BUNDLE_ID,
    families = ["iphone"],
    minimum_os_version = "13.0",
    infoplists = ["//ios-app/Resources:Info_plist"],
    visibility = ["//visibility:public"],
    deps = ["//ios-app/Source/App:App"],
)
