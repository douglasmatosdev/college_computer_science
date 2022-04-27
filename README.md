# Computer Science (Ciências da Computação)

## Third Semester

- ### [Programming I](https://github.com/douglasmatosdev/college_computer_science/tree/master/programming_i)
- ### [Data Structure](https://github.com/douglasmatosdev/college_computer_science/tree/master/data_structure)
- ### [Data Modeling](https://github.com/douglasmatosdev/college_computer_science/tree/master/data_modeling)
- ### [Basic Software Programming](https://github.com/douglasmatosdev/college_computer_science/tree/master/basic_software_programming)
- ### [Operating Systems with Practice on Linux](https://github.com/douglasmatosdev/college_computer_science/tree/master/operating_systems_with_pratice_on_linux)


```bash
gcc -c -g src/main.c -Iinclude -o obj/main.o && \
gcc -c -g src/biblioteca.c -Iinclude -o obj/biblioteca.o && \
gcc -g -o application obj/main.o obj/biblioteca.o && \
./application

```