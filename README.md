# rtweekend
following https://raytracing.github.io/books/RayTracingInOneWeekend.html

Requires cmake and C++11

Setup cmake (and refresh it if you modify CMakeLists.txt)
cmake -B build

Build
Mac/Linux
cmake --build build --config release
Windows
(I had limited success configuring cmake so used Visual Studio to build with cmake)

Run (render)
Mac/Linux
build/inOneWeekend > image.ppm
Windows
build\Release\inOneWeekend.exe > image.ppm
