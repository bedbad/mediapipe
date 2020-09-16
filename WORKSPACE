workspace(name = "CameraMouseSuite")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "new_git_repository")

new_git_repository(
    name = "CameraMouseSuite",
    path = "https://github.com/bedbad/CMS-CP.git",
    build_file = "CameraMouseSuite.BUILD",
)

cc_binary(
    name = "CameraMouseSuite",
    srcs = ["main.cpp"],
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
    deps = [":Monitor"],
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
                    
 cc_library(
    name = "MouseControlModule",
    srcs = ["MouseControlModule.cpp"],
    hdrs = ["MouseControlModule.h"],
  ) 

  cc_binary(
    name = "MouseControlModule",
    srcs = ["MouseControlModule.cpp"],
    deps = [":MouseControlModule"],
  ) 

 cc_library(
    name = "Point",
    srcs = ["Point.cpp"],
    hdrs = ["Point.h"],
  )     
  
 cc_binary(
    name = "Point",
    srcs = ["Point.cpp"],
    deps = [":Point"],
  )     
  
cc_library(
    name = "Settings",
    srcs = ["Settings.cpp"],
    hdrs = ["Settings.h"],
  )    

cc_binary(
    name = "Settings",
    srcs = ["Settings.cpp"],
    deps = [":Settings"],
  )  

cc_library(
    name = "StandardTrackingModule",
    srcs = ["StandardTrackingModule.cpp"],
    hdrs = ["StandardTrackingModule.h"],
  )    

cc_binary(
    name = "StandardTrackingModule",
    srcs = ["StandardTrackingModule.cpp"],
    deps = [":StandardTrackingModule"],
  ) 

cc_library(
    name = "TemplateTrackingModule",
    srcs = ["TemplateTrackingModule.cpp"],
    hdrs = ["TemplateTrackingModule.h"],
  )    

cc_binary(
    name = "TemplateTrackingModule",
    srcs = ["TemplateTrackingModule.cpp"],
    deps = [":TemplateTrackingModule"],
  )  

 cc_library(
    name = "TrackingModule",
    srcs = ["TrackingModule.cpp"],
    hdrs = ["TrackingModule.h"],
  )    

 cc_binary(
    name = "TrackingModule",
    srcs = ["TrackingModule.cpp"],
    deps = [":TrackingModule"],
  )    

 cc_library(
    name = "VideoManagerSurface",
    srcs = ["VideoManagerSurface.cpp"],
    hdrs = ["VideoManagerSurface.h"],
  )    
    
  cc_binary(
    name = "VideoManagerSurface",
    srcs = ["VideoManagerSurface.cpp"],
    deps = [":VideoManagerSurface"],
  )      

 cc_library(
    name = "asmOpenCV",
    hdrs = ["asmOpenCV.h"],
  )    
    
  
