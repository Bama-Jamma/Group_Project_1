# Group Project 1
First Group Project for Rutgers Data Science Boot Camp

# Pokemon Data Analysis
This repository contains Python code and data files for analyzing Pokemon data. The analysis focuses on exploring various attributes of Pokemon and visualizing their distributions.

## Contents
The repository contains the following files:

* pokemon_data.csv: The dataset used for analysis, containing information about different Pokemon species.
* PokeProj1Start.ipynb: A Jupyter Notebook file containing the Python code for data analysis.
* README.md: This file.

## Dependencies

The following Python libraries are required to run the code:

* pandas (version 1.3.3 or higher)
* matplotlib (version 3.4.3 or higher)
* numpy (version 1.21.2 or higher)
* scipy (version 1.7.1 or higher)
* Pokemon CSV File located in the "Resources" folder

## Analysis
The pokemon_analysis.ipynb notebook contains the Python code for analyzing the Pokemon data. The analysis includes the following:

Distribution of Special Defense by Type: A boxplot is created to visualize the distribution of Special Defense for each type of Pokemon.

Linear Regression: Linear regression is performed to analyze the relationship between different attributes of Pokemon. The notebook includes linear regression analysis for Attack and Defense, HP and Defense, HP and Weight, Weight and Speed.

Outliers: Outliers are identified for the attributes of Defense, HP, Weight, and Speed.

Top 10 Heaviest Pokemon: A bar chart is created to display the top 10 heaviest Pokemon based on their weight.

Overall Highest Stats by Type: The Pokemon types with the highest overall stats are identified and visualized using a bar chart.

Boxplot of Total Stats: A boxplot is created to show the distribution of total stats among all Pokemon, including the median and outliers.

## Usage
To run the analysis, follow these steps:

Make sure you have the required dependencies installed.
Clone this repository or download the files to your local machine.
Open the pokemon_analysis.ipynb notebook using Jupyter Notebook or any other compatible environment.
Run each code cell in the notebook to perform the analysis and generate the visualizations.
Results
The analysis provides insights into various attributes of Pokemon, such as their special defense, attack and defense relationship, outliers in different attributes, heaviest Pokemon, and overall highest stats by type. The visualizations help in understanding the distributions and relationships between these attributes.

Please refer to the notebook for detailed code and analysis explanations.


# Pokémon Project Analysis
This project focuses on analyzing Pokémon data using a combination of data from the PokeAPI and a provided CSV file. It aims to provide insights into various aspects of Pokémon statistics, including average stats per type, distribution of stats, frequency of types, and identification of top Pokémon with high stats.

### Data Sources
The project utilizes two main data sources:

* PokeAPI:The PokeAPI is an open API that provides comprehensive information about Pokémon. In this project, the API is used to retrieve details such as ID, name, type, height, HP, and weight for the first 151 Pokémon.

* CSV File: A CSV file named "Pokemon.csv" is provided as a supplementary dataset. It contains additional information about Pokémon, including their stats and types.

#### Data Processing and Analysis
The project involves several steps of data processing and analysis. Here's an overview of the key steps:

* Data Retrieval: The project starts by making API calls to the PokeAPI to retrieve details for the first 151 Pokémon. The obtained data includes the Pokémon's ID, name, type(s), height, HP (base stat), and weight.

* Data Integration: The data retrieved from the API is merged with the data from the provided CSV file. This integration ensures that the final dataset contains a comprehensive set of attributes for each Pokémon.

* Data Cleaning and Transformation: The merged dataset undergoes a cleaning and transformation process to standardize the data. This includes converting the names to lowercase, removing leading and trailing whitespaces, and dropping unnecessary columns.

#### Statistical Analysis and Visualization: 
The cleaned dataset is then analyzed to derive meaningful insights. The project calculates average HP, Attack, and Defense for each Pokémon type and visualizes them using bar charts. Additionally, box plots are created to showcase the distribution of HP and special attack values across different Pokémon types. The project also counts the frequency of each Pokémon type and presents the results in bar and pie charts. Lastly, the project identifies the top 10 Pokémon with the highest special attack values and visualizes them using a bar chart.

#### Results and Findings
The analysis of the Pokémon data yielded several interesting findings:

* Average HP: The project calculated the average HP for each Pokémon type. It was observed that certain types, such as Dragon and Normal, tend to have higher average HP compared to others.

* Average Attack and Defense: The average Attack and Defense values were also analyzed for each Pokémon type. This analysis revealed variations in attack and defense strengths across different types. For example, Fighting and Dragon types tend to have higher average attack values, while Steel and Rock types have higher average defense values.

* Distribution of HP and Special Attack: The box plots created for HP and special attack values provided insights into the spread and range of these attributes for different Pokémon types. Some types, such as Ghost and Dragon, exhibited a wider range of HP values, indicating greater variability within those types.

* Pokémon Type Frequency: The project counted the frequency of each Pokémon type and presented the results using bar and pie charts. This analysis revealed the prevalence of certain types, such as Water and Normal, which are more abundant compared to others.

* Top Pokémon with Highest Special Attack: By identifying the top 10 Pokémon with the highest special attack values, the project showcased some exceptional Pokémon known for their powerful special attacks. This information can be useful for Pokémon trainers and enthusiasts looking to build formidable teams.

##Conclusion
The Pokémon Data Analysis project combines data from the PokeAPI and a provided CSV file to offer insights into various aspects of Pokémon statistics. By leveraging data processing, statistical analysis, and visualization techniques, the project provides a comprehensive analysis to allow you to understand what Pokémon might give you the edge in battle.

