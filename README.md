# Robotics Teaching Kit with Jet

## Overview

This kit includes examples, slides, quizzes, labs, and projects for teaching a course on robotics.
The material is organized into modules that cover a specific topic.  It is helpful to proceed in order
through the modules, but each module is self-contained so you are free to skip or omit modules as needed.

The kit is produced jointly by NVIDIA and Cal Poly San Luis Obispo.  All material is available under
the [Creative Commons Attribution-NonCommercial License](http://creativecommons.org/licenses/by-nc/4.0/).

## Content

### Examples

The `/examples` folder includes a variety of demonstrations.  Many of the examples
have been converted into lab assignments; therefore the examples should not be provided
to students because the examples contain solutions to many labs.
You can run an example by following the instructions below:

1. Build and launch the rosjet platform (following the instructions in lab 1).
2. Navigate to the examples folder
3. Enter the command `catkin_make && source devel/setup.sh`
4. Run any of the examples by typing `rosrun [example_name] [example_name]`

### Docs

The `/docs` folder contains the quizzes, projects and labs for the course.  To create the .pdf and .docx versions
of the documents, you must install [pandoc](http://pandoc.org/installing.html).

Then the labs can be built with the command `python make_labs.py` when you are in the
`/docs` directory.  The build folder will then contain the compiled documentation as
well as zipped folders that contain the code and solutions for the labs.

Students should receive both the lab description (.docx or .pdf) and the code.zip folder.
The solution.zip should be kept by the instructor.

### Hardware

The hardware (BOM) for the Jet robot can be acquired at the following Amazon links:

TK1: http://amzn.com/sl/16YHGMBK62X6G

TX1: http://amzn.com/sl/2QNJMQAAMVYRN

The `/hardware` folder includes illustrator files that can be used to laser cut
the plastic base plate and the sonar holders.  The `nvidia_robot.ai` file is the
layout of the base plate.  The `FiveSonarArrangement.ai` file is a layout of five
sonar holders.