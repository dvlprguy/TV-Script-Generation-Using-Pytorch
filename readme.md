# Generating TV Scripts using Pytorch

This project aims at generating unseen scripts from data. These scripts make somewhat sense. 

## Dataset

The dataset used was seinfeld chronicles scripts for 9 seasons.

    https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv

## Files
    helper.py: Contains helper functions
    problem_unittests.py: Contains functions to test implementation
    tv_script_generation: Main code for training
    Data: Directory for training data

## Models

A lstm based model was used to achieve some amount of meaningfulness among the generated scripts. 

## Results
The following scripts were produced:-
* genereted_script_1.txt 
* genereted_script_2.txt 