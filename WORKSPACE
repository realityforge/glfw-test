# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

GLFW_VERSION = "3.3.5"

GLFW_SHA256 = "a89bb6074bc12bc12fcd322dcf848af81b679ccdc695f70b29ca8a9aa066684b"

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "glfw",
    build_file = "@//third_party/glfw:glfw.BUILD.bazel",
    sha256 = GLFW_SHA256,
    strip_prefix = "glfw-{}".format(GLFW_VERSION),
    urls = ["https://github.com/glfw/glfw/archive/{}.zip".format(GLFW_VERSION)],
)

GLA_VERSION = "1.5"

GLA_SHA256 = "726729b2938f8747a359c9a3174977e278772d09a39ea43a9d1097bcb5697b71"

http_archive(
    name = "gla",
    sha256 = GLA_SHA256,
    strip_prefix = "gla-%s" % GLA_VERSION,
    url = "https://github.com/realityforge/gla/archive/refs/tags/v%s.tar.gz" % GLA_VERSION,
)
