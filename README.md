# BBC News Classification

## Members
- **Amine HADDOU**
- **Marouan BOULLI**

## Project Purpose
The aim of this project is to develop a news article recommendation system. This system functions as follows:
- A user-provided news article is classified by an algorithm.
- Another algorithm searches for similar articles within the same category, providing a ranked list based on their similarity to the user's article.

The dataset employed is the publicly available [BBC News Classification](https://kaggle.com/competitions/learn-ai-bbc), comprising 2225 articles across 5 categories: **business**, **entertainment**, **politics**, **sport**, and **tech**.

## Installation of Dependencies

### Direct Installation in Notebooks
Execute the first cell in the notebooks to install all necessary dependencies using the `!pip` command.

### Using pipenv (Recommended)

Dependencies can be installed using `pipenv`. 

- Install `pipenv` librairie :
```console
pip install pipenv 
```
- Install the dependecies and a virtual environnement by running :
```console
pipenv install 
```
- Activate the environnement by running :
```console
pipenv shell 
```
- Depending on your code editor, make sure to have selected the right kernel : `BBC_news_classification-<Random_string>`

## Project Structure

### Data Folder
The `Data` folder contains the datasets used for both training and testing the model:
- Original dataset: [BBC News Train](./data/BBC_News_Train.csv)
- Preprocessed dataset: [BBC News Train Preprocessed](./data/BBC_News_Train_PREPROCESSED.csv)
- LLM evaluation articles: [10 random articles](./data/ten_articles.csv), [Reference article](./data/reference_article.csv)

### Assets
This folder houses all the models and databases that were utilized throughout the project.

### Report
Key documentation and source files are located here:
- Project Report: [Report in PDF](./report/report.pdf)
- Report Source Code: [Source code in LaTeX](./report/report.tex)
