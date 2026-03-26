# Amazon Best Sellers Analysis

I completed this project during a data analytics bootcamp to strengthen my Python and exploratory data analysis skills. The dataset contains Amazon best-selling books and includes variables such as author, genre, user rating, review count, price, and year.

A major part of this project involved identifying and handling missing values, then using the cleaned dataset to examine patterns in pricing, author frequency, and other trends over time. This project gave me additional practice working through a full analysis process, from data inspection and cleaning to summarization and visualization.

## Tools Used

- Python
- pandas
- NumPy
- matplotlib
- seaborn

## Project Focus

This project explored questions such as:

- where missing values were located in the dataset
- how book prices changed over time
- which authors appeared most frequently among best sellers
- how ratings and review counts were distributed
- whether there were noticeable differences across genres

## What I did

- imported and inspected the dataset in Python
- reviewed data types, summary statistics, and missing values
- focused on missing values in the `Price` column
- compared possible approaches for handling null values
- filled missing prices using the average price for the corresponding year
- grouped and summarized the data by year and by author
- created visualizations to examine pricing trends and other patterns

## Key Takeaways

One important part of this project was seeing how data-cleaning decisions can affect the rest of an analysis. Rather than dropping rows with missing prices, I filled them using yearly average prices so that more of the dataset could be retained for later exploration.

The project also gave me more experience using grouped summaries to identify trends in author frequency and pricing patterns across the dataset.

## What I Learned

Through this project, I gained more experience with:

- cleaning data in pandas
- handling missing values
- grouping and summarizing data
- creating basic visualizations
- using exploratory analysis to answer questions from a real dataset

## Files

- `amazon_best_seller.ipynb` — main notebook
- `amazon_bestsellers.csv` — dataset used in the project

## How to Run

Install the required libraries and open the notebook in Jupyter:

```bash
pip install pandas numpy matplotlib seaborn
