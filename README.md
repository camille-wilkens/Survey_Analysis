### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>
This code was written using Python3 and listed below are the required packages:

- numpy
- matplotlib
- seaborn
- pandas
- os
- collections
- warnings
- dataframe_image


## Project Motivation<a name="motivation"></a>


A data science demographic analysis of the 2020 Stack Overflow Survey results focusing on LGBTQ+ IT Developers around the world. The Stack Overflow's annual Developer Survey is the largest survey for IT developers around the world - in 2020, close to 65k people participated in this survey across 183 countries. This survey also captures the diversity of IT developers world-wide. Using the 2020 Stack Overflow survey results and applying data science methodologies, this study will provide insight into the current demographics of the LGBTQ+ IT Developer community by answering the following 3 questions:

1) "What percentage of IT developers are LGBTQ+ vs Straight/Heterosexual?"
2) "What are the Top 10 countries for LGBTQ+ IT developers based on the survey population?"
3) "What is the mean salary difference between LGBTQ+ vs. Straight/Heterosexual IT developers across the Top 10 countries?"

## File Descriptions <a name="files"></a>

Data: survey_results_public_2020.csv -- Data was downloaded from: https://insights.stackoverflow.com/survey

Analysis:  Jupyter Notebook - Survey_Analysis.ipynb.  This notebook contains all the analysis (Descriptive statistics) performed on 2020 Stack Overflow Survey Results to address my three question.  

## Results<a name="results"></a>
1) What percentage of Professional Developers are LGBTQ+ vs Straight/Heterosexual? 8.1% are LGBTQIA and 91.9% are Straight/Heterosexual

2) What are the top 10 countries for LGBTQ+ Professional Developers? United States, United Kingdom, Germany, India, Canada, Brazil, France, Australia, Netherlands, Spain

3) What is the mean salary difference between LGBTQ+ and Straight/Heterosexual Professional Developers by Top 10 Country?


|Country       	| LGBTQ+ Mean Salary|	 
|		| (USD) Difference  |
|---------------|:-----------------:|
|Spain	      	| -42.7%	    |
|Brazil        	| -36.0%	    |
|Canada        	| -25.9%	    |
|United States 	| -19.4%	    |
|France        	| -18.2%	    |
|United Kingdom | -13.7%	    |
|Australia      | -8.6%	    	    |
|Germany 	| -7.9%	            |
|Netherlands    | +20.6%	    |
|India        	| +40.1%	    |



See my blog for additional insight -  https://medium.com/p/e17d2628ec64/edit).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

The dataset used in this analysis was created by Stack Overflow and made available for download under the Open Database License (ODbL).


