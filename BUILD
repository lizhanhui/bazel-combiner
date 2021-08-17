load("@combiner//bazel:combine.bzl", "my_cc_combine")
 
my_cc_combine(
    name = "hello_combined",
    # 这里将所有的静态库合并成一个静态库
    genstatic = True,
    output = "libcombined.a",
    deps = ["//libA:A", "//libB:B", "//libC:C"]
) 