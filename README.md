[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/t8eNCNAU)



Assignment: Anatomy of a CirleCI Config

Objective: The goal of this assignment is to familiarize yourself with CircleCI and create simple configuration files using YAML for various scenarios.

Instructions:

Part 1: CircleCI Basics 1. Create a new repo with a CircleCI conifg file. That CircleCI file must contain the following: - A single workflow that invokes a single job - The job must use the Docker executor. The image can be the image of your choice but you may just want to stick with an Ubuntu based image - Have steps that accomplish the following: - checkout the repo - A step that prints “Hello, world” - A step that lists all files in the current directory. Be sure to display all files including hidden ones AND make sure it’s long form (the flags for this are -la) - Create a file called example.txt - Write text to that file. If you are unsure how to do this look up how to write text to a file without opening it in a shell script - Cat the newly created file - Install Zip and Unzip - Create a Zip archive of your example.txt file and call it artifact.zip - Store build artifacts (newly created zip file) - Unzip and list components in your archive (unzip -l <<filename>>) - Clean up. Remove all created files

Requirements: - A specific step for each of the above steps should be created - Job must run and complete in CircleCI

Submission Guidelines: - Submit the document through GitHub Classroom .

Grading Criteria: - Correct and complete YAML syntax implementation in the chosen scenario. Be sure to validate your YAML. - Inclusion of all required elements - Adherence to submission guidelines and deadlines.