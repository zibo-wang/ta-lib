cc_library(
    name = "ta_common_headers",
    hdrs = [
        "ta_common.h",
        "ta_defs.h",
    ],
    includes = ["."],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "ta_func_headers",
    hdrs = [
        "ta_func.h",
    ],
    includes = ["."],
    visibility = ["//visibility:public"],
    deps = [":ta_common_headers"],
)

cc_library(
    name = "ta_abstract_headers",
    hdrs = [
        "ta_abstract.h",
    ],
    includes = ["."],
    visibility = ["//visibility:public"],
    deps = [":ta_common_headers"],
)

cc_library(
    name = "ta_libc_headers",
    hdrs = [
        "ta_libc.h",
    ],
    includes = ["."],
    visibility = ["//visibility:public"],
    deps = [
        ":ta_abstract_headers",
        ":ta_common_headers",
        ":ta_func_headers",
    ],
)
