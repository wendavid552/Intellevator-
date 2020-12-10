# Intellevator 
The smart elevator.
This project is built to simulate and conduct researches on the managing of elevator, in order to make all the people waiting for it mroe convenient.

We found that this problem is similar to the Disk Scheduling Problem, a very fundamental problem with proven solutions for many years. We are going to build our Intellevator based on it.

## Features to be built
- Testing Version 0.001
  - A console application, or a small application using Bootstrap
  - To simulate the most classical logic for normal elevator: continue to go up if there are any requirement, which is similar to the SCAN algorithm in the Disk scheduling Porblem.
  - Given the number of people waiting on each floor, and the elevator has its size.
  
- Alpha Version 0.100
  - To test the efficiency of each kind of algorithm through visualization.
  - Find an effective algorithm, if when new vistors will come and how many are they are given.

- Alpha Version 0.200
  - Parallel Application
  - To scan how many people are waiting for elevators on each floor through CV.
  - Analyse and Record the data into log
  
- Alpha Version 0.300
  - Make the prediction of how many people will come in the future with the recorded data, so that the elevator can be at
  - Record the energy usage.
  - Compare the effeciency of each algorithm in the worse cases, the average(random) cases and cases in patterns.
  - Score each up and down of the elevator with:
    - The time waiting for it
    - The comfort on it(e.g. how clear the air is in it, based on how long the air conditionor has opened)
