# Dataset and description

With the datasets that we have chosen, we still had to clean them to be able to merge them into 1 understandable and usable dataset. This was tricky due to the different ways the datasets described some countries. In the next chapters we will go through the process in an way that can be replicated and understood.

## Cleaning

We began the data cleaning process by thoroughly cleaning the Freedom dataset. This involved identifying and removing redundant columns to streamline the dataset and enhance its usability. The original dataset contained 123 columns, which we reduced to 8 essential columns using a Python script. Additionally, we filtered the dataset to include only European countries, narrowing the focus from a global scope to Europe specifically. This filtering was also performed using a Python script.

For the Happiness dataset, we improved readability and accessibility by renaming all the columns to shorter, easier-to-read names. Like the Freedom dataset, we filtered the Happiness dataset to include only European countries, focusing our analysis on Europe.

In the second phase of our data cleaning process, we merged the cleaned Freedom and Happiness datasets into one comprehensive dataset. We ensured the merged dataset was free of duplicates, making it ready for further analysis. 

## Variables Description

The variables in the cleaned dataset can be organised and classified in the following manner:

- Continuous / Interval: `hi_score`, `hi_gdp`, `hi_support`, `hi_expectancy`
- Continuous / Ordinal: `hi_choice`, `hi_generosity`
- Discrete / Ordinal: `hi_corruption`
- Discrete / Nominal: `country`

All other variables are continuous and interval expect `ef_rank` which is discrete and ordinal. This thorough cleaning and merging process provided us with a streamlined and focused dataset, optimized for subsequent analysis and visualization.
