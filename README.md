# SCOIR Technical Interview for Back-End Engineers
This repo contains an exercise intended for Back-End Engineers.

## Instructions
1. Fork this repo.
1. Using technology of your choice, complete [the assignment](./Assignment.md).
1. Update this README with
    * a `How-To` section containing any instructions needed to execute your program.
    * an `Assumptions` section containing documentation on any assumptions made while interpreting the requirements.
1. Before the deadline, submit a pull request with your solution.

## Expectations
1. Please take no more than 8 hours to work on this exercise. Complete as much as possible and then submit your solution.
1. This exercise is meant to showcase how you work. With consideration to the time limit, do your best to treat it like a production system.

## How-To
1. This project was built in the NetBeans IDE using an ANT Build file. It can be imported into most IDE's as a general project. (i.e., Eclipse - Import -> Git -> Projects from Git -> clone URI -> Import as General Project, or the ZIP can be downloaded/unzipped and loaded into IDE as general project.)
1. The Main method is found in the CSV_2_JSON.java class and can be run as a Java Application or built into an executable file.
1. Once the application is launched, the User must select the Input, Output and Error directories. After directory selections have been made, the program will then begin to monitor the Input directory, waiting for any .CSV files.

## Assumptions
1. This project was built and tested on a Windows OS, testing on MacOS and UNIX was not conducted. (Limited access, sorry!)
1. The amount of columns for a row will always be 5 (always 4 commas in any given row), anything other than 5 will be considered an error. (Middle name being ommitted will be recognized when ,, seen between first and last name columns.)
1. The application only converts new CSV files after the three directories have been selected. CSV files that already existed in the 'Input Directory' prior to selection of directories will not be converted.
