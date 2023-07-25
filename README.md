
# Analytical data for YouTube Analysis

## Overview
This is a data engineering project aims to create a analytical data from the structures and semi-structured YouTube videos data based on the video categories and trending metrics.

## Project Goals
1. Data Ingestion — Loading the datasets from local to AWS S3 using CLI and creting a Data lake as a central repository
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Scalability — As the size of our data increases, we need to make sure our system scales with it
4. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS

## Services used
1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
4. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
5. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

## Dataset used
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

link: https://www.kaggle.com/datasets/datasnaek/youtube-new




