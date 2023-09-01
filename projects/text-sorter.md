---
layout: project
type: project
image: img/english-japanese.png
title: "Text Sorter"
date: May 2022
published: true
labels:
  - C++
  - Commandline
summary: "Text sorter developed in ICS 212."
---

<img class="img-fluid" src="../img/english-japanese.png">

This was an independent assignment that sorted the provided data text file based on the characters it was read in. Using the command line, the user must input some text file which will then prompt the program to run. The program had to access the file and read each character to determine how to order the following information. For example, if the input character was `[`, then I would need to ensure that I grab all of the characters inside until reaching `]` into one line.

This project expanded my knowledge when it comes to accessing files with C++. There was also the necessity to write a friend function for the cout `<<` operator.

Source: <a href="https://github.com/michho8/text-sorter"><i class="large github icon "></i>ics212-a26</a>
