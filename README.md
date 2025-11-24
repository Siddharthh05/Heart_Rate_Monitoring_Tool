# Heart Rate Analysis Tool

## 

## \## Overview



A simple tool that monitors heart rate of an individual.People measures their pulse but are unsure whether the values are normal,low or high. This tool solves that by taking multiple readings, calculating key statistics, and giving a clear analysis along with a line graph for better understanding.

## 

## \## Features



\* Input five heart rate readings with respect to time

\* Validation for valid and invalid input

\* Calculates minimum, maximum and average heart rate

\* Checks whether the average lies in a safe range (60–100 bpm)

\* Prints a simple text report

\* Displays a line graph using matplotlib


## \## Technologies / Tools Used



\* Python 3

\* Matplotlib (for graph plotting)

\* Command-line interface (CLI)

\* Modular structure with multiple Python files

## 

## \## File Structure



\* `readings.py` – Handles user input

\* `analysis.py` – Calculates statistics

\* `reports.py` – Prints the summary

\* `graph.py` – Generates the graph

\* `main.py` – Connects all modules and manages flow



## \## Steps to Install \& Run



1\. Install Python on your system.

2\. Install matplotlib:



&nbsp;  ```

&nbsp;  pip install matplotlib

&nbsp;  ```

3\. Place all project files in the same folder.

4\. Run the main script:



&nbsp;  ```

&nbsp;  python main.py

&nbsp;  ```



## \## Instructions for Testing



\* Enter different reading values: normal, low, high, or random

\* Provide incorrect inputs (letters, negatives, zero) to test error handling

\* Check whether min, max, and average values are calculated correctly

\* Verify that the graph wrt to readings







