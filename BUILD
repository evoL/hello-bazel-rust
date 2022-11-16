load("@rules_rust//rust:defs.bzl", "rust_binary", "rust_doc")

package(default_visibility = ["//visibility:public"])

rust_binary(
  name = "hello_rust",
  srcs = ["src/main.rs"],
  deps = [],
)

rust_doc(
  name = "hello_rust_doc",
  crate = ":hello_rust",
)
