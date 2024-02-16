# 🌐 Tech News Summariser 🌐

# Project Description

For the final project of training programme, we were tasked with building a cloud-hosted solution to a real-life issue. The project was built using Python, SQL, OpenAI, HTML, Streamlit, Docker and a range of AWS services.

N.B. The original repo was created under a separate private account, therefore this work is a copy of final project directory and thus repo history (previous commits etc) is not available.

## Overview

The technology industry moves at an incredible pace with new advancements and updates being released each day. Keeping up to date with recent news and trending topics in the technology sector is a difficult task due to the high volume of news output each day.
This project aims to extract information from the Hacker News API, which contains news stories related to the technology sector.

The project provides a cloud-hosted live Dashboard with informative news insights on top of an ETL pipeline, and an updated automated email and text messaging services through AWS SNS and AWS SES.

## 🗃️ Repository Structure

This repository contains several directories, each with a specific functionality.

- `pipeline`: This contains the extract, transform and load scripts which make up the data pipeline. This pipeline continually extracts information from the Hacker News APIs in order to track the top 200 stories each hour and stores this information in an RDS database.
- `dashboard`: Here you can find the files necessary to build and run our Streamlit dashboard that contains information about trending stories and topics, as well as additional insights into other factors such as comments.
- `text_lambda`: This directory contains the script for detecting viral stories as well as the Dockerfile to deploy it as an AWS Lambda function.
- `email_lambda`: This contains the instructions for setting up the daily email newsletter which provides the user with insights and top stories from the past news cycle. It contains the necessary details for deploying this as an AWS Lambda function.

## Getting Started

Each repository contains a `README.md` file with instructions for that specific repository.

