# cs-vis-project
CS 329E Elements of Data Visualization Project

By Anna-Maria Andreeva, Ishita Kumar, and Crystal Tse

In this project, two visualizations were developed using Altair (Python visualization library) to inform prospective and current University of Texas system students about salary prospects of different areas of study based on historical data. Using the SeekUT dataset, which has major, industry, and salary data, we developed visualizations that provide easy access to comprehensive information about financial prospects of different areas of study.

In visualization 1, users filter to their UT system university of interest by using the dropdown menu. Once a university has been selected, users can explore the average salaries of different industries of study for that campus, along with the institution median. Users can select as many or as few industries to explore salary information for. The resulting line chart from this visualization shows salary data at the 1, 5, and 10 year points after graduation. A tooltip allows users to determine the exact salary numbers at these points in time. 


<img src="./images/vis-1-demo.jpg" alt="Visualization 1. Each line represents an industry's median salary and its change over time." width = "700"/>
  
In visualization 2, users get to explore salary data by industry of study even further for each school in the UT System. Users first select a university and a “years out of college” point in time they want to view salary data for. They can then select as many industries as they want from the histogram, and a boxplot of salary data for specific majors within each industry will be displayed about the median, 10th percentile, 25th percentile, 75th percentile, 90th percentile salary information for each major, also accessible through the tooltip.

<img src="./images/vis-2-demo-pt1.jpg" alt="Visualization 2. Selecting individual bars/industries allows the user to see major distributions below." width = "700" />

<img src="./images/vis-2-demo-pt2.jpg" alt="Visualization 2. Individual major distributions can be viewed through the boxplots." width = "700" />
