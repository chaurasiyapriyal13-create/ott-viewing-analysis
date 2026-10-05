#  OTT Viewing Habits Analyzer

A beginner-friendly Python project exploring OTT viewing habits, sleep duration and self-reported productivity.

##  Objective

Practice data cleaning, exploratory data analysis and visualization while examining patterns in digital consumption.

## Dataset

The CSV contains these columns:

| Column | Description |
|---|---|
| `viewing_hours` | Daily time spent watching OTT content |
| `sleep_hours` | Average sleep duration per night |
| `productivity_rating` | Self-reported productivity, from 1 to 10 |

**Data source:** Synthetic sample data for learning and demonstration. It does not represent actual survey findings.

## Analysis

The project aims to:

- Calculate average daily OTT viewing time.
- Summarize sleep duration and productivity ratings.
- Create a scatter plot comparing viewing hours with sleep hours.
- Explore patterns without making causal claims.

## Technologies

- Python
- Pandas
- Matplotlib

##  Project Files

- `analysis.py` — Python analysis script
- `ott_data.csv` — Sample dataset
- `README.md` — Project documentation

## How to Run

Install the required libraries:

```bash
pip install pandas matplotlib
```

Keep the CSV and script in the same folder, then run:

```bash
python analysis.py
```

##  Limitations

Synthetic data is useful for demonstrating the workflow but cannot support conclusions about real people. An association between viewing time and sleep does not prove that OTT usage causes sleep changes.

## Future Improvements

- Analyze anonymous, consent-based survey responses.
- Compare viewing habits across different groups.
- Add productivity visualizations.
- Build an interactive Streamlit dashboard.

## Author

**Priyal Chaurasiya**  
B.Sc. Data Science
