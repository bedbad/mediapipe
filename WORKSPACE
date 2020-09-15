workspace(name = "CameraMouseSuite")

load("@bazel_tools//tools/build_defs/repo:http.bzl")

cc_binary(
    name = "CameraMouseSuite",
    srcs = ["main.cpp"],
    compiler_flags = ["-threaded"],
    )

cc_library(
    name = "CameraMouseController",
    srcs = ["CameraMouseController.cpp"],
    hdrs = ["CameraMouseController.h"],
    ) 

cc_binary(
    name = "CameraMouseController",
    srcs = ["CameraMouseController.cpp"],
    deps = [":CameraMouseController"],
  )

cc_library(
    name = "ClickableLabel",
    srcs = ["ClickableLabel.cpp"],
    hdrs = ["ClickableLabel.h"],
  ) 

cc_binary(
    name = "ClickableLabel",
    srcs = ["ClickableLabel.cpp"],
    deps = [":ClickableLabel"],
  )
 
 cc_library(
    name = "FeatureInitializationModule",
    srcs = ["FeatureInitializationModule.cpp"],
    hdrs = ["FeatureInitializationModule.h"],
  ) 

cc_binary(
    name = "FeatureInitializationModule",
    srcs = ["FeatureInitializationModule.cpp"],
    deps = [":FeatureInitializationModule"],
  )


