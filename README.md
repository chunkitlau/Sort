# Sort

This repository is for the novel idea skill 1 exercise of research skill training.

---

This package contains the source code for sorting. There are README, source code, and technical reports in this repository.

# Usage Step

0. Setup: ```cd src```
1. Compilation: ```g++ sort.c -o sort -g```
2. The input file: "data.txt" (Format of this file can be found in Appendix A)
3. Execution: ```./sort```
4. Output files: "output.txt", "stat.txt", and "time.txt" (Format of these files can be found in Appendix B)

# Appendix A. Format of the configure file “config.txt”

1. name of the input file
2. no. of elements 
3. parameter 1
4. parameter 2
5. parameter 3

# Appendix B. Format of the input file "data.txt"

The input file is a line of text consisting of multiple numbers representing the sequence to be sorted, with the numbers separated by spaces.

# Appendix C. Format of output files

## Format of “output.txt”

The file is a line of text consisting of multiple numbers representing the sorted sequence, with the numbers separated by spaces.

## Format of “stat.txt”

The file contains a number indicating the number of swaps in the sorting.

## Format of “time.txt”

The file contains four lines representing read, sort, write and overall time, where each line contains two numbers representing user time and system time.