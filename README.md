# Data Analysis and Text Processing Projects
This repository contains two separate scripts designed for specific tasks: one for analyzing student grades across various subjects (process_grades.py), and another for counting word occurrences in the text of "Alice in Wonderland" (count_words.py).

# Project Descriptions
Grade Analysis (process_grades.py)

This script processes multiple text files, each containing marks for assignments and exams for different subjects. It calculates average marks for each assessment and counts the number of students who failed (assuming a passing mark of 50%).

## Key Features:

Read grades from files named like SUBJECT_CODE.txt.

Calculate average marks for Assignment 1, Assignment 2, and the Final Exam.

Determine the number of failed students based on the final exam scores.

Output these statistics to SUBJECT_CODE_ave.txt and SUBJECT_CODE_failed.txt respectively.

Word Occurrence Counter (count_words.py)

This script reads the entire text of "Alice in Wonderland" from a file and allows the user to enter words they wish to count within the text. The process repeats until the user types "exit".

## Key Features:

Load text data from alice_in_wonderland.txt.

Interactive prompt for entering words to be counted.

Case-insensitive counting of word occurrences.

Output the count of occurrences after each input.
