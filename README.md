# Machine Learning Portfolio

A repository of the projects I worked on or currently working on. It is updated regularly. The projects are written in Python (Jupyter Notebook). Click on the projects to see full analysis and code. 

## Projects:

[Detecting a Rock or a Mine](https://github.com/Kathi-Urban/new_project/blob/main/K-Nearest-Neighbors/KNN%20Project.ipynb):
Main goal is to create a **KNN machine learning model** capable of detecting the difference between a rock or a mine based on the response of the 60 separate sonar frequencies.

**The Sonar Data:**
Sonar (sound navigation ranging) is a technique that uses sound propagation (usually underwater, as in submarine navigation) to navigate, communicate with or detect objects on or under the surface of the water, such as other vessels. The data set contains the response metrics for 60 separate sonar frequencies sent out against a known mine field (and known rocks). These frequencies are then labeled with the known object they were beaming the sound at (either a rock or a mine). 
[Data Source](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks))


[CIA Country Analysis and Clustering](https://github.com/Kathi-Urban/new_project/blob/main/Kmeans-Clustering/KMeans%20Clustering%20Project.ipynb):
Implemented a **Kmeans-Clustering model** to gain insights into similarity between countries and regions of the world by experimenting with different cluster amounts.

These data sets are made up of data from the US government. [Data Source](https://www.cia.gov/library/publications/the-world-factbook/docs/faqs.html)

[Handwritten Digits](https://github.com/Kathi-Urban/new_project/blob/main/Principal%20Component%20Analysis/Principal%20Component%20Analysis%20Project.ipynb):
The objective of this project is to be able to read in the digits automatically, even if they are handwritten. The goal is to know which handwritten numbers are the hardest to tell apart. In this project I have performed PCA to get better insight into which numbers are easily separable from the rest.

**Data Set Information from Original Authors:**
We create a digit database by collecting 250 samples from 44 writers. The samples written by 30 writers are used for training, cross-validation and writer dependent testing, and the digits written by the other 14 are used for writer independent testing. This database is also available in the UNIPEN format.
We use a WACOM PL-100V pressure sensitive tablet with an integrated LCD display and a cordless stylus. The input and display areas are located in the same place. Attached to the serial port of an Intel 486 based PC, it allows us to collect handwriting samples. The tablet sends  𝑥  and  𝑦  tablet coordinates and pressure level values of the pen at fixed time intervals (sampling rate) of 100 miliseconds.
These writers are asked to write 250 digits in random order inside boxes of 500 by 500 tablet pixel resolution. Subject are monitored only during the first entry screens. Each screen contains five boxes with the digits to be written displayed above. Subjects are told to write only inside these boxes. If they make a mistake or are unhappy with their writing, they are instructed to clear the content of a box by using an on-screen button. The first ten digits are ignored because most writers are not familiar with this type of input devices, but subjects are not aware of this.
[Data Source](https://archive.ics.uci.edu/ml/datasets/Pen-Based+Recognition+of+Handwritten+Digits)

[Fraud in Wine](https://github.com/Kathi-Urban/new_project/blob/main/Support-Vector-Machines/Support-Vector-Machines%20Project.ipynb):
Overall goal is to use the wine dataset shown below to develop a **SVM machine learning model** that attempts to predict if a wine is "Legit" or "Fraud" based on various chemical features.

**Wine Fraud:**
Wine fraud relates to the commercial aspects of wine. The most prevalent type of fraud is one where wines are adulterated, usually with the addition of cheaper products (e.g. juices) and sometimes with harmful chemicals and sweeteners (compensating for color or flavor).
Counterfeiting and the relabelling of inferior and cheaper wines to more expensive brands is another common type of wine fraud.
Data Source: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.



