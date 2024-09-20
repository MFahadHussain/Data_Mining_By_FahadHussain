Trimmed Mean Calculator

This repository contains a Python script that calculates the trimmed mean of a dataset using the Pandas library. The trimmed mean is a robust measure of central tendency that mitigates the effect of outliers by excluding a specified percentage of data from both ends of the dataset.
Features

    Trim Percentage: Easily adjustable percentage of data to trim from both the lower and upper ends.
    Robust Calculation: Computes the trimmed mean to provide a more accurate measure of central tendency.
    Output: Displays the trimmed mean alongside the data length and bounds for transparency.

Prerequisites

    Python 3.x
    Pandas library

You can install Pandas using pip:

    pip install pandas

Usage

    Import the necessary libraries and load your data into a Pandas DataFrame named df.
    Adjust the trim_percent variable to set the desired percentage of data to trim (default is 20%).
    Run the script to calculate and print the trimmed mean.

Example

Here’s a simple example to demonstrate usage:

       import pandas as pd

       # Example DataFrame
       data = {'values': [1, 2, 3, 4, 100]}
       df = pd.DataFrame(data)

       # Set the trim percentage
       trim_percent = 0.2

       # Your trimming code here

Output

The script will print:

    The total length of the dataset
    The lower and upper bounds for trimming
    The calculated trimmed mean
