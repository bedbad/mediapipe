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


 cc_library(
    name = "ImageProcessing",
    srcs = ["ImageProcessing.cpp"],
    hdrs = ["ImageProcessing.h"],
  ) 

 cc_binary(
    name = "ImageProcessing",
    srcs = ["ImageProcessing.cpp"],
    deps = [":ImageProcessing"],
  )

 cc_library(
    name = "Keyboard",
    srcs = ["Keyboard.cpp"],
    hdrs = ["Keyboard.h"],
  ) 
 
cc_binary(
    name = "Keyboard",
    srcs = ["Keyboard.cpp"],
    deps = [":Keyboard"],
  ) 

cc_library(
    name = "MainWindow",
    srcs = ["MainWindow.cpp"],
    hdrs = ["MainWindow.h"],
  ) 

cc_binary(
    name = "MainWindow",
    srcs = ["MainWindow.cpp"],
    deps = [":MainWindow"],
  ) 

cc_library(
    name = "Monitor",
    srcs = ["Monitor.cpp"],
    hdrs = ["Monitor.h"],
  ) 

cc_binary(
    name = "Monitor",
    srcs = ["Monitor.cpp"],
    deps = [":Monitor],
  ) 

cc_library(
    name = "Mouse",
    srcs = ["Mouse.cpp"],
    hdrs = ["Mouse.h"],
  ) 
            
 cc_binary(
    name = "Mouse",
    srcs = ["Mouse.cpp"],
    deps = [":Mouse"],
  ) 
                     
            
            
