cc_library(
    name = "ta_abstract",
    srcs = [
        "frames/ta_frame.c",
        "ta_abstract.c",
        "ta_def_ui.c",
        "ta_func_api.c",
        "ta_group_idx.c",
    ],
    hdrs = [
        "frames/ta_frame.h",
        "ta_def_ui.h",
        "ta_frame_priv.h",
        "ta_java_defs.h",
    ],
    includes = [
        ".",
        "frames",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//include:ta_abstract_headers",
        "//src/ta_common",
    ],
)
