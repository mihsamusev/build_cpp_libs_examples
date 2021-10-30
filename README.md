# Collection of minimal examples of linking and runnig popular scientific C++ libraries
All examples contain a minimal `CMakeLists.txt` and `main.cpp` files in order to get started. The Collection is Linux biased, however, links to alternative installation of libraries is given. Linking of the libraries is crossplatform thanks to CMake.

## Typical workflow
For a specific example:
1. Downloading library binaries manually, getting them through a package tool like `dpkg` or `apt` or compiling library binaries from source code.
2. Get into the specific example`s folder
3. Compiling example code Windows way with CMake GUI or Linux way for example: `mkdir build && cd build && cmake .. && make -j4` 
4. Running the resulting executable

## Libraries
- [x] [Boost](/boost) dpkg -s libboost-dev | grep 'Version'
- [] [CGAL](/cgal) dpkg -s libcgal-dev | grep 'Version' + sudo apt-get install libcgal-dev
- [x] [Eigen](/eigen) 
- [x] [OpenCV](/opencv)