# Boost Python Analyses with AI and Google Colab

This project demonstrates how data analysts and data scientists can leverage Google Colab's integrated Gemini AI capabilities to dramatically streamline their Python data analysis workflow.

## Overview

The project showcases four powerful ways to use AI assistance in your data analysis:

1. **Dataset Exploration** 
2. **Data Cleaning** 
3. **Error Resolution** 
4. **Visualization Generation** 

## Key Features

### 1️⃣ Dataset Exploration

Use Gemini AI prompts to quickly understand your data:

```
Can you show me what columns are in df?
For numeric variables, show me the distribution of the data.
For categorical variables, show me the unique values and their frequencies.
```

Find data quality issues with targeted prompts:

```
Can you analyze df for missing data? Please:
1. Show me the count and percentage of missing values for each column
2. Visualize the missing data patterns with a heatmap
3. Suggest appropriate strategies for handling the missing values
```

### 2️⃣ Data Cleaning

Handle outliers and skewed distributions without memorizing complex code:

```
I have a column called 'runtime' in my movie dataset. I'd like to floor and cap this variable at the 5th and 95th percentile respectively.

Show me the distribution of the data before and after the capping/flooring logic.
```

```
My 'imdb_rating' column has a skewed distribution. I'd like to:
1. Apply a log transformation to this column
2. Show me the distribution before and after transformation
3. Calculate skewness and kurtosis before and after transformation
```

### 3️⃣ Error Resolution

Quickly diagnose and fix common coding errors:
- Missing aligned tabs
- Mismatched data types
- Misspelled variable names

Simply click the "Explain Error" button in Google Colab or describe the error.

### 4️⃣ Visualization Generation

Create professional visualizations using plain English:

```
Give me a line chart for average runtime by release_year. Requirements:
- Return the chart only for release_year 1990 and after
- Add a smoothing line that shows a 5-year moving average
- Make the average runtime line a dotted grey line
- Add a legend on the top right corner
```

## Getting Started

1. Open Google Colab (colab.research.google.com)
2. Create a new notebook
3. Upload your dataset or connect to your data source
4. Start using Gemini AI prompts to analyze your data

## Example Dataset

This project uses a movie dataset containing:
- Movie titles
- Release years
- Runtimes
- IMDB ratings
- Metacritic scores

A good starting point is the [TMDb Movie Dataset](https://www.kaggle.com/code/edumisvieramartin/christmas-movies-eda/input) from Kaggle.

## Benefits

- Focus on insights rather than writing boilerplate code
- Reduce time spent debugging syntax errors
- Create professional visualizations without memorizing complex plotting syntax
- Streamline data cleaning and preprocessing workflows

---

*Note: This is not sponsored content. These techniques are shared to help analysts and data scientists improve their workflow efficiency.*
