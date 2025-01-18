cc_library(
    name = "ta_common",
    srcs = [
        "ta_global.c",
        "ta_retcode.c",
        "ta_version.c",
    ],
    hdrs = [
        "ta_global.h",
        "ta_magic_nb.h",
        "ta_memory.h",
        "ta_pragma.h",
    ],
    includes = [
        ".",
        "../../include",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//include:ta_common_headers",
        "//include:ta_func_headers",
    ],
)
