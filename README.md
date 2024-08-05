# OpenGL scene editor

Create a scene with a UI for OpenGL and save it in a file.

The project was made on linux, I did not tested it on Windows.

## First build

mkdir build
cmake -B build

make -C build

## Dependencies

- Dear ImGUI: https://github.com/ocornut/imgui
- glfw: https://github.com/glfw/glfw
- glm: https://github.com/g-truc/glm
- glad: https://gen.glad.sh/

You may need to generate your glad files for your machine.