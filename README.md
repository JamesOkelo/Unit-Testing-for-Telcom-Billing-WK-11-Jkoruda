# Unit-Testing-for-Telcom-Billing-WK-11-Jkoruda
Unit Testing for Telecommunication
Billing Data Pipeline
Background Information
You are working on a project related to telecommunication billing data. As part of the project, a
data pipeline has been provided to you. The data pipeline is responsible for extracting data from
a CSV file, performing transformations using pandas, and storing the transformed data in
another CSV file. Your task is to write unit tests for the functions in the data pipeline using the
unittest framework.
Problem Statement
Your goal is to develop robust unit tests for the three functions in the data pipeline:
data_extraction, data_transformation, and data_loading. These tests ensure the data
pipeline functions correctly and handle various scenarios and edge cases.
Guidelines
● Use the unittest framework to create test cases for each function in the data pipeline.
● Write at least three test cases for each function, covering different scenarios and edge
cases.
● Ensure that your tests are independent and do not rely on each other.
● Name your test methods descriptively to indicate the scenario being tested.
● Use assertions to validate the expected behavior of each function.
● Provide informative error messages when assertions fail to aid in debugging.
Sample input dataset
A sample CSV file named 'billing_data.csv' has been provided. It contains telecommunication
billing data with the following columns: 'customer_id', 'billing_amount', and 'tax_amount'. You
can use this file as the input for your unit tests.
Starting code with the data pipeline: [Link]
Note: You may need to replace the file path in the data_extraction function and adjust the
expected results in the test cases based on your specific setup and requirements.
