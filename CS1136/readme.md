<!-- To preview this markdown file in VSCode: Ctrl+Shift+V -->

# CS0 Laboratory Portfolio | CS 1136 (Programming Fundamentals Laboratory)
## Author: Bushra Rahman
These labs assignments were done through [zyBooks](https://www.zybooks.com/).

## Compilation & Execution Instructions
Open terminal in `CS0-portfolio` and run:
<!-- CODE START -->
```
cd CS1136
mkdir build
g++ src/main.cpp src/lab_exercises.cpp -o build/labs
# Or use the *.cpp wildcard for a conciser compilation instruction:
g++ src/*.cpp -o build/labs
build/labs
```
<!-- CODE END -->

## `src/` Folder
### Header File
* [lab_exercises.h](/CS1136/src/lab_exercises.h): contains 21 lab function prototypes
  * 1-1, 1-2
  * 2-1, 2-2, 2-3
  * 3-1, 3-2
  * 4-1, 4-2
  * 5-1, 5-2
  * 6-1, 6-2
  * 7-1, 7-2
  * 8-1, 8-2
  * 9-1, 9-2
  * 10-1, 10-2

### Source Files
* [main.cpp](/CS1136/src/main.cpp): program driver containing `main()`
* [lab_exercises.cpp](/CS1136/src/lab_exercises.cpp): implementation of 21 homework functions and 19 helper functions

## `data/` Folder
When executing from the project root, input & output file names must be provided through their relative path (ie. with the prepend `data/`). (This functionality is hard-coded into [lab_exercises.cpp](/CS1136/src/lab_exercises.cpp).)
* Lab 7-1:
  * [7-1_sales.txt](/CS1136/data/7-1_sales.txt): input file
  * [7-1_saleschart.txt](/CS1136/data/7-1_saleschart.txt): output file
* Lab 7-2:
  * [7-2_avg.txt](/CS1136/data/7-2_avg.txt): input file
  * [7-2_invalids.txt](/CS1136/data/7-2_invalids.txt): output file
* Lab 9-2:
  * [9-2_data.txt](/CS1136/data/9-2_data.txt): input file
  * [9-2_output.xls](/CS1136/data/9-2_output.xls): output file
* Lab 10-1:
  * [10-1_student.txt](/CS1136/data/10-1_student.txt): input file
  * [10-1_answers.txt](/CS1136/data/10-1_answers.txt): input file
* Lab 10-2:
  * [10-2_grades.txt](/CS1136/data/10-2_grades.txt): input file
