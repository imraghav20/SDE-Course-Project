# SDE-Course-Project
Analysis and implementation of the [research paper](https://github.com/imraghav20/SDE-Course-Project/blob/main/Impact%20of%20stack%20overflow%20code%20snippets%20on%20software%20cohesion.pdf) titled "Impact of stack overflow code snippets on software cohesion".

## Project Abstract
In this project, we aim to study the impact of code snippets from stackoverflow over the cohesion of the project. We want to visualise the results of change in cohesion of the project with time as more snippets from stackoverflow are pasted in it. 

## Implementation
1. This project uses a publically available database called SOTorrent which is present on Google BigQuery.
2. The data is first translated to CSV files for ease of convenience in using pandas library and a random set of 500 entries was picked where all files were in Java.
3. The CC and LSCC metrics for the data is calculated using the methods described in the papers and the results obtained for various files are visualised using bar graphs, pie charts and line graphs with help of matplotlib library.

## Project Report
A detailed report regarding our findings and observations can be found [here](https://github.com/imraghav20/SDE-Course-Project/blob/main/B19CSE004_B19CSE019_SDE_Course_Project.pdf).

The results obtained were equivalent to the paper we studied.

## Explanation Video
A video can be found [here](https://youtu.be/ZlJZJtI2LKE) explaining the project work and our results obtained.
