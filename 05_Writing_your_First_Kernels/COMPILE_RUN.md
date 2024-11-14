## How to compile and run the `.cu` files
Create the appropriate `CMakeLists.txt` file for the project.
For instance, for `01 CUDA Basics`, the `CMakeLists.txt` file is:
```CMake
cmake_minimum_required(VERSION 3.10)

project(01_idxing CUDA)

add_executable(01_idxing 01_idxing.cu)
```

Then, we proceed creating the build directory and compiling the project:
```bash
mkdir build
cd build
# If you want to debug
# cmake -DCMAKE_BUILD_TYPE=Debug ..
cmake ..
cmake --build .
```

To run the compiled program, use:
```bash
./01_idxing
```
