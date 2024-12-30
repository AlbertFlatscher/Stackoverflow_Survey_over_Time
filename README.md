# Stackoverflow_Survey_over_Time
Analysing stackoverflow survey results over a time period from 2011 to 2024

### Table of Contents
 
1. [Project Motivation](#motivation)
2. [Data](#data)
3. [Files](#files)
4. [Libraries](#libraries)
5. [Results](#results)
6. [Licensing](#licensing)

## Project Motivation <a name="motivation"></a>

Writing a data science blog post is one of the projects within the Udacity Data Scientist Nanodegree Program. The StackOverflow Annual Developer Surveys from 2019 till 2024 were chosen as the data basis. This timeframe was optimal for the questions at hand. Older survey results were looked at as well but proved to be too different from later suvreys to be included.

## Data <a name="data"></a>
The focus of the Stack Overflow survey is to understand significant aspects of jobs in software development.</br>

2024 number of survey paritcapants: 65437
2023 number of survey paritcapants: 89184
2022 number of survey paritcapants: 73268
2021 number of survey paritcapants: 83439
2020 number of survey paritcapants: 64461
2019 number of survey paritcapants: 88883

The survey data of each year contains of the following two CSV files:
<ul>
  <li>schema of the survey data, containing information about the columns (i.e., questions) used within the survey
  <li>survey results, containing thousands of individual answers to the survey questions 
</ul>

Further information about the original dataset can be found at [StackOverflow](https://survey.stackoverflow.co)

## Files <a name="files"></a>

The following files are provided within this project:
<ul>
  <li><b>Shifts_in_Programming_Preferences_from_2019_to_2024.ipynb:</b> Jupyter Notebook containing the Python code for the analysis</li>
  <li><b>README.md:</b> This file</li>
</ul>

## Libraries <a name="libraries"></a>

I used a Jupyter notebook (Python) for the analysis. The ipynb file should run on any Python 3 version (3.0.* or higher) without any problems.</br>

Here are the additional Python libraries used within this project:

<ul>
  <li>Numpy Version "1.26.4"</li>
  <li>Pandas Version "2.2.2"</li>
  <li>Matplotlib Version "3.8.4"</li>
  <li>seaborn Version "0.13.2"</li>
  <li>glob Version "0.5.0"</li>
</ul>

You will need to download Stackoverflow’s Annual Developer Surveys from 2019 till 2024 and put it in a path of this form:

os.path.join('..', 'data', 'stack-overflow-developer-survey-' + year)

[Here](https://insights.stackoverflow.com/survey) you can find the data. </br>

## Results <a name="results"></a>

The aim of the analysis was to get an overview of the most used programming languages from 2019 till 2024. From this starting point it was tried to find trends and conclusions.

The results can be found on Medium [Blog](https://techdataman.github.io/2024/09/16/blog-post-first.html).

## Licensing <a name="licensing"></a>

Thanks to Stack Overflow for providing the data.
