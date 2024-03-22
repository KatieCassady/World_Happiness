# World Happiness and COVID
Capstone project for CodeLouisville Data Analysis Course

This project will compare the World Happiness Report for 2015 to 2022 (https://www.kaggle.com/datasets/mathurinache/world-happiness-report?resource=download) to look for a correlation between countries happiness level with their trust in their government and freedom to make life choices over before, during, and post-COVID.

Instructions
1. Clone the repo to your machine
2. Create a virtual environment and install the packages listed in the requirements.txt
3. Remove columns that are unique to different years or I know I don't plan to use. Most are standard deviations: 
2015 - Standard
	Region
	Dystopia Residual
2016 - Lower Confidence Interval
	Upper Confidence Interval
	Region
	Dystopia Residual
2017 - Whisker.high
	Whisker.low
	Dystopia Residual
2020 - Regional indicator
	Standard error of ladder score
	upperwhisker
	lowerwhisker
	Ladder score in Dystopia	
	Explained by: Log GDP per capita
	Explained by: Social support
	Explained by: Healthy life expectancy
	Explained by: Freedom to make life choices
	Explained by: Generosity	
	Explained by: Perceptions of corruption
	Dystopia + residual
2021 - Regional indicator
	Standard error of ladder score
	upperwhisker
	lowerwhisker
	Ladder score in Dystopia	
	Explained by: Log GDP per capita
	Explained by: Social support
	Explained by: Healthy life expectancy
	Explained by: Freedom to make life choices
	Explained by: Generosity	
	Explained by: Perceptions of corruption
	Dystopia + residual
2022 - Whisker-high
	Whisker-low
4. Create a dictionary of all years combined
5. Combine dataframes and concatinate
6. Replace and N/A or blank spaces with 0
7. Create pivot tables for Happiness Score, Trust, and Freedom
8. Generate visualizations with matplotlib for a high happiness country (Switzerland), a midrange country (Turkey), and a low happiness country (Togo). Including the United States as well as a home comparison.

Virtual Environment Instructions
1. After you have cloned the repo to your machine, navigate to the project folder in GitBash/Terminal
2. Create a virtual environment in the project folder. python3 -m venv venv
3. Activate the virtual environment. source venv/bin/activate
4. Install the required packages. pip install -r requirements.txt
5. When you are done working on your repo, deactivate the virtual environment. deactivate