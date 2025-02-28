load("@envoy//bazel:envoy_build_system.bzl", "envoy_mobile_package")
load("@envoy_mobile//bazel:apple.bzl", "envoy_mobile_swift_test")
load("@rules_cc//cc:defs.bzl", "objc_library")

licenses(["notice"])  # Apache 2

envoy_mobile_package()

envoy_mobile_swift_test(
    name = "end_to_end_networking_test",
    srcs = [
        "EndToEndNetworkingTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "cancel_stream_test",
    srcs = [
        "CancelStreamTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "engine_api_test",
    srcs = [
        "EngineApiTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
    ],
)

envoy_mobile_swift_test(
    name = "filter_reset_idle_test",
    srcs = [
        "FilterResetIdleTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "grpc_receive_error_test",
    srcs = [
        "GRPCReceiveErrorTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "idle_timeout_test",
    srcs = [
        "IdleTimeoutTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "key_value_store_test",
    srcs = [
        "KeyValueStoreTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "receive_data_test",
    srcs = [
        "ReceiveDataTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "receive_error_test",
    srcs = [
        "ReceiveErrorTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
    ],
)

envoy_mobile_swift_test(
    name = "reset_connectivity_state_test",
    srcs = [
        "ResetConnectivityStateTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "send_data_test",
    srcs = [
        "SendDataTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "send_headers_test",
    srcs = [
        "SendHeadersTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "send_trailers_test",
    srcs = [
        "SendTrailersTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "set_event_tracker_test",
    srcs = [
        "SetEventTrackerTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "set_event_tracker_test_no_tracker",
    srcs = [
        "SetEventTrackerTestNoTracker.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "set_logger_test",
    srcs = [
        "SetLoggerTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

envoy_mobile_swift_test(
    name = "cancel_grpc_stream_test",
    srcs = [
        "CancelGRPCStreamTest.swift",
    ],
    exec_properties = {
        "sandboxNetwork": "standard",
    },
    visibility = ["//visibility:public"],
    deps = [
        ":test_extensions",
        "//library/objective-c:envoy_engine_objc_lib",
        "//test/objective-c:envoy_test_server",
    ],
)

objc_library(
    name = "test_extensions",
    hdrs = [
        "TestExtensions.h",
    ],
    module_name = "TestExtensions",
    visibility = ["//visibility:public"],
    deps = [
        "@envoy_build_config//:test_extensions_no_autoregister",
    ],
)
