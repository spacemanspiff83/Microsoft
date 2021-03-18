# Phase 1 Data Science project - Microsoft 

**Authors**: Arjun Rao

## Overview

This is the first solo project assigned as part of Flatiron school's Data science program. Flatiron school's Data Science program is a bootcamp which delves into the world of data science, giving students in depth knowledge and experience in data science technologies and terminologies to embark on a new career in Data science. As part of the final project in phase 1, we were presented with a problem where Microsoft is looking to establish its own movie studio and is need of guidance on which productions would ensure a successful launch. Data was sourced for multiple online movie databases which outline many data points (production costs, domestic and foreign gross receipts, genre, etc.). 

## Business Problem

Microsoft's entry into the film industry, however late, does present a unique opportunity. Although Microsoft will be facing stiff competition from other tech companies (Amazon, Netflix, Apple to name a few), it can utilize its current organization to either expand (either under Xbox game studios or Xbox Entertainment Studios) or create a new studio as a new subsidiary. Microsoft task for us is to analyze the current motion picture landscape and advise them on the creation of a successful movie studio. 

To begin we first look to answer the following questions. 

* Identify the most profitable movie studios
* Impact of Genre
* Domestic vs Foreign release


## Data

The analysis primarily focuses on 4 datasets extracted from Box Office Mojo, IMDB and the-numbers.com. The datasets focus on the business problem presented as they contain production budgets, domestic and foreign gross, genre,etc. The goal was to determine the highest likelihood of a successful production given the variables above. 



## Methods

At the start of analysis, it was apparent that the data available would need to be cleaned and formatted so the various datasets could be joined. New consolidated data files were created to simulate a golden source file that contained analysis relevent information. The new data file contained only the columns that were required, all other fields were removed. New columns were added and logic applied to indicate profit or loss. Visualization was done using matplotlib.



## Results

Most Profitable Studios

(./images/TopStudios.png)

Most profitable Genres

(./images/Profit-loss-genre.png)

Production costs vs. profit/loss

(./images/prod-budget-impact.png)

Release type

(./images/release-type.png)


## Conclusions

Based on the analysis done, we can provide the following recommendations:
* Higher likelihood of success if Microsoft were to produce a film in Action, Adventure and Comedy genres
* Production budgets greater than $20MM typically yield successful films
* To maximize chance of a successful production, any new film will need to be released in both domestic and foreign markets, this will help in reaching a wider audience base.

In conclusion, I would recommend that Microsoft release a movie that meets the 3 specific criteria above as they have proven to be successful. 
Further analysis will be required in the future by adding additional data sets as they become available. It could also be expanded upon by revenue generated on streaming platforms.




## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact Arjun Rao (arjunmrao@gmail.com)

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── Microsoft.ipynb                     <- Narrative documentation of analysis in Jupyter notebook
├── data_cleaning.ipynb                 <- Narrative documentation of analysis in Jupyter notebook
├── Microsoft Project Presentation.pdf  <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
