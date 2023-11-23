# describe

Document your CMake C project with ease.

This is a [G2EPM](https://github.com/grzegorz-grzeda/g2epm) library.

## Initialize
Download dependencies by running `g2epm download` in the project root.

## How to compile and link it?

Just include this directory in your CMake project.

Example `CMakeLists.txt` content:
```
...

add_subdirectory(<PATH TO THIS LIBRARY>)

...
```

## Run
The `describe` module will automatically configure a `<BUILD_DIR>/documentation` directory. Just build the `<PROJECT-NAME>-describe` target. A corresponding HTML documentation will appear in the configured output directory.

# Copyright
This library was written by G2Labs Grzegorz Grzęda, and is distributed under MIT Licence. Check the `LICENSE` file for
more details.