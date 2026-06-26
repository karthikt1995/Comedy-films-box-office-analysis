# Comedy Films Box Office Analysis (2000–2016)

Exploratory data analysis of 817 comedy films from 2000 to 2016 using the TMDB 5000 Movies Dataset. This project investigates box office performance, budget efficiency, revenue trends, and audience ratings across two decades of comedy filmmaking.

## Key Questions Explored
- Which comedy films grossed the most between 2000–2016?
- Does a higher production budget guarantee higher revenue?
- Which release months generate the highest comedy box office returns?
- Which low-budget comedies achieved the highest return on investment?
- Does audience rating actually drive box office revenue?

## Key Findings
1. **Minions ($1.16B)** is the highest grossing comedy of the era, followed by Toy Story 3 ($1.07B) and Despicable Me 2 ($971M)
2. **Higher budgets positively correlate with revenue** — but significant outliers exist where low-budget films massively outperformed expectations
3. **Comedy revenue trended upward from 2014 onwards**, with mean annual revenue rising sharply in the final years of the dataset
4. **Summer months (June/July)** consistently generate the highest average comedy box office returns
5. **Some low-budget comedies achieved extraordinary ROI** — demonstrating that budget size alone does not determine commercial success
6. **Audience ratings show only weak positive correlation with revenue** — production budget is a stronger predictor of box office performance than critical reception

## Charts
| Chart | Description |
|---|---|
| `top25_comedy_revenue.png` | Top 25 highest grossing comedies (2000–2016) |
| `budget_vs_revenue.png` | Production budget vs box office revenue scatter plot |
| `revenue_by_year.png` | Mean and median revenue trends by year |
| `revenue_by_month.png` | Average revenue by release month |
| `top10_roi_comedy.png` | Top 10 highest ROI comedies |
| `rating_vs_revenue.png` | Audience rating vs revenue (colored by budget) |

## Tools & Libraries
- **Python 3.13**
- **pandas** — data loading, cleaning, and analysis
- **matplotlib** — data visualization
- **seaborn** — enhanced chart styling
- **numpy** — numerical computing and trend line calculation

## Dataset
TMDB 5000 Movies Dataset — [Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## Skills Demonstrated
Exploratory data analysis · Feature engineering · Data cleaning · Statistical correlation · Data visualization · Python for finance and business analytics

## Relevance to Financial Analytics
The analytical techniques used in this project — regression analysis, ROI calculation, correlation analysis, and predictive trend modeling — are directly transferable to financial forecasting, risk assessment, and data-driven decision making in fintech and banking environments.
