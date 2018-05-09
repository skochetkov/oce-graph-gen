## OCE Graph Generator
OCE network graph generator project using igraph

### Installation

#### Requirements

Make sure you have the following before installing igraph:

- C and C++ compilers such as gcc.
- The GNU make tool.
- Optionally the libxml2 library for reading GraphML files.

#### Compilation
The standard installation method uses the autoconf/automake toolset. Run the following commands from the top-level directory of the code.

```
./configure
 make
 make check
 make install
 ```
 #### Running OCE Graph Gen
To run sample example 'oce_graph_gen':
```
gcc oce_graph_gen.c -Iigraph/include -L/usr/local/lib -ligraph -o oce_graph_gen
```
Providing that igraph libraries are installed in /usr/local/lib

*Note: For MacOS You can use the regular Unix way, or Homebrew, the homebrew/science/igraph formula.
Example:
```
brew install igraph
```

For more information about igraph library go to:

http://igraph.org/c/doc/index.html

## Basics

[Data structure library: vector, matrix, other data types](http://igraph.org/c/doc/ch07.html)
