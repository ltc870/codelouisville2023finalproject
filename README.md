# Code Louisville Final Project

---

This project was created to serve as my final project for Code Louisville's Data Science track. This readme file will explain the details of the project and the tools utilized to complete the project.

## Background

This data analysis project is based on several studies done based on several studies of greenspaces/canopy's and crime in urban environments. Two articles on this topic are below:

[Urban Greenspace Linked to Lower Crime Risk Across 301 Major Cities](https://www.research.ed.ac.uk/en/publications/urban-greenspace-linked-to-lower-crime-risk-across-301-major-us-c%20%20%20)

[The Impact of Green Space on Violent Crime in Urban Environments: An Evidence Synthesis](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6950486/)

This project focused on the city of Louisville, KY and looked at the potential relationship between the number of trees planted and the amount of crime in a given zip-code. Before discussing the findings of the project, I will first outline the project requirements detailed by Code Louisville for completing the Data Science Track.

---

## Requirements

---

#### GitHub Repository and Commits:

This project was uploaded to GitHub by way of Git. At the creation of this README.md file, I have 25 commits.

#### README File:

You are currently reading the README.md file that must be included with the project. Within this file, I will discuss the 5 features I implemented from Code Louisville's feature list. I will also include instructions on how to run this program.

#### Data Analysis Implementation

The data was pulled from two csv data sets retrieved from [Louisville Metro Open Data](https://data.louisvilleky.gov/). The data was pulled from [Louisville Metro KY - Crime Data 2022](https://data.louisvilleky.gov/datasets/louisville-metro-ky-crime-data-2022/explore) and [Louisville Metro KY - Urban Heat Island Neighborhood Data](https://data.louisvilleky.gov/datasets/louisville-metro-ky-urban-heat-island-neighborhood-data/explore). Both datasets were published in 2022.

To analyze the data, Jupyter Notebooks was utilized along with Python and its libraries Matplotlib and Seaburn.

#### Feature Selection

1. **Loading Data**
   - Performed a pandas merge between the two aforementioned datasets.
2. **Clean and operate on the data while combining them**
   - Removed all of the null values in both datasets before merging them, then after merging them, removing the values that resulted in a null value.
3. **Visualize/Present your data**
   - Made 3 matplotlib or seaborn visualizations to display data.
4. **Best practices: Enhance your project to a higher tier that will impress employers and help other programmers understand your project.**
   - Utilized a virtual environment. Instructions on how utilize the virtual environment are within this README.md file.
5. **Interpretation of your data**
   - Annotated code with markdown cells in Jupyter Notebook, and wrote clear code comments.
