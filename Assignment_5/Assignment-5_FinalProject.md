# CS-GY 6533 A / CS-UY 4533 - Interactive Computer Graphics - Fall 2022

# Assignment 5: Final Project

**Handout date:** 11/10/2022

**Submission deadline:** 11/17/2022, 11:59PM ET (for the project proposal) / 12/13/2022, 11:59PM ET (for the actual project)

**Demo date:**  TBA, via Zoom appointments ***+ 12/14/2022: all projects need to be presentation in class! (~3-5 min each)***

This assignment accounts for 25\% of your final grade. You can win 15\% of extra credit on this assignment based on the originality and complexity of your project.

## Goals

This is the final project of the class. You are free to decide what you want to work on, as long as it follows the guidelines below.

## Submission

*	Follow the link (see discord channel) to create your repository.

*	Add a README.md in markdown format as a report of what you did and add screenshots to document your results.

*	Push the code into the repository before deadline

## Project Guidelines

You have to prepare a 1-2-page overview of your project, detailing what you want to do and what the relation with the topics learned in this class is. This document (PDF or markdown) has to be pushed to your repository by the first deadline (11/17/22) and will be approved by Tuesday, November 22, 2022. Your proposal should split the project into tasks and include a suggested grading (this might be adapted by the instructors). Feel free to include bonus points (see above: up to 15% extra credit); however, extra credit might also be awarded based on the quality of the final result.

*Let us know if you submit your project description early, you might be able to get a pre-approval!*

*You can contact the instructors if you want feedback on your project idea.*

**You can work on the project in small teams of up to 3 people, but:**

* the proposed amount of work has to be appropriate for the size of the team
* each team member will be graded individually, that is, the proposal must include a plan how the work will be distributed, and it needs to be clear what the contributions of each team member was (e.g., comments in the code, GitHub commits, etc.)

### Grading ###

The final project will be graded depending on the correctness and completeness of the graphics part of the project (wrt your project proposal). As mentioned above, you have to briefly present the results of your project in class on Dec 14.

### Software Libraries ###

You are free to use any software library you want if it is detailed in the project description and approved by the instructors. However, if you choose to use external libraries, the amount of work you do yourself still has to be sufficiently high (i.e., we expect more advanced graphics / methods if you use libraries).

_________________

## Ideas for Possible Project ##

### Ray Tracing ###
Extend the ray tracer from assignment 2 with additional capabilities and effects, e.g., more/different light sources (spotlights, area lights,...), different objects (meshes, tori/“donuts”, cylinders,...), lenses/depth-of-field, improve scalability / computation speed (spatial data structures for faster intersections),...

### Visual Effects in OpenGL ###
Extend the OpenGL program from assignments 3 + 4 with additional capabilities and effects, e.g., shadows (shadow maps/volumes), different materials, normal/bump mapping, environment mapping, displacement mapping (using tessellation or geometry shaders),...

### Screen-space Methods ###
Extend the Deferred Shading pipeline from assignment 4  by adding various screen-space / post-processing effects such as (screen-space) ambient occlusion, improved contour rendering, depth-of-field, motion blur,...

### Procedural Rendering ###
Procedural modeling uses a combination of rules (e.g., grammars or L-systems) and randomness to generate 3D geometry (see https://en.wikipedia.org/wiki/Procedural_generation). It is often used to generate natural-looking objects and scenes, e.g., terrains or trees, but also buildings or whole cities. You could implement a simple procedural generation algorithm and render the results to create a specific object like a tree or a whole landscape.

### Computer Graphics for (Scientific) Visualization ###
Get some interesting data and implement a rendering for it. Examples could be: 
 * Molecular Graphics - get molecular data from https://www.rcsb.org/ and, e.g., write a GLSL shader that renders a ball-and-stick representation of a molecule using shader-based ray casting (see, e.g., https://link.springer.com/content/pdf/10.1007/978-3-031-02604-1.pdf, chapter 3). 
 * NYC offers a lot of data that you can use, e.g., a 3D model of the whole city (https://www.nyc.gov/site/planning/data-maps/open-data/dwn-nyc-3d-model-download.page) that you can use for a project. You can for example combine this 3D model with other city-related data (https://opendata.cityofnewyork.us/), use it for a level-of-detail rendering to improve rendering performance, or try to re-create the street level shadow calculation presented in the lecture. You can use the Online 3D Viewer (https://3dviewer.net/) to load the 3DM files and convert them, e.g., to the OFF file format.
 * Obtain some climate data (e.g., wind, temperature, precipitation,...) and render it on a globe using multiple textures, bars (e.g., like this: http://seminar.mmc.nsu.ru/en.php) a particle system (e.g., similar to https://earth.nullschool.net/). You could also add flight routes or other connections (see https://datavizcatalogue.com/methods/connection_map.html) as 3d geodesic arcs or your globe could support level-of-detail rendering the closer the camera is...

*These are just some ideas - you are very much encouraged to come up with a project idea of your own!*