# rtweekend
following https://raytracing.github.io/books/RayTracingInOneWeekend.html

Setup cmake (and refresh it if you modify CMakeLists.txt)
cmake -B build

Build
cmake --build build --config release

Run (render)
Mac/Linux
build/inOneWeekend > image.ppm
Windows
build\Release\inOneWeekend.exe > image.ppm
