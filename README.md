### Project Description:
This project explores the relationship between big data and cloud computing, and how organisations can harness the power of these tools to develop data-driven strategies that keeps them competitive and innovative. 

### General Approach
 - #### Source of Big Data
This project will use the Amazon Customer Dataset (a.k.a. Product Reviews), particularly reviews on electronics products. The Amazon Customer Dataset Reviews a rich source of information for academic researchers in the fields of Natural Language Processing (NLP), Information Retrieval (IR), and Machine Learning (ML), amongst others. This dataset was constructed to represent a sample of customer evaluations and opinions, variation in the perception of a product across geographical regions, and promotional intent or bias in reviews”.

#### Cloud Environment
This project will be developed on the Amazon Web Services (AWS) platform, making use of the following services:
   - Amazon Elastic Compute Cloud (EC2): a web service that provides resizable compute capacity in the cloud.
   - Amazon Simple Storage Service (S3): an object storage built to retrieve any amount of data from aanywhere.
   - Amazon EMR: a cloud big data platform for running large-scale distributed data processing jobs, interactive SQL queries, and machine learning (ML).
  
#### Data Analysis Tool - PySpark
The volume of data to be processed exceeds the capacity of a local computer therefore a utilities Engine, Spark Framework, will be used to read the dataset from Amazon’s Simple Storage Service (S3), which is a service offered by Amazon Web Services (AWS), which provides object storage through a web service interface. All ETL processing will be done in the cloud, using the Amazon Web Services. Statistical analysis will be done using PySpark and SQL capabilities bundled with the Spark module. Apache Spark is an open-source, distributed processing system, used to optimize and run fast analytic queries against data. PySpark is an interface for Apache Spark in Python.
