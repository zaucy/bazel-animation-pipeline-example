# Bazel animation pipeline example

Example repository for using [Bazel](https://bazel.build) as a rendering pipeline

Tools used in this repository include:

* [Blender](https://www.blender.org/) ([bazel rule](https://github.com/zaucy/rules_blender))
* [ImageMagick](https://imagemagick.org/) ([bazel rule](https://github.com/zaucy/rules_imagemagick))

## How to build

Download and install [Bazel](https://bazel.build) and run:

```sh
bazel build //blender/2d
```

## License

MIT
