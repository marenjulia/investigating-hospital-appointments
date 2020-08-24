# Investigating Hospital Appointments
This project investigates a dataset of information from 100k medical appointments in Brazil. The  dataset is publically available on [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments). The aim of this project is to evaluate a range of patient characteristics, and analyze if some of those are connected to higher or lower no-show rate for patients at their appointments.

## Table of Contents
1. [Installations](#installations)
2. [Project Motivation](#motivation)
3. [File Overview](#overview)
4. [Key Results](#results)

## <a id="installations"/> Installations

This project used Python 3 within Jupyter Notebook, plus the following libraries: 
- pandas
- NumPy
- matplotlib
- Seaborn

## <a id="motivation"/> Project Motivation

The motivation of this project was to practice exploratory data analysis skills by:
- Assessing the data for general properties, data quality and data tidiness
- Cleaning the data to be able to use it as a basis for meaningful analyses
- Identify patient features that might influence no-show rates for medical appointments and explore their relationships using bivariate and multivariate visualizations

The questions posed during analysis were: 
1. Are patients with healthcare scholarships more, less, or equally likely to show up to their appointment than those without?
2. Are SMS notified patients more, less, or equally likely to show up to their appointment than non-recipients?
3. Are patients with a shorter waiting time more, less, or equally likely to show up to their appointment than the ones with longer waiting time?

##  <a id="overview"/> File Overview
- investigate-a-dataset-project-code.ipynb: Exploration notebook, including data assessment, cleaning, analysis and visualization.
- noshowappointments-kagglev2-may-2016.csv: Medical appointment data, source: [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments)

## <a id="results"/> Key Results 

Waiting time before the appointment, SMS reminders, and healthcare scholarship membership are most promising for predicting no-show, followed by age, and then medical conditions. Gender does not seem relevant in predicting no-shows.
