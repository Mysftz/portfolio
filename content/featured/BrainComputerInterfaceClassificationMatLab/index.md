---
date: '1'
title: 'Brain-Computer Interface Classification in MatLab'
cover: './demo.png'
github: 'https://github.com/mysftz/brain-computer-interface-classification-matlab'
tech:
  - MatLab
  - C#
  - CNN
  - Deep Learning
company: 'University of Kent'
showInProjects: true
---

This Project utilises Matlab to run variation of a convolutional neural network (CNN) which is located in the CNN folder, these file learns from dataset located in the dataset folder which contains 15 subjects and 7 session each with 9 files of data. The .m files in the CNN folder run session 1-7, 1-3 or 4-7 to which requests the appropriate data from the dataset file using a list that is located in the SBJ-S folder which contains subject, session numbers and cell range to which the results will be printed into a spreadsheet. These spreadsheet will write over each other so the results are copied into another spreadsheet in the results folder called All_Results_Data which contains all the project and experiment results, these are then organised further into spreadsheets for results for sessions 1-3, 4-7 and 1-7. The BCI_CNN_Function.m file in the CNN folder is the convolutional neural network that can be manipulated to run different variations of the CNN to improve the session accuracy.
