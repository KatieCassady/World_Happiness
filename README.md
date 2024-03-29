# World Happiness and COVID
Capstone project for CodeLouisville Data Analysis Course

This project will compare the World Happiness Report for 2015 to 2022 (https://www.kaggle.com/datasets/mathurinache/world-happiness-report?resource=download) to look for a correlation between countries happiness level with their trust in their government and freedom to make life choices over before, during, and post-COVID. I found this dataset for the World Happiness survey on Kaggle. This got me thinking about what impact COVID had on the general happiness of people around the world before, during, and after the global pandemic. I theorized that general happiness, trust in government, and the belief of freedom to make your own life choices would go down during the COVID years due to the rampant conspiracy theories, high death toll, and interaction restrictions that were reported in the United States. I chose a country that was consistendly near the top of the chart over the course of the 8 years present in the data, Switzerland, one in the midrange, Turkey, and one that was near the bottom, Togo.  Note regarding Togo: this country was not always at the bottom of the list, but other countries that were lower were not present in all the data sample years. I also chose to include the United States for a "home" reference. The United States was consistently in the mid-to-upper teens with the exception of 2021 where it slipped to 20th.

### Installation  
#### How to Run the Project   
**Before you begin, ensure you have met the following requirements:**    
You have installed Python. This project was developed using Python 3.12.0. If you don't have Python installed or if you need to upgrade your current version, you can download it from the [official Python website](https://www.python.org/downloads/).  

You have installed Git, which is necessary to clone the repository. If you don't have Git installed, you can download it from the [Git](https://git-scm.com/downloads).  

**Follow these steps to run the project on your local machine:**  
#### Clone the repository  
1. Clone the repository to your Github account  
2. Access the repository from your command line or preferred CMD software  
3. Install a virtual environment.   

*It's recommended to create a virtual environment to keep the project's dependencies isolated from your system's Python environment. You can create a virtual environment using the following command:*  

On Windows:    
On macOS and Linux: python3 -m venv venv  
This will create a new virtual environment named venv in your current directory.  

#### Activate the virtual environment using the following command:   

On Windows:   

```python
.\venv\Scripts\activate
```

On macOS and Linux:   

```python
source venv/bin/activate
```
  
*Your prompt should change to indicate that you are now operating within a Python virtual environment.*  

#### Install the required packages by running the following command:  

```python
pip install -r requirements.txt
```
  
You are now ready to run the project!   

#### Run the .ipynb file:
If you have Jupyter Notebook installed, enter jupyter notebook and open the .ipynb file.  

If you are using Visual Studio Code, open the .ipynb file and run the cells using the run button that appears at the top left of each cell.  

To deactivate the virtual environment when you are done, simply type deactivate in your terminal.  

---
### Project Notebooks
Run the project notebook cells from top to bottom.
