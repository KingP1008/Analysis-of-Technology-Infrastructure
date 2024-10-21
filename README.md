![image](https://github.com/user-attachments/assets/dfc30e65-c8b0-4664-b193-d3cba8655f2e)# Analysis of the technology infrastructure of LogisticAI
================

## Project Overview
 This project is a simulation project by Deloitte ireland for LogisticAI, the aim of the project is to explore the dataset given on the technology infrastructure of LogisticAI and discover which components were most at risk and then create a powerpoint presentation to report findings.

### Goals
* Discover which components are more at risk
* Create a Powerpoint presentation to report findings

## Visualization
![image](https://github.com/user-attachments/assets/df555eeb-06af-491b-b508-d2ac9593faf3)

## Data Description
### Data Source
Deloitte ireland

### Data Format
* CSV
## Analysis and Methodology
### Tools Used
* Excel
* Powerpoint

### Data Cleaning/Preparation
* Removing Duplicates
* Filling in missing data
  
### Exploratory Data Analysis
My approach to discovering which components were most at risk was to focus solely on times the components had a maximum timeout range which I defined as a level 5 risk. After filtering to find out the level 5 risk of each components, I did a count of the number of times a level 5 risk has occurred on each component to determine which components were most at risk.


### Results and Findings
* 89% of logisticAI components display a level 5 risk score too frequently
* The Django controller, Customer database and the Shipping database in my opinion are the ones that carry the most risk
* The Web frontend is logisticAI most reliable component

### Recommendations
* Since the Web frontend component was the most reliable component, maximizing the use of this component should be a priority

## Contributing and Feedback
### Contributors
* [Isiguzo Prince]

### Contact
[Princeisiguzo100@gmail.com]
