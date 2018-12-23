# Songs Recommendation System

This repository contains documentation and code related to building a recomendation system for the Million Song Dataset using the song data and user listen data.

## Project Motivation

The Great Music Service company has a 1M catalog of songs available to their users for listening. Given the large catalog of songs, no one user can be reasonably expected to go through all the content and choose what they want to listen to. 

The Great Music Service conducted with survey of their active users found that: (1) users are not aware of all the music available, (2) the catalog is too big and is hard to choose what to listen to, (3) they do not always know what they are looking for, and (4) they often use the music service as a song discovery tool in which they are explicitly interested in listening to new things. 

The goal was to build a 'test' or 'preliminary' recomendation algorithm given the available computational resources and data.

## Repository Files

There are several files contained in this repository that were created in the course of the project's workflow. The most project important workproducts are as follows: 

### Project Code

+ **Step 1:** [Data Wrangling:](https://github.com/IvetteMTapia/Capstone1_Songs-Recommender_System/blob/master/Code-Notebooks/Data%20Wrangling%20Notebook.ipynb) Cleaned and procesed .h5 files, SQL files, and text files. Produced three CSV files with song metadata,user listening data, and artist tags.

+ **Step 2:** [Preliminary Exploratory Analysis](https://github.com/IvetteMTapia/Capstone1_Songs-Recommender_System/blob/master/Code-Notebooks/Preliminary%20Exploratory%20Data%20Analysis.ipynb)

+ **Step 3:** [Exploratory Analysis and Statistical Inference](https://github.com/IvetteMTapia/Capstone1_Songs-Recommender_System/blob/master/Code-Notebooks/Exploratory%20Analysis%20and%20Statistical%20Inference.ipynb)

+ **Step 4:** [Merge Song User Data](https://github.com/IvetteMTapia/Capstone1_Songs-Recommender_System/blob/master/Code-Notebooks/Merge%20Song%20User%20Data.ipynb)

+ **Step 5:** [Small Scale Recomender System Testing](https://github.com/IvetteMTapia/Capstone1_Songs-Recommender_System/blob/master/Code-Notebooks/Recommender%20System%20Testing.ipynb): Tested recomenders with small subset of the available data. 

+ **Step 6:** [Final Recommendation System](https://github.com/IvetteMTapia/Capstone1_Songs-Recommender_System/blob/master/Code-Notebooks/Recommender%20System.ipynb): Implementation of song popularity, artist popularity, item collaborative filetering and Ranking Matrix Factorization.

  
### Final Project Report

+ [**Final Project Report:**](https://github.com/IvetteMTapia/Capstone1_Songs-Recommender_System/blob/master/Reports-Graphics/Music%20Recommedation%20System%20Report.pdf) This report contains in detail business motivation, summary of recomender algorithms options and trade-offs, data wrangling steps (with visual aids), exploratory data analysis and recomender system implementation with a description of limitations and recomendations. 

### Presentation

+ [**Presentation:**](https://github.com/IvetteMTapia/Capstone1_Songs-Recommender_System/blob/master/Reports-Graphics/Capstone%201_Music%20Recomendation%20System_Presentation.pdf)The presentation sumarizes the project motivation,findings of exploratory analysis and recomender implementation.
