# arduino-data-visualization

This project takes 200 data inputs over time from an Arduino Uno (connected to a Sensor Base Kit) and provides Descriptive Statistics and Visualizations on the different types of environmental factors (Pressure, Altitude, Light, Sound, Temperature, and Humidity. It is a Jupyter Notebook (.ipynb) file and shows the steps that I went through to collect and analyze / visualize the data. The notebook is broken up into two parts: Part A - Data Collection and Part B - Data Analysis and Visualization.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Status](#status)

## General info
This project is part of my extracurricular work as a Research Assistant at the Data Mining and Connectivity (DMC) Lab at the College of Charleston. I utilized the technologies that I have learned through my classes, such as libraries like matplotlib and numpy, and learned new technoligies, such as the arduino coding language and the python serial package, in order to collect, visualize, and analyze data about different types of environmental factors. All of the data collection was done indoors, in a controlled environment.
	
## Technologies
Project is created with:
* Python 3.8.5
* Jupyter Notebook
* Arduino IDE
* Arduino UNO R3
* Arduino SensorKit - Base
	
## Setup
To run this project locally you must have an Arudino UNO R3 (+ SensorKit) connected to your computer and change the variable 'port' on the Arduino_Data_Collection_and_Basic_Visualization.ipynb file to the local path of the arduino. You also need to have the arduino code provided uploaded and running on the Arduino UNO. 

On the Arduino sketch, you need to download:
Arduino_SensorKit.h library 

For python you need to install following libraries:
time (built-in)
pip install numpy
pip install matplotlib
pip install serial

## Status
This project is still in progress. I plan to expand by creating and adding a .py file (instead of a .ipynb file) that takes in user input on the amount of data values that are collected from the arduino, and the time between each value. From this, the user can also input what type of visualization they want on a chosen type of collected data. I also plan to add another .py file that allows for real time visualization of data as it is being retrieved from the arduino.
