# ScanCan

## Introduction
ScanCan is a python-scripted, command-line based, scalable framework designed to help students efficiently bridge and automate interactions between the Canvas web application and students' personal computers. The ScanCan framework provides a selection of modules that automatically organize and optomize academic resources so students can completely focus on the content of their courses.

## Example Modules:
#### Download_Files
Automatically downloads all available files for all classes. Organizes files based on semester/classes/file_structure_of_class... Syncs files to specified directory (if run multiple times). Student may chose to skip or replace duplicate files. 

#### Course_Information
Returns the first n-lines (10 default) of the syllabus for a specified course. May find information such as office hours, office locations, meeting times, instructor contact information, etc... 

#### Bookmarks
Pulls all external links referenced on a student's Canvas page and returns an organized bookmarks folder that may be uploaded to most browsers. Downloaded as a compressed zip file.

#### Priority_Checklist
Checklist that guides students on what assignments to work on, prepare for, and prioritize. Priority is based on due date and grade weight of assignment. May be downloaded as csv file or interactive pdf.

## Getting Started: 

```Download the project from source
 git clone https://github.com/dbherol/ScanCan.git
 Navigate into directory and execute ./setup 
 ```
  
## Using ScanCan (Quickstart):
 
 ```
"scancan list" to list all possible modules
"scancan -u <username> -p <password> use <module name> <flags>" to use module with options
"scancan <module> --help" for complete usage of module
"man scancan" for complete usage of framework
 ```
## Release:
This project is still under construction and net yet prepared for an official release.

## Contributions:
Both the framework and modules are open to contributions. Please contact me and I will put you in touch with the owner(s) of the module.

## Inquiry:
Please do not hesitate to raise an issue or contact me with any questions or comments. My email address is danielbherold@gmail.com.
