package(default_visibility = ["//visibility:public"])
licenses(["notice"])

cc_library(
    name = "yoga",
    hdrs = glob([
      "yoga/*.h"
    ]),
    srcs = glob([
      "ypga/*.cpp",
    ]),
    linkstatic = 1,
    includes = ["."],
    copts = [
      '-fno-omit-frame-pointer',
      '-fexceptions',
      '-Wall',
      '-Werror',
      '-std=c++1y',
      '-fPIC'
    ]
)