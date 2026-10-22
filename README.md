# Nike vs. Adidas: Sneaker Pricing, Discount & Ratings Analysis

Data and opinion mining on an e-commerce dataset of **Nike and Adidas sneakers** (prices, discounts, ratings and review counts) to compare the two brands' pricing and discount strategies and see what drives customer engagement.

## Key findings
- Adidas has more distinct products than Nike in the dataset.
- Listing and sale prices are strongly right-skewed: a few premium sneakers raise the averages.
- Review counts are highly concentrated: a small number of products get most of the reviews.
- Listing price and sale price have the strongest correlation; **discounts alone don't drive higher ratings or more reviews**.
- The most-reviewed products tend to be **mid-priced with meaningful discounts**, suggesting pricing drives engagement.
- Top-rated products come from both brands.

## Methods
Data cleaning · descriptive statistics · distribution analysis · correlation analysis · brand-level comparisons · visualization

## Tech stack
Python · pandas · NumPy · Matplotlib · seaborn · Jupyter

## Files
| File | Description |
|---|---|
| `sneaker_analysis.ipynb` | Full analysis notebook |
| `data/sneakers.csv` | Product dataset (name, ID, listing price, sale price, discount, brand, rating, reviews) |

## How to run
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook sneaker_analysis.ipynb
```

---
*Programming for Data Science final project – M.S. Data Science, University of St. Thomas (Houston).*
