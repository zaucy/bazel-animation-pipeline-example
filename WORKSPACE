# workspace(name = "com_github_zaucy_bazel_animation_pipeline_example")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "rules_blender",
    strip_prefix = "rules_blender-0498f84bbbf7005e72621821ce316a73536de9b4",
    urls = ["https://github.com/zaucy/rules_blender/archive/0498f84bbbf7005e72621821ce316a73536de9b4.zip"],
    sha256 = "8a869bb2d158f078e15ae3accac655b5f5175c14329a634dfa941f207a15df6a",
)

load("@rules_blender//:index.bzl", "blender_repositories")
blender_repositories()

http_archive(
    name = "rules_imagemagick",
    strip_prefix = "rules_imagemagick-f8755fd2ec7d1271bd11a3a817af35225cb4f858",
    urls = ["https://github.com/zaucy/rules_imagemagick/archive/f8755fd2ec7d1271bd11a3a817af35225cb4f858.zip"],
    sha256 = "e48640e20a8f2c39548fb1fe86aa7e476e906031412d5036c7f71b0731c7b062",
)

load("@rules_imagemagick//:index.bzl", "imagemagick_repositories")
imagemagick_repositories()
