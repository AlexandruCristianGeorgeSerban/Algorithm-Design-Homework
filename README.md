# Compiling The Code

There are multiple methods for compiling and running this code:

- Compiling the code with the [MinGW compiler](https://www.mingw-w64.org/downloads/) (or any other), which must be installed locally; After installation, set a System Variable Path to MinGW's `bin` folder. To see if the installation worked, open Command Prompt and type `gcc --version`. If it worked, go to the root directory `AD Homework` and run `gcc -o main.c book_division.c`. 

- In any compatible IDE, create a `blank project` and import the following files:`main.c`, `book_division.c` and `book_division.h`.
