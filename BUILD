package(default_visibility = ["//visibility:public"])

package_group(
    name = "ta_lib_internal",
    packages = [
        "//src/ta_abstract/...",
        "//src/ta_common/...",
        "//src/ta_func/...",
    ],
)

exports_files([
    "LICENSE",
    "VERSION",
])

cc_library(
    name = "ta_lib",
    visibility = ["//visibility:public"],
    deps = [
        "//include:ta_libc_headers",
        "//src/ta_abstract",
        "//src/ta_common",
        "//src/ta_func",
    ],
)
