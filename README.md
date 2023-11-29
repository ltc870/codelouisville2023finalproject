# Number of Trees Planted vs Crime in Louisville, KY Analysis

---

## Background

This data analysis project is based on several studies done based on several studies of greenspaces/canopy's and crime in urban environments. Two articles on this topic are below:

[Urban Greenspace Linked to Lower Crime Risk Across 301 Major Cities](https://www.research.ed.ac.uk/en/publications/urban-greenspace-linked-to-lower-crime-risk-across-301-major-us-c%20%20%20)

[The Impact of Green Space on Violent Crime in Urban Environments: An Evidence Synthesis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6950486/)

This project focused on the city of Louisville, KY and looked at the potential relationship between the number of trees planted and the amount of crime in a given zip code.

---

## Question Addressed by This Project

The main question for this project is, does the number of crime instances in a zip code correlate with the amount of trees planted in that same zip code. More specifically, if there is a higher number of trees planted in a zip code, then does that mean there will be a lower number of crime instances in that zip code.

## Gathering the data

The data utilized in this study was retrieved from [Louisville Metro Open Data](https://data.louisvilleky.gov/). The two datasets utilized was [Louisville Metro KY - Urban Heat Island Neighborhood Data](https://data.louisvilleky.gov/datasets/louisville-metro-ky-urban-heat-island-neighborhood-data/explore) and [Louisville Metro KY - Crime Data 2022](https://data.louisvilleky.gov/datasets/louisville-metro-ky-crime-data-2022/explore), with both datasets being developed in 2022.

## How to Run The Project

This project was developed utilizing Visual Studio Code as the IDE, Python programming language, Jupyter Notebook, and Pandas, Matplotlib, and Seaborn libraries.

1. Fork the repository to your GitHub account and clone it to your local machine.
2. To run the program, I utilized Visual Studio Code, but you can use any IDE of your choice (I believe PyCharm's free version only allows you to read Notebooks, not edit them).
3. You will find a `requirements.txt` file within this repo which can be used to create a virtual environment.
   - To create the virtual environment:
     - Linux/macOS: `python 3 -m venv venv`
     - Windows: `python -m venv venv`
   - Activating the virtual environment:
     - Linux/macOS: `source venv/bin/activate`
     - Windows: `venv\Scripts\activate`
   - Then install the packages listed in the requirements.txt file: `pip install -r requirements.txt`
   - To deactivate the virtual environment after running the project: `deactivate`

## Code Louisville Project Requirements

1. **Load Data**
   - I read from two CSV files
2. **Clean and Operate on the Date While Combining Them**
   - I removed all of the null values from both csv datasets individually, then I combined both csv datasets by using a pandas merge on the ZIP_CODE column. I then removed the resulting null values from the new dataset.
3. **Visualize/Present Your Data**
   - I made 3 matplotlib or seaborn visualizations to display my data.
4. **Best practices: Enhance your project to a higher tier that will impress employers and help other programmers understand your project.**
   - I utilized a virtual environment and I included instructions in this README on how a user should set one up.
5. **Interpretation of Data**
   - I annotated my code with markdown cells in Jupyter Notebook; I wrote clear code comments; and I provided a README file.

## Findings

Unfortunately, the findings of this study ended up being contrary to the original hypothesis of this project. I found that as the amount of trees planted increased per zip code, the amount of crime increased, but this finding was very, very weak correlation. This finding however was in line with the studies found in [The Impact of Green Space on Violent Crime in Urban Environments: An Evidence Synthesis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6950486/). Although the researchers found that most of research pointed at a reduction of crime with an increase of greenery, there were studies that found the opposite, that the amount of greenery did not affect the amount of crime in a neighborhood.

Some points to think about with this project: - This project did not take into account that neighborhoods can be in multiple zip codes. - This project also did not look at if there was a relationship between the specific type of crime vs. the amount of trees planted for a given zip code.
I believe these points should be taken into account before ruling out the possibility that nature does not play a role in reducing crime in Louisville, KY. It could very well be possible that an increase in nature could assist in decreasing a specific kind of crime.
