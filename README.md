# hockey_data_analysis_python

In this project I analyze hockey game data using Python and several Python libraries.

The goal of this project is to demonstrate my data analysis, coding, and problem solving skills using Python. I do this by solving several tasks with varying complexity.

Libraries:

I will be using a number of Python libraries such as numpy, pandas, plotly/matplotlib, and sklearn

Data Info:

- There are two data files (the files are attached above, ensure the two files are saved in the same file directory as the Jupyter file containing the Python code, this will ensure the code works) . One has a condensed event set from a randomly chosen hockey game and the other contains Expected Goals values (xg) provided only for shots that successfully hit the net. If an xg value doesn't correspond to a shot event, it should not be counted

- X and Y Coordinates are in Feet and are adjusted such that both teams shoot in the same direction

- Line Carry events are tagged when the puck is carried over either blue line or the centre ice red line

- Binary columns that have values of 0 or 1 indicate 0=No, 1=Yes

- Successfull passes are completed passes, successful shots are shots on net
