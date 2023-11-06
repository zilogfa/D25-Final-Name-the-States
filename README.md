# US States Quiz with Interactive Map

An educational tool that tests users on their knowledge of the US states. This app presents an interactive map of the US and prompts the user to name the states one by one.

## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Developer](#developer)

## Introduction

The US States Quiz is a Python-based graphical application that utilizes the Turtle module along with Pandas for data management. It aims to provide an engaging way to learn the names and geographical locations of the 50 US states.

## Technologies

- Python 3.8+
- Turtle
- Pandas

## Features

- Interactive map-based quiz interface.
- Score tracking for each session.
- Generates a CSV file of states yet to be learned for further review.
- Flexible answer input with case-insensitive matching.

## Setup

To run this quiz, make sure you have the following prepared:

1. Python must be installed on your computer. If it's not, you can get it from [python.org](https://www.python.org/downloads/).
2. Install the Pandas library if it's not already available:
```shell
pip install pandas
```
The 50_states.csv file should be present in the project directory to provide the states data.
The blank_states_img.gif should be in the same directory as the main.py script for the map visualization.

## Usage
1. Execute main.py to launch the quiz.
2. Type in the name of a US state when prompted.
3. If the state is correct, it will be marked on the map and your score will increase.
4. If you want to finish the quiz early, type 'Exit' and a states_to_learn.csv file will be generated with the states you didn't guess. This can be used for studying.


## Developer
The US States Quiz app is developed by Ali Jafarbeglou. For feedback or any inquiries, feel free to reach out.


When running your application, make sure the `50_states.csv` and `blank_states_img.gif` files are located in the correct directory. These are essential for the application to function properly. If you implement an "Exit" feature that creates a `states_to_learn.csv`, ensure that this file can be correctly generated in the project directory.
