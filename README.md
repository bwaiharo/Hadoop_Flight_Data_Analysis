# Hadoop_Flight_Data_Analysis
Flight Data Analysis
In this project, you will develop cloud-based Big Data workflows to process and analyze a large volume of flight data.

Instructions:
Form a project team of two students (including yourself).
 Install Hadoop on your AWS VMs.
Download the Airline On-time Performance data set (flight data set) from the period of
October 1987 to April 2008 on the Statistical Computing website:
 http://stat-computing.org/dataexpo/2009/the-data.html
Design, implement, and run MapReduce jobs to find out
the 3 airlines with the highest and lowest probability, respectively, for being on
schedule;
the 3 airports with the longest and shortest average taxi time per flight (both in and
out), respectively; and
the most common reason for flight cancellations.
 Requirements:
Your workflow must contain at least three MapReduce jobs.
Run your workflow to analyze the entire data set (total 22 years from 1987 to 2008) at one
time and measure the execution time.
Run your workflow to analyze the data in a progressive manner with an increment of 1 year,
i.e. the first year (1987), the first 2 years (1987-1988), the first 3 years (1987-1989), …, and
the total 22 years (1987-2008), and measure each corresponding execution time.
Submission (all in a zipped file):
A commands.txt text file that lists all the commands you used to run your code and produce
the required results in fully distributed mode
An output.txt text file that stores the final results from all the runs
The source code of your MapReduce programs (including the JAR files) and any other
programs you might have developed and included in the workflow
A project report in PDF that includes:
A detailed description of the algorithm you designed to solve each of the problems
A performance measurement plot that compares the execution time in
response to an increasing data size (from 1 year to 22 years) and an in-depth
discussion on the observed performance comparison results
Optional:

Install Oozie on your AWS VMs.
Design, implement, and run an Oozie workflow to manage the MapReduce jobs.
Run in fully distributed mode.
Run your workflow to analyze the entire data set (total 22 years from 1987 to 2008) at one
time on two VMs first and then gradually increase the system scale to the maximum allowed
number of VMs for at least 5 increment steps, and measure each corresponding workflow
execution time.
On the run for incremental years, use the maximum allowed number of VMs.
Please also submit the Oozie workflow XML file
Also include in your project report:
a diagram that shows the structure of your Oozie workflow
A performance measurement plot that compares the workflow execution time in
response to an increasing number of VMs used for processing the entire data set (22
years) and an in-depth discussion on the observed performance comparison results
