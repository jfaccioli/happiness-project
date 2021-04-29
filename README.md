# The Happiness Project

# Project Intro

Australia was recently ranked the 12th happiest country in the world according to authors of the 2021 World Happiness Report. The report reviews the state of happiness in the world today. But what Makes us Happy and across the world who is Happy? 

What makes you happy? What makes me happy? Surely there would be endless variables that would make a person happy? How does wealth play a part in happiness? What about Freedom? Education levels? Does that person have a significant other or live in a family unit? Do they own a pet? Do they exercise regularly, eat well, drink perhaps, but maybe only moderately? 
Not only does this report contain clues as to What Makes Us Happy, it is increasingly being used by governments, organisations and civil society to inform policy-making decisions and how well-being can be used to assess the progress of nations. Our analysis will investigate economic, social, and world factors that lead to greater happiness.


# Project structure
```
happiness-project 
|__ .gitignore                                  # gitignore file
|__ envname.yml                                 # conda environment
| 
|__ data/                               # Contains raw data
|   |__ world-happiness-report-2021.csv     # From the 2021 World Happiness Report
|   |__ world-happiness-report.csv          # From historical World Happiness Reports from 2005 to 2020
|   |__ country_data.csv                    # Raw data of analysed countries (source??)
|   |__ Temp_data.csv                       # Historical global temperatures by country from the World Bank
|   |__ Rainfall_data.csv                   # Historical global rainfall by country from the World Bank
|   |__ Sunlight_data.csv                   # Global sunlight by country from Kaggle
|   |__ mental_health.csv                   # Data of common mental disorders from the World Health Organisation
|   |__ covid_data.csv                      # Collected from https://about-corona.net/ using API calls
|   |__ final_df.csv                        # All raw data, cleaned and collated into the one data frame      
|       |__ Final Dataframes/           # Raw data collated into dataframes, cleaned & exported into .csv files
|           |__ happiness_df.csv            # Created from world-happiness-report-2021.csv
|           |__ happiness_time_final.csv    # Created from world-happiness-report & world-happiness-report-2021.csv
|           |__ country_df.csv              # Created from country_data & world-happiness-report-2021.csv
|           |__ weather_data.csv            # Created from country_data, Temp_data, Rainfall_data, Sunlight_data & world-happiness-report-2021.csv
|           |__ mental_health_data.csv      # Created from world-happiness-report-2021 & mental_health.csv
|           |__ final_covid_data.csv        # Created from world-happiness-report-2021 & covid_data.csv   
|           |__ final_df.csv                # All raw data, cleaned & collated into the one data frame 
|
|__ notebooks/
|   |__ Data Exploration and Clean.ipynb    # Cleaning notebook that takes in the raw data and outputs cleaned data for analysis   
|   |__ Analysis.ipynb                      # Analysis of cleaned data with output of plots and Choropleth maps
|   
|
|__ images/             # Contains plots jupyter notebook
|
|__ proposal/
|   |__ Happiness Proposal     # Project proposal 

```

# Usage ??????????

<!-- Create an environment from YAML file and activate environment 
```
# create environment 
conda env create --file envname.yml

# activate environment
conda activate envname
```

Export an environment to a YAML file that can be read on Windows, macOS, and Linux
```
conda env export --name envname > envname.yml -->
```

# Questions 

1. Who is Happy? 
2. What makes us Happy? 
3. How has the Covid-19 global pandemic affected happiness?
4. How happy are we in Australia?


# Datasets 

|-|-|-|
|1| World Happiness Report      |https://worldhappiness.report/ed/2021/| |https://www.kaggle.com/ajaypalsinghlo/world-happiness-report-2021\|
|2| World Bank Group            |https://climateknowledgeportal.worldbank.org/|
|3| World Health Organisation   |https://www.who.int/| |https://www.who.int/publications/i/item/depression-global-health-estimates|
|4| About Corona API            |https://about-corona.net/|
|5| Kaggle Open Source Datasets |https://www.kaggle.com/datasets| 
|6| Country Demographics |https://gist.github.com/tadast/8827699| 
|7| Data World - Cities Ranked by Sunshine Hours |https://data.world/makeovermonday/2019w44 



# Analysis

### Question 1: Who is Happy? 

The 2021 happiness report reviews the state of happiness in the world today. Data from the report was used in this project to investigate which countries across the globe ranked the happiness in the world and how this state of happiness has changed since 2005.

![chart](images/matplotlib.png)



### Question 2: What makes us Happy? 


![chart](images/matplotlib.png)




### Question 3: How has the Covid-19 global pandemic affected happiness?

![chart](images/matplotlib.png)


### Question 4: How happy are we in Australia?

Australia is ranked the 11th happiest country in the world in the 2021 report.  

However, data also shows that the level of happiness in Australia has shown gradual decline since 2006.


# Contributors
- [@adamlever](https://github.com/adamlever)
- [@dcurrigan](https://github.com/dcurrigan)
- [@jfaccioli](https://github.com/jfaccioli)