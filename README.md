Decaf-Compiler
Description
Compiler for Decaf Programming Language. Developed as a course project for Compilers course. Decaf is a strongly-typed, object-oriented language with support for inheritance and encapsulation. By design, it has many similarities with C/C++/Java, so you should find it fairly easy to pick up. But it is not an exact match to any of those languages. The feature set has been trimmed down and simplified to keep the programming projects manageable

Repo structure
src contains all the code written in C++, flex and bison and CMake files
class_definitions contains definitions for all the classes
docs contain code documentation
sample_inputs contain some sample Decaf programs to test the compiler
Building
mkdir build
cd build/
cmake ..
make 
This will create an executable named decafCompiler in build/bin directory

Running the executable
decafCompiler <input_file> > <output_file>
lli <output_file>
