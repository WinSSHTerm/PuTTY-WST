# PuTTY-WST
A fork of Simon Tatham's SSH client [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/) for use with WinSSHTerm 2.41.0 or higher.

## Changes
![Scroll Demonstration](scroll_demo.gif)
* Scroll behaviour similar to Windows Terminal (mouse wheel and trackpad)
* Change font size with CTRL+MOUSEWHEEL
* Prevent weird terminal behaviour on Windows systems that support Modern Standby (see [issue](https://github.com/WinSSHTerm/PuTTY-WST/issues/1))

## How to build PuTTY-WST
### Sample Setup
* Windows 10 or higher
* Visual Studio (C++ Development)
* [CMake](https://cmake.org/)

### Build
* Download and extract the source zip file
* Run `cmake -A x64 .` if you want a `x64` build or run `cmake -A arm64 .` for a `arm64` build
* Start the build with `cmake --build . --config Release`
* A new sub-directory `Release` will be created that contains the binaries

