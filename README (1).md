# Fuel Economy (MPG) Analysis

An exploratory data analysis of the classic **Auto MPG dataset**, examining the factors that influence vehicle fuel efficiency using Python, seaborn, and matplotlib.

## Dataset

**Source:** Built into the seaborn library — loaded directly with `sns.load_dataset("mpg")`  
No external file download needed.

The dataset contains fuel economy data for cars from the 1970s and early 1980s, with the following fields:

| Column | Description |
|---|---|
| mpg | Fuel economy in miles per gallon |
| cylinders | Number of engine cylinders |
| displacement | Engine displacement (cubic inches) |
| horsepower | Engine horsepower |
| weight | Vehicle weight (lbs) |
| acceleration | 0–60 mph time (seconds) |
| model_year | Last two digits of the model year |
| origin | Country of origin (USA, Europe, Japan) |
| name | Vehicle name/model |

## Setup

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install seaborn matplotlib pandas
   ```
3. Open and run `mpg-analysis.ipynb`

## What the Notebook Covers

### Visuals & Analysis

| # | Analysis | Type |
|---|---|---|
| 1 | Relationship between horsepower and fuel economy | Scatter plot |
| 2 | Fuel economy summary by country of origin | Summary table |
| 3 | How fuel economy has changed over time | Line chart |
| 4 | Distribution of MPG across all vehicles | Histogram + KDE |
| 5 | Fuel economy by number of cylinders | Box plot |

### Key Findings

- **Horsepower vs. MPG:** There is a clear negative correlation — more powerful cars tend to be less fuel-efficient.
- **Origin:** Japanese and European vehicles have higher average fuel economy compared to American cars, likely due to smaller engine sizes.
- **Over time:** Fuel economy improved significantly after the 1970s, driven by efficiency regulations and advances in automotive technology.
- **Distribution:** Most vehicles fall in a mid-range MPG category, with a right-skewed distribution and a few highly efficient outliers.
- **Cylinders:** 4-cylinder cars are the most fuel-efficient; 8-cylinder cars have significantly lower MPG.

## Tech Stack

- Python 3
- pandas
- seaborn
- matplotlib
- Jupyter Notebook
