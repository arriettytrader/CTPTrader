package(default_visibility = ["//visibility:public"])

cc_binary(
    name = "consumer",
    srcs = [
		"consumer.cpp"
	],
    deps = [
        "@boost//:lockfree",
        "@boost//:interprocess",
        "@boost//:system",
        "@boost//:thread",
	],
    linkopts = [
        "-lrt"
    ],
)

cc_binary(
    name = "producer",
    srcs = [
		"producer_test.cpp"
	],
    deps = [
        "@boost//:lockfree",
        "@boost//:interprocess",
        "@boost//:system",
        "@boost//:thread",
	],
    linkopts = [
        "-lrt"
    ],
)

cc_binary(
    name = "main",
    srcs = [
		"main.cpp"
	],
    deps = [
        "@boost//:lockfree",
        "@boost//:interprocess",
        "@boost//:system",
        "@boost//:thread",
        "@boost//:circular_buffer",

	],
    linkopts = [
        "-lrt"
    ],
)

cc_binary(
    name = "array",
    srcs = [
		"array.cpp"
	],
    deps = [
        "@boost//:lockfree",
        "@boost//:interprocess",
        "@boost//:system",
        "@boost//:thread",
        "@boost//:circular_buffer",

	],
    linkopts = [
        "-lrt"
    ],
)

cc_binary(
    name = "folly_blocking_q",
    srcs = [
		"folly_blocking_q.cpp"
	],
    deps = [
        "@folly//:folly",
        "@com_google_googletest//:gtest_main",
	],
    copts = [
        "-std=c++14",
    ],
)
