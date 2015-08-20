# aima-python
Automatically exported from code.google.com/p/aima-python

# AIMA Python Code

This file gives an overview of the Python code for the algorithms in the textbook AI: A Modern Approach. 
The code is Copyright (c) 2002 by Peter Norvig and is offered free of charge for your use. 
As you may know, the textbook presents algorithms in pseudo-code format; as a supplement we provide this Python 
code as well as Lisp code. The intent is to implement all the algorithms in both languages, so that you can choose 
whichever language you prefer. 
As yet neither implementation is complete, but the Lisp version is closer.

# Installation Instructions

Here is how to download the files and make them ready for use. You only need to do this once, and if you are taking a course, 
your instructor may have set this up for you.

1.  Create a directory where you want the code to reside on your local machine. 
    You can call this whatever you want; we'll call it home.
   
2.  Get the data.zip, store it in home file and unzip it. Your browser may unzip automatically, or you can give the 
    command "unzip aima-python.zip" or drag the file to your zip program icon. In the end, just make sure you have files in the directory home/data.

3.  Download the file aima-python.zip into home.

4.  Unzip it, creating files in home/python. You must have Python (version 2.2 or later) installed. 
    Python comes preinstalled on most versions of Linux and Mac OS. Versions are also available for Windows, Solaris, and other operating systems. 
    If your system does not have Python installed, you can download and install it.

5.  Make sure that home/python is in your module search path. You do this either by always starting Python from the 
    directory where you keep the files, or by editing the environment variable PYTHONPATH.

6.  Test the code. There are unit tests interspersed in the code. They follow the Python doctest conventions and can be run 
    with the command line "python doctests.py -v *.py". The "-v" is optional; it means "verbose". Various output is printed, 
    but if all goes well there should be no instances of the word "Failure", nor of a long line of "*****". If you do use 
    the "-v" option, the last line printed should be "Test passed."

# User's Guide

Once you have the files installed, you can use them in several ways.

* Read the code. This can enhance your understanding of the algorithms, and clarify parts that were not spelled out 
  in the book's pseudo-code.
* Run the existing code on your own data. For the module(s) you want, do "import module" and then run the 
  functions you want on the data you want.
* Experiment with extending the code.

# Code File Summary

You can Browse through the python/ directory to see all the files.
Look at the .txt files to see some unit tests (doctests) and their expected output.
See the code repository index to see what functions and data types are available, and how they map to the pseudocode figures in the book.
The following table lists the code files (modules), the chapters in the book to which they refer, the number of lines of code in each file, and a brief description of each file. Each module name links to a pretty, colorized version of the Python source code, and the Files column lists the original .py file and (in some cases) a .txt file of doctests.

Chapter	Module	Files	Lines	Description

1-2	agents	.py	532	Implement Agents and Environments (Chapters 1-2).
3-4	search	.py .txt	735	Search (Chapters 3-4)
5	csp	.py .txt	449	CSP (Constraint Satisfaction Problems) problems and solvers. (Chapter 5).
6	games	.py	285	Games, or Adversarial Search. (Chapters 6)
7-10	logic	.py .txt	887	Representations and Inference for Logic (Chapters 7-10)
11-12	planning	.py	6	Planning (Chapters 11-12)
13-15	probability	.py .txt	170	Probability models. (Chapter 13-15)
17	mdp	.py .txt	141	Markov Decision Processes (Chapter 17)
18-20	learning	.py	585	Learn to estimate functions from examples. (Chapters 18-20)
21	rl	.py	14	Reinforcement Learning (Chapter 21)
22	nlp	.py .txt	169	A chart parser and some grammars. (Chapter 22)
23	text	.py .txt	364	Statistical Language Processing tools. (Chapter 23)
 	doctests	.py .txt	42	Run all doctests from modules on the command line. For each
 	py2html	.py	109	Pretty-print Python code to colorized, hyperlinked html.
 	utils	.py .txt	713	Provide some widely useful utilities. Safe for "from utils import *".
5201	
Developer's Guide

If you'd like to contribute to this project, we could really use the help. Read the guidelines and then let me know what you'd like to contribute.
Acknowledgements

Many thanks for the bug reports, corrected code, and other support from Phil Ruggera, Peng Shao, Amit Patil, Ted Nienstedt, Jim Martin, Ben Catanzariti, and others.
