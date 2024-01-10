To compile the code, make sure you have the nlohmann/json library installed. You can install it using a package manager like vcpkg:
```
vcpkg install nlohmann-json
```
Then, compile the code with:
```
g++ -o main main.cpp april.cpp -std=c++17 -I/path/to/nlohmann/json/include
```
Make sure to adjust the include path for nlohmann/json based on your setup. 
The provided example assumes you are using a Unix-like environment.