# Blackstone-legal-cat

## This repository aims to assess the performance of the Python package Blackstone. 
[Blackstone](https://research.iclr.co.uk/blackstone) a spaCy model and library for processing long-form, unstructured legal text. Blackstone is an experimental research project from the Incorporated Council of Law Reporting for England and Wales' research lab, ICLR&D. It was trained on UK case law of a considerable period (the oldest cases date to 1860s). 

Its features include Named-Entity Recognition (NER), which is able to detect case names, citations, court, names of judges etc. 

However, the focus of this project is on the text classification features. There are five categories in which it classifies text: 

1. AXIOM - The text appears to postulate a well-established principle
2. CONCLUSION - The text appears to make a finding, holding, determination or conclusion
3. ISSUE - The text appears to discuss an issue or question
4. LEGAL_TEST - The test appears to discuss a legal test
5. UNCAT - The text does not fall into one of the four categories above

## Objectives of this project
The *code* folder contains two python files with the same code: One *.py* script, and the other a Jupyter notebook. 

The code in both files applies blackstone's text classification feature on the Singaporean case *Spandeck Engineering v DSTA* (2007). 

I am currently working on explaining the code in the Jupyter notebook and intend to share it with students interested in legal technology. My objective is to demystify the use of machine learning / data science techniques and make it approachable for law students who may be apprehensive in picking up coding.

A subsidiary objective is to assess the performance of blackstone on Singaporean case law. It would be interesting to see its performance metrics since anecdotally, UK judgements use more complex sentences, while Singaporean judgements are usually more direct.

## Requirements
Python 3.7.5
Blackstone
Pandas

## How to use
The code is the same in both the *.py* file and Jupyter notebook. 
The relevant data is *spandeck.txt*, which is __*Spandeck*__  converted from the pdf file and contained in the data folder.