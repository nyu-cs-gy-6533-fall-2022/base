# CS-GY 6533 A / CS-UY 4533 A – Interactive Computer Graphics - Fall 2022

# General Rules

## Plagiarism note and late submissions

Copying code (either from other students or from external sources) is strictly prohibited! We will be using automatic anti-plagiarism tools, and any violation of this rule will lead to expulsion from the class. Late submissions will be penalized. See the syllabus for more information about late submissions. In case of severe illness or emergency, please notify the assistants and provide a relevant medical certificate.

## Provided Software

For this class, you will use minimal C++ frameworks available at the class github account for most of the assignments. They compile on Windows, Linux, and Mac OS X. Make sure to pull the more recent changes from the git repository as we might be updating the source code from time to time.

## Compiling the Sample Projects

In order to compile the provided project files for a given assignment on your machine, you need to do the following:

* Install [CMAKE](https://cmake.org/)

* Clone the class repo with the --recursive option. NOTE: The recursive option is very important and it will not work without it.

* Create a directory called **build** in the assignment directory **TOPDIR/Assignment_X**, e.g., by typing in a terminal window:

```bash
cd TOPDIR/Assignment_X; mkdir build
```

* Create the necessary makefiles for compilation and place them inside the build directory, using the CMAKE GUI (Windows), or the command line equivalent: 

```bash
cd build; cmake ../
```

* Compile and run the compiled executable by typing:

```bash
make; ./AssignmentX
```

If you run into problems, please contact us on Discord. More information can be found in the C++ lecture slides

## What to Hand In

The delivery of the exercises is done using github classroom. The repository should follow the template provided, and it must contain:

* The source code, together with the necessary CMAKE project files, but excluding all compiled binaries/libraries. Specifically, do not include the build/ directory. The code must successfully compile on Linux operating system using GCC 9.3.0. Codes that don't successfully compile will receive a grade of 0%.

* A README.md file containing a description of what you've implemented and compilation instructions, as well as explanations/comments on your results.

*  Screenshots of all your results with associated descriptions in the README file. You should embed your images in your README file at the appropriate locations like this: ![NYU logo](NYU_Long_RGB_Color.png) 

Note: It will generally not be necessary to use additional external software for your assignments. If you find that you need to use additional binaries / external libraries other than those provided by us, please first get approval by contacting us on Discord.

## Grading

Your submission will be graded according to the quality of your image results, and the correctness of the implemented algorithms. The submitted code must reproduce exactly the images included in your readme. 

To ensure fairness of your grade, you will be asked to briefly present your work to a teaching assistant. Each student will have about 5 minutes to demo their submission and explain in some detail what has been implemented, report potential problems and how they tried to solve them, and point the assistants to the code locations where the various key points of the assignments have been implemented. If you cannot make it to the demo session (scheduled via Zoom), please tell the assistant in advance. You also have to schedule a separate meeting with the assistant as soon as possible to receive a grade for the assignment.
