<!-- To preview this markdown file in VSCode: Ctrl+Shift+V -->

# CS0 Lecture Portfolio | CS 1336 (Programming Fundamentals Lecture)
## Author: Bushra Rahman
These homework assignments were done through the course and have accompanying instructions.

## Compilation & Execution Instructions
Open terminal in `CS0-portfolio` and run:
<!-- CODE START -->
```
cd CS1336
mkdir build
g++ src/main.cpp src/hw_exercises.cpp -o build/hw
# Or use the *.cpp wildcard for a conciser compilation instruction:
g++ src/*.cpp -o build/hw
build/hw
```
<!-- CODE END -->

## Homework Instructions
* [HW 1: Basic Programming](/CS1336/instructions/HW1_Basic_Programming.pdf)
* [HW 2: Basic Calculations](/CS1336/instructions/HW2_Basic_Calculations.pdf)
* [HW 3: Calculations Continued](/CS1336/instructions/HW3_Calculations_Cont.pdf)
* [HW 4: Calculations Review](/CS1336/instructions/HW4_Calculations_Review.pdf)
* [HW 5: Selection Logic](/CS1336/instructions/HW5_Selection_Logic.pdf)
* [HW 6: Introduction to Loops](/CS1336/instructions/HW6_Intro_to_Loops.pdf)
* [HW 7: Loops Continued and File Operations](/CS1336/instructions/HW7_Loops_Cont_And_File_Operations.pdf)
* [HW 8: Functions](/CS1336/instructions/HW8_Functions.pdf)
* [HW 9: Arrays](/CS1336/instructions/HW9_Arrays.pdf)

## `src/` Folder
### Header File
* [hw_exercises.h](/CS1336/src/hw_exercises.h): contains 20 homework function prototypes
  * 0-0
  * 1-1, 1-2
  * 2-1, 2-2
  * 3-1, 3-2
  * 4-1
  * 5-1, 5-2, 5-2 BONUS
  * 6-1, 6-2
  * 7-1, 7-1 BONUS, 7-2
  * 8-1, 8-2
  * 9-1, 9-2

### Source Files
* [main.cpp](/CS1336/src/main.cpp): program driver containing `main()`
* [hw_exercises.cpp](/CS1336/src/hw_exercises.cpp): implementation of 20 homework functions and 12 helper functions

## `data/` Folder
When executing from the project root, input & output file names must be provided through their relative path (ie. with the prepend `data/`). (This functionality is hard-coded into [hw_exercises.cpp](/CS1336/src/hw_exercises.cpp).)
* HW 7-2:
  * [7-2_NumListLong.txt](/CS1336/data/7-2_NumListLong.txt): input file choice 1 (for standard output)
  * [7-2_NumListShort.txt](/CS1336/data/7-2_NumListShort.txt): input file choice 2 (for program testing)
* HW 8-1:
  * [8-1_PrimeOut.txt](/CS1336/data/8-1_PrimeOut.txt): output file
* HW 9-1:
  * [9-1_LSStandard.txt](/CS1336/data/9-1_LSStandard.txt): input file
  * [9-1_LSTest.txt](/CS1336/data/9-1_LSTest.txt): input file
* HW 9-2:
  * [9-2_StudentsListLong.txt](/CS1336/data/9-2_StudentsListLong.txt): input file choice 1 (for standard output)
  * [9-2_StudentsListShort.txt](/CS1336/data/9-2_StudentsListShort.txt): input file choice 2 (for program testing)
  * [9-2_CorrectList.txt](/CS1336/data/9-2_CorrectList.txt): input file
  * [9-2_ExamAnalysis.txt](/CS1336/data/9-2_ExamAnalysis.txt): output file
