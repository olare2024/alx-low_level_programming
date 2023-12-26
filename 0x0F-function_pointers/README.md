# C - Function pointers
<p><img src="data:image/png;base64,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" alt"pointers"></p>
In this project, I learned about function pointers in C - what they hold,
where they point in virtual memory, and how to use them.

## Tests :heavy_check_mark:

* [tests](./tests): Folder of test files. Provided by ALX Best School.

## Header Files :file_folder:

* [function_pointers.h](./function_pointers.h): Header file containing prototypes
for all functions written for programs 0-2 of the project.

| File                 | Prototype                                                            |
| -------------------- | -------------------------------------------------------------------- |
| `0-print_name.c`     | `void print_name(char *name, void (*f)(char *));`                    |
| `1-array_iterator.c` | `void array_iterator(int *array, size_t size, void (*action)(int));` |
| `2-int_index.c`      | `int int_index(int *array, int size, int (*cmp)(int));`              |

* [3-calc.h](./3-calc.h): Header file containing definitions and prototypes for all
types and function written for the program [3-main.c](./3-main.c).

| Type/File          | Definition/Prototypes                                        |
| ------------------ | ------------------------------------------------------------ |
| `struct op`        | <ul><li>`char *op`</li><li>`int (*f)(int a, int b)`</li><ul> |
| `typedef op_t`     | `struct op`                                                  |
| `3-op_functions.c` | <ul><li>`int op_add(int a, int b);`</li><li>`int op_sub(int a, int b);`</li><li>`int op_mul(int a, int b);`</li><li>`int op_div(int a, int b);`</li><li>`int op_mod(int a, int b);`</li></ul>                                            |
| `3-get_op_func.c`  | `int (*get_op_func(char *s))(int, int);`                     |

## Tasks :page_with_curl:

* **0. What's my name**
  * [0-print_name.c](./0-print_name.c): C function that prints a name.

* **1. If you spend too much time thinking about a thing, you'll never get it done**
  * [1-array_iterator.c](./1-array_iterator.c): C function that executes a function given
  as a parameter on each element of an array.

* **2. To hell with circumstances; I create opportunities**
  * [2-int_index.c](./2-int_index.c): C function that searches for an integer.
    * Returns the index of the first element for which the `cmp` function does not return `0`.
    * If no element is matched or `size` <= 0, the function returns `-1`.

* **3. A goal is not always meant to be reached, it often serves simply as something to aim at**
  * [3-op_functions.c](./3-op_functions.c): File containing the following five functions:
    * `op_add`: Returns the sum of `a` and `b`.
    * `op_sub`: Returns the difference of `a` and `b`.
    * `op_mul`: Returns the product of `a` and `b`.
    * `op_div`: Returns the division of `a` by `b`.
    * `op_mod`: Returns the remainder of the division of `a` by `b`.

  * [3-get_op_func.c](./3-get_op_func.c): C function that selects the correct function
  from `3-op_functions.c` to perform the operation asked by the user.
    * If the operator argument `s` does not match any of the five expected operators
    (`+`, `-`, `*`, `/`, `%`), the function returns `NULL`.

  * [3-main.c](./3-main.c): C program that performs simple mathematical operations.
    * Prints the result of the operation, followed by a new line.
    * Usage `./a.out num1 operator num2`
    * The program assumes `num1` and `num2` are integers that can be converted from string
    input to `int` using `atoi`.
    * The program assumes that the result of all operations can be stored in an `int`.
    * `operator` is one of either `+` (addition), `-` (subtraction), `*`
    (multiplication), `/` (division), or `%` (modulo).
    * If the number of arguments is incorrect, the program prints `Error` followed by a new
    line and exits with a status value of `98`.
    * If the `operator` is none of the above, the program prints `Error` followed by
    a new line and exits with a status value of `99`.
    * If the user tries to divide (`/` or `%`) by `0`, the program prints
    `Error` followed by a new line and exits with a status value of `100`.

* **4. Most hackers are young because young people tend to be adaptable. As long as you remain adaptable, you can always be a good hacker**
  * [100-main_opcodes.c](./100-main_opcodes.c): C program that prints the opcodes of its
  own main function, followed by a new line.
    * Usage: `./main number_of_bytes`
    * Opcodes are printed two-decimal long in hexadecimal, lowercase.
    * If the number of arguments is incorrect, the program prints `Error`
    followed by a new line and exits with a status value of `2`.