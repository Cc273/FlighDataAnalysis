# FlighDataAnalysis
### Overview
This project, completed as part of CS 644: Introduction to Big Data, involves developing an Oozie workflow to process and analyze a large volume of flight data. The analysis aims to derive insights into airline on-time performance, average taxi times, and reasons for flight cancellations using Hadoop and Oozie on AWS VMs.

### Dataset
The Airline On-time Performance dataset, covering October 1987 to April 2008, was sourced from the Harvard Dataverse.

### Project Objectives
The project has three primary objectives:
->Identify the three airlines with the highest and lowest probabilities of being on schedule.
->Determine the three airports with the longest and shortest average taxi times per flight (both in and out).
->Find the most common reason for flight cancellations.

### Oozie Workflow
The Oozie workflow developed for this project includes multiple MapReduce jobs running in fully distributed mode. The workflow is designed to handle and analyze the entire dataset efficiently.

### Key Components
MapReduce Jobs: Three primary MapReduce jobs were developed to process the data and extract the required insights.
Oozie Workflow: The workflow coordinates the execution of the MapReduce jobs and ensures the proper sequence of operations.
