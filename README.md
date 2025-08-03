# Chinook Music Store SQL Analysis

This project uses SQL to analyze sales data from the Chinook music store database. The goal is to answer business questions and give useful recommendations.

---

## Dataset

- **Chinook SQLite database**
- Includes info on customers, invoices, tracks, employees, and sales.

---

## Tools Used

- SQLite
- Jupyter Notebook
- ipython-sql (SQL magic in notebooks)

---

## Key Questions Answered

1. **Which music genres sell best in the USA?**
   - Rock is the top genre (53% of sales).

2. **Which employees have the best sales performance?**
   - Jane Peacock had the highest total sales.

3. **Which countries bring in the most revenue?**
   - USA leads in total sales. Czech Republic and India have high value per customer.

4. **Do people buy full albums or single tracks?**
   - Only 18.6% of purchases are full albums.

---

## Recommendations

- Focus on Rock genre for new purchases.
- Run small marketing tests in countries with high customer value.
- Stock full albums to avoid losing album buyers.

---

## How to Use

1. Clone this repo.
2. Install `ipython-sql` with: `pip install ipython-sql`
3. Open the notebook in Jupyter: `Chinook_Analysis.ipynb`

---

## Files

- `chinook.db` – Database
- `Chinook_Analysis.ipynb` – SQL analysis notebook
- `README.md` – Project summary


