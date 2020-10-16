![](./assets/preview.png)
<h1 align="center"> Classify.Jobs</h1>

<p align="center">
  <a href="https://github.com/SandeepBalachandran/classify.jobs/releases/" target="_blank">
    <img alt="GitHub release" src="https://img.shields.io/github/v/release/SandeepBalachandran/classify.jobs?include_prereleases&style=flat-square">
  </a>

  <a href="https://github.com/SandeepBalachandran/classify.jobs/commits/master" target="_blank">
    <img src="https://img.shields.io/github/last-commit/SandeepBalachandran/classify.jobs?style=flat-square" alt="GitHub last commit">
  </a>

  <a href="https://github.com/SandeepBalachandran/classify.jobs/issues" target="_blank">
    <img src="https://img.shields.io/github/issues/SandeepBalachandran/classify.jobs?style=flat-square&color=red" alt="GitHub issues">
  </a>

  <a href="https://github.com/SandeepBalachandran/classify.jobs/pulls" target="_blank">
    <img src="https://img.shields.io/github/issues-pr/SandeepBalachandran/classify.jobs?style=flat-square&color=blue" alt="GitHub pull requests">
  </a>

  </br>

  <a href="https://standardjs.com" target="_blank">
    <img alt="ESLint" src="https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square">
  </a>
  
  <a href="" target="_blank">
    <img alt="ESLint" src="https://img.shields.io/github/stars/SandeepBalachandran/classify.jobs">
  </a>
  
  <a href="" target="_blank">
    <img alt="ESLint" src="https://img.shields.io/github/forks/SandeepBalachandran/classify.jobs">
  </a>
  
  <a href="" target="_blank">
    <img alt="Codesize" src="https://img.shields.io/github/languages/code-size/SandeepBalachandran/classify.jobs.svg">
  </a>
  <a href="" target="_blank">
    <img alt="Top Language" src="https://img.shields.io/github/languages/top/SandeepBalachandran/classify.jobs.svg">
  </a>
  
</p>
<hr>

# Table of contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Installation](#installation)
- [Contribute](#contribute)

# Introduction

<h3 align="center">The primary objective is to make the searches easy for job seekers. </h3>

- The database of the application will be populated using the classifications of jobs predicted by the model  along with job types. 
- A certain number of new entries are manually updated to db within certain time periods from different * trusted sources. 
- Once the classification of  new entries is triggered by the admin or user using the front end, the model will predict the labels and pass it to the application.
- The backend will store the data to db.  
- Users can view these changes using the frontend view provided.

# Usage
<i>For developers</i>

- Upload the csv file by  using the front end view provided.
- Backend will process the csv and pass it to the trained model
- Model will predict the labels and pass the csv to the backend.
- Backend stores the data to the database and updates the front end.


<i>For users</i>
- You will be provided with job types and classification in the front end view.
- Ex : Angular developer - Google - Front Developer
- Front developer is the classification model predicted.



# Installation



# Contribute
