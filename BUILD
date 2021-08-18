load("@combiner//bazel:combine.bzl", "cc_combine")
 
cc_combine(
    name = "hello_combined",
    # 这里将所有的静态库合并成一个静态库
    genstatic = True,
    output = "libcombined.a",
    deps = ["//libA:A", "//libB:B", "//libC:C"]
) 

cc_combine(
    name = "hello_combined_shared",
    # 这里将所有的静态库合并成一个静态库
    genstatic = False,
    output = "libcombined.so",
    deps = ["//libB:B", "//libC:C"]
) 