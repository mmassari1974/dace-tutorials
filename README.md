# dace-tutorials
Tutorials on the use of DACE Library.

To use the DACE library in your project, we recommend using CMake. New DACE releases past version 2.0.1 come with a CMake package system plugin that allows very simple use of the DACE within the CMake framework. To get started, have a look at the Tutorials directories. In Both of the Tutorials there are independent projects with their own stand-alone CMake file you can use as a starting point for your own programs.

## Running the Tutorials
To compile the tutorials on your system (with DACE installed) just clone the repository and build the tutorials using CMake. The following commands will clone the repository and build the first tutorial.  

```
git clone "https://github.com/dacelib/dace-tutorials.git" dace-tutorials
```

To build all the examples in the Tutorials folder:
```
mkdir tutorial1-build
cmake -S dace-tutorials/Tutorials/Tutorial1 -B tutorial1-build
cmake --build tutorial1-build

mkdir tutorial2-build
cmake -S dace-tutorials/Tutorials/Tutorial2 -B tutorial2-build
cmake --build tutorial2-build
```
This should automatically compile all tutorials, ready to be run by you using e.g. the command ```./Example1```.