load("//ReactNative:DEFS.bzl", "rn_android_library", "YOGA_TARGET", "react_native_dep", "react_native_target")

rn_android_library(
    name = "art",
    srcs = glob(["*.java"]),
    visibility = [
        "PUBLIC",
    ],
    deps = [
        YOGA_TARGET,
        react_native_dep("libraries/fbcore/src/main/java/com/facebook/common/logging:logging"),
        react_native_dep("third-party/java/jsr-305:jsr-305"),
        react_native_target("java/com/facebook/react/bridge:bridge"),
        react_native_target("java/com/facebook/react/common:common"),
        react_native_target("java/com/facebook/react/module/annotations:annotations"),
        react_native_target("java/com/facebook/react/uimanager:uimanager"),
        react_native_target("java/com/facebook/react/uimanager/annotations:annotations"),
    ],
)
