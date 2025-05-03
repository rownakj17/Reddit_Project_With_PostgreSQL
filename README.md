
Project Name
------------

Structured PostgreSQL database project with real-time Reddit data.

Project Overview
----------------

This project focuses on creating a PostgreSQL database loaded with real-time Reddit data. It includes database design, web scraping, data ingestion, SQL querying, and bash scripting. Bash scripting has been used to complete all the steps to achieve automation.

Elements Used
-------------

-- Creation of a PostgreSQL database which consists of four tables: submissions, comments, authors and subreddits.
-- Web scraping to create CSV files and bulk data loading into the database using these CSV files.
-- Writing structured queries to retrieve specific insights from the dataset.
-- Using Shell Scripting (Bash) to automate the whole process of data scraping, loading processes and querying.
-- Structured storage of query results in corresponding tables (query1 to query5).

Project Infrastructure
----------------------

-- PostgreSQL v14
-- Bash Scripting
-- Python (for data scraping)
-- SQL (for querying)
-- GitHub (for version control)

Table Structure
---------------

-- authors table: stores Reddit author ids.
-- subreddits table: stores details about subreddits.
-- submissions table: stores details of submissions to Reddit.
-- comments table: stores comments under stored submissions.
-- Primary key and Foreign key relationships has been enforced.
-- query1 to query5 tables: stores specific query results as follows:
                                                         
                -- query1 table: stores the most active authors
                -- query2 table: stores the top subreddits by average score
                -- query3 table: stores the most discussed submission
                -- query4 table: stores the most upvoted comments
                -- query5 table: stores the author with highest average score

Project Steps
-------------

-- Database Setup & Tables Creation: Create the database and basic four tables (except query tables) with constraints.
-- Automation: A Bash script (mainFile.sh) automates the following processes
                                                                           |__ Scraping
                                                                           |__ Database Insertion
                                                                           |__ Query Execution

Software need to be installed
-------------------------------

-- Ensure PostgreSQL v14 is installed and running.

Project Files
-------------

-- SQL scripts for creating tables, relations, loading data and executing queries. 
-- Bash script for automation

Acknowledgments
---------------

-- Data sourced from Reddit (https://www.reddit.com/).

-- This project has been developed for educational purposes.

