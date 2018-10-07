# Integer Multifind

## Objective:
This project aims to create a program that uses multiple threads to find an integer value in several (݊ n ≥ 1) files with integer values in different quantities.

All this operation - reading the files and location of the value - should occur using 2, 4, 8 or 16 threads, at the discretion of the user. The program was written to the Linux operating system and use the POSIX Threads Library.

## Contributors (sorted alphabetically):
* [Andrey Okamura](https://github.com/okamuratoshi)
* [Gustavo Polli](https://github.com/gapolli)
* [Mateus Santos](https://github.com/mateuspim)

## Automate all the work:
At the Terminal or other Shell interpreter, just type the following
```
sh automate.sh
```
and all the dirty work will be done in an automated way.

*The following commands should only be used if you want to do the entire process step by step or if you have not used the automate.sh automation script.*

## Compilation:
At the Terminal or other Shell interpreter, type the following
```
make
```
## Observations:
After the compilation is successful, clean the garbage with the following command
```
make clean
```

## Usage:
At the Terminal or other Shell interpreter, type the following
```
./multifind 16 123 arq1.in arq2.in arq3.in
```
where
* 16 is the number of threads to be created in the execution;
* 123 is the integer to find;
* arq1.in, arq2.in and arq3.in are the text files to be explored.

## Aditional observations:
The *random* sub-module is an aid program for the Multifind project. A basic tutorial on using the module can be found in the random folder, regardless of whether the repository was cloned on your machine or not.

*If you are using the automate.sh automation script, you do not have to go through the modules manually.*

This guide will be updated as we make changes.
