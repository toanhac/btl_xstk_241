# Statistical Analysis Project - GPU Dataset

## General Information
- **Project title**: GPU Data Analysis
- **Course**: Probability and Statistics
- **Group**: Group_8
- **Date**: October 7, 2024

## Project Description
This is a final course project for the Probability and Statistics class. The project analyzes a dataset of graphics processing units (GPUs) stored in `All_GPUs.csv`. The goal is to clean, process, visualize, and interpret the data using statistical methods.

## Report Overview (`main.Rmd`)
The R Markdown file `main.Rmd` contains the full code and explanations for each step of the analysis. The main sections include:

### 1. Data Preprocessing
- Import the CSV file and handle missing values.
- Convert variables to appropriate data types (`numeric`, `character`, etc.).
- Remove columns with high rates of missing data.

### 2. Descriptive Statistics
- Compute metrics like mean, median, min, max, etc.
- Visualize data distributions using histograms and boxplots.

### 3. Correlation Analysis
- Use `cor()` and `corrplot()` to identify variable relationships.
- Create a correlation matrix to assist with feature selection.

### 4. Multivariate Analysis
- Use `GGally::ggpairs()` to generate a matrix of pairwise plots.
- Visualize groupings by brand, memory, price, and other features.

### 5. Insights and Conclusions
- Compare average prices between NVIDIA and AMD GPUs.
- Highlight key features that influence GPU price.

## How to Use
1. Place `All_GPUs.csv` in the same folder as `main.Rmd`.
2. Open `main.Rmd` in RStudio.
3. Click Knit to render the document into HTML or Word.

## Requirements
- R version >= 4.0
- Required packages: `questionr`, `knitr`, `ggplot2`, `GGally`, `corrplot`, `gridExtra`

## Authors
- Hoa Toàn Hạc
- Đặng Châu Anh
- Nguyễn Công Thành
- Nguyễn Chí Duy Khang
- Nguyễn Lê Khôi Nguyên
