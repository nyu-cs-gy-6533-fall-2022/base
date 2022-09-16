# CS-GY 6533 A / CS-UY 4533 - Interactive Computer Graphics - Fall 2022

### Course Instructors

*Michael Krone (instructor)*

370 Jay Street, room 1155

<michael.krone@nyu.edu>

Office hours: t.b.a.

### Lectures:
Wednesdays, 5:00pm - 7:30pm
2 MetroTech Center, Rm 909

## Course Description

This course provides an introduction to the field of Computer Graphics. We will cover the basic mathematical concepts, such as 2D and 3D transformations, study the interaction of light with geometry to derive shading models, the representation of geometric data in the memory, and implement iterative rendering algorithms. We will investigate how these fundamental components are integrated into current graphics processors (GPUs) and study the corresponding programming APIs (OpenGL and GLM). This course will also include a brief introduction to C++. 

Students will experiment with modern graphics programming and build small demos in C++ and OpenGL. 

By the end of the course, the student must be able to: 

Explain and apply the fundamental mathematical concepts used in image synthesis algorithms 

* Implement a basic real-time rendering pipeline based on rasterization 
* Implement visual effects such as shadows and reflections on rasterization pipelines 
* Be able to model scenes using triangulated models 
* Develop simple graphics programs in C++ using OpenGL and GLSL 

## Readings 

*Textbook*:
Fundamentals of Computer Graphics, 4th Edition (5th Ed. can also be used)
December 18, 2015 by A K Peters/CRC Press
Textbook - 734 Pages - 541 Color
ISBN 9781482229394

Optional and recommended texts are:  
* OpenGL Programming Guide 9th Ed. (8th Ed. can also be used), Addison Wesley 
* Real Time Rendering 4th Ed., CRC Press 

## Grading 

This class will not have any written exams. All the grading will be based on assignments, quizzes, and class participation. We will check all assignments for plagiarism, and strictly enforce university rules. See the class syllabus for more info.

## Class Discord
We will use Discord as the main means of communication. Send an e-mail to the intructor if you have not received an invitation yet.

### Acknowledgement: 
This course is based on the computer graphics course designed by Professor Daniele Panozzo (NYU Courant) and later revised by Professor Claudio Silva (NYU VIDA Lab) with help from Jonathas Costa in 2019-2021. 

## Assignments

* [General Guidelines](General_Rules.md) 

* [Assignment 1: Images, Morphological Operators](Assignment_1/requirements/Assignment-1_Images.md) 

* t.b.a.

<!--
* [Assignment 2: 2D Vector Graphics Editor](Assignment_2/requirements/Assignment-2_2D_Editor.md) 

* [Assignment 3: 3D Scene Editor](Assignment_3/requirements/Assignment3_3D.md) 

* [Assignment 4: Shadows, Reflections, and Depth Maps](Assignment_4/requirements/Assignment4.md) 
-->

# Compilation Instructions

```bash
git clone --recursive https://github.com/nyu-cs-gy-6533-fall-2022/base # --recursive flag is necessary for dependencies
cd Assignment_N
mkdir build
cd build
cmake ../ # re-run cmake when you add/delete source files
make
```

You can substitute `cmake ../` with the following to make the program **run faster** (optimized code generation)

```bash
cmake -DCMAKE_BUILD_TYPE=Release ../ # use this cmake command instead of the previous linefor faster run
```

If you are looking for an IDE, I suggest to use [VSCode](https://code.visualstudio.com), [Visual Studio](https://visualstudio.microsoft.com/) (Windows/Mac only), or [CLion](https://www.jetbrains.com/clion/) (Free Educational Licenses available).
