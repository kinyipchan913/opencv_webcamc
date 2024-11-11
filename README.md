# opencv_webcamc
Example of build and run OpenCV on Windows using CMake build with CMakeLists.txt

## Dependencies
The following applications are used to build OpenCV webcam example:
- [CMake](https://cmake.org/)
The following libraries are used by OpenCV webcam example:
- [OpenCV](http://opencv.org/)

## Build
Build OpenCV webcam example using CMake:
```bash
mkdir build
cd build
# [windows]
cmake -G "Visual Studio 16 2019" -A x64 ..
cmake --build . --config Release
# [linux]
cmake ..
make -j$(nproc)
```

### Run example
To run the OpenCV webcam example, run the following commands:
```bash
cd build/Release
./OpenCV_testc.exe
