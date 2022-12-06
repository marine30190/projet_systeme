# projet_systeme

## Introduction :

This software is used to analyze .sam files. Here, this tool will be used to sort the reads of the .sam file according to their flag and their qualities but also to say if the read is mapped in totality or if it has insertions, deletions.
For this program the language used is Python3.10.6. 

## launch of the run :

To launch this tool you have to enter a terminal, launch the python3 environment and then launch the program and the file to be analyzed.
Example of the command: python3 project_system.py file_name.sam

## DEPENDENSE :

Import of os, sys, re and time modules tested on version 10.6.

## FICHIER Généré :

With this program we start from a sam file. (https://www.samformat.info/) The output files are a .sam file that contains all the reads sorted by flag (well-mapped and well-oriented read singles and end pairs that are also well-mapped and well-oriented) and read quality with MAPQ. The second file is of type txt which summarizes all the counters as well as the summary of the CIGAR which informs on the percentage of totally mapped read as well as the percentage of indels.

## LICENSE :

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

