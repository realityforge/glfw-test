GLFW_VERSION = "3.3.5"

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "glfw",
    build_file = "@//third_party/glfw:glfw.BUILD.bazel",
    sha256 = "a89bb6074bc12bc12fcd322dcf848af81b679ccdc695f70b29ca8a9aa066684b",
    strip_prefix = "glfw-{}".format(GLFW_VERSION),
    urls = ["https://github.com/glfw/glfw/archive/{}.zip".format(GLFW_VERSION)],
)

GLA_VERSION = "1.3"

GLA_SHA256 = "f13d19c6bbc94ce70bea98ebdf89e52d91c6104ba4072f98d7f7bc1bac9c267c"

http_archive(
    name = "gla",
    sha256 = GLA_SHA256,
    strip_prefix = "gla-%s" % GLA_VERSION,
    url = "https://github.com/realityforge/gla/archive/refs/tags/v%s.tar.gz" % GLA_VERSION,
)
