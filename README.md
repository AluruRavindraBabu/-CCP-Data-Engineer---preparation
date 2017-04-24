# -CCP-Data-Engineer---preparation
Self preparatory material -- ( Do not test on your production environment until you test... :) )


Syllabus for the exam..

Data Ingest
The skills to transfer data between external systems and your cluster. This includes the following:

Import and export data between an external RDBMS and your cluster, including the ability to import specific subsets, change the delimiter and file format of imported data during ingest, and alter the data access pattern or privileges.
Ingest real-time and near-real time (NRT) streaming data into HDFS, including the ability to distribute to multiple data sources and convert data on ingest from one format to another.
Load data into and out of HDFS using the Hadoop File System (FS) commands.
Transform, Stage, Store
Convert a set of data values in a given format stored in HDFS into new data values and/or a new data format and write them into HDFS or Hive/HCatalog. This includes the following skills:

Convert data from one file format to another
Write your data with compression
Convert data from one set of values to another (e.g., Lat/Long to Postal Address using an external library)
Change the data format of values in a data set
Purge bad records from a data set, e.g., null values
Deduplication and merge data
Denormalize data from multiple disparate data sets
Evolve an Avro or Parquet schema
Partition an existing data set according to one or more partition keys
Tune data for optimal query performance
Data Analysis
Filter, sort, join, aggregate, and/or transform one or more data sets in a given format stored in HDFS to produce a specified result. All of these tasks may include reading from Parquet, Avro, JSON, delimited text, and natural language text. The queries will include complex data types (e.g., array, map, struct), the implementation of external libraries, partitioned data, compressed data, and require the use of metadata from Hive/HCatalog.

Write a query to aggregate multiple rows of data
Write a query to calculate aggregate statistics (e.g., average or sum)
Write a query to filter data
Write a query that produces ranked or sorted data
Write a query that joins multiple data sets
Read and/or create a Hive or an HCatalog table from existing data in HDFS
Workflow
The ability to create and execute various jobs and actions that move data towards greater value and use in a system. This includes the following skills:

Create and execute a linear workflow with actions that include Hadoop jobs, Hive jobs, Pig jobs, custom actions, etc.
Create and execute a branching workflow with actions that include Hadoop jobs, Hive jobs, Pig jobs, custom action, etc.
Orchestrate a workflow to execute regularly at predefined times, including workflows that have data dependencies
What should you expect?
You are given five to eight customer problems each with a unique, large data set, a CDH cluster, and four hours. For each problem, you must implement a technical solution with a high degree of precision that meets all the requirements. You may use any tool or combination of tools on the cluster (see list below) -- you get to pick the tool(s) that are right for the job. You must possess enough industry knowledge to analyze the problem and arrive at an optimal approach given the time allowed. You need to know what you should do and then do it on a live cluster under rigorous conditions, including a time limit and while being watched by a proctor.

Who is this for?
Candidates for CCP Data Engineer should have in-depth experience developing data engineering solutions and a high-level of mastery of the skills above. There are no other prerequisites.

What is the best way to prepare?
The CCP Data Engineer exam was created to identify talented data professioanls looking to stand out and be recognized by employers looking for their skills. Outside of having hands-on experience in the field, it is recommended that professional looking to achieve this certification start by taking Cloudera's Spark and Hadoop Developer training course

 GET STARTED
Have more questions? Check out our Certification FAQ

Exam delivery and cluster information
