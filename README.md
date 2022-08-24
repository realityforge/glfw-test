# glfw-test

This project is going to be an experiment creating Vulkan, OpenGL and/or Metal apps. The experiment is intended to support presenting the same scene graph (which may simply be a colored triangle) in multiple windows, in multiple monitors, in multiple APIs. Later it will support receiving input in multiple of these windows. All of this will be done using GLFW to experiment with the API.

## References

* [glfw](https://www.glfw.org/): GLFW is a free, Open Source, multi-platform library for OpenGL, OpenGL ES and Vulkan application development. It provides a simple, platform-independent API for creating windows, contexts and surfaces, reading input, handling events, etc.
* [triangle-opengles.c](https://github.com/glfw/glfw/blob/master/examples/triangle-opengles.c): Example of drawing a triangle in OpenGL ES using GLFW and GLAD in C.
* [bazel-glfw](https://github.com/pbellis/bazel-glfw): A bazel project demonstrating how use OpenGL via GLAD, GLFW and GLM in C++.
* [vulkan-bazel-samples](https://github.com/Morfly/vulkan-bazel-samples): A bazel project demonstrating how use Vulkan, GLFW and GLM in C++.
* [rules_vulkan](https://github.com/jadarve/rules_vulkan): Rules for working with vulcan and also for compiling GLSL etc.
