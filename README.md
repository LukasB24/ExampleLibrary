# Install
- create build folder with <code> cmake -B cmake-build-debug </code>
- create library with <code> cmake --build cmake-build-debug </code>
- install library with <code> cmake --install cmake-build-debug </code>

# Uninstall
- <code>cd cmake-build-debug</code>
- remove library with <code> sudo cmake --build . --target uninstall </code>

### Source
https://medium.com/@omaralv/creating-a-shared-library-with-modern-cmake-f332a69bb478