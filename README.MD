# 🎵 Chinook Music Store SQL Analysis

This project explores sales data from the Chinook music store using SQL in a Jupyter Notebook environment. The analysis helps derive business insights and provide actionable recommendations for inventory, marketing, and sales optimization.

---

## 📂 Dataset

**Chinook SQLite Database**  
The Chinook database contains information about a digital music store, including tables for artists, albums, customers, invoices, tracks, and employees.

---

## 🧰 Tools & Technologies

- SQLite
- Jupyter Notebook
- SQL (CTEs, joins, subqueries, aggregates)
- `%sql` magic (via `ipython-sql`)

---

## 📊 Business Questions Answered

### 1. 🎸 Which genres sell best in the USA?
- **Rock** dominates sales with 53.4% of tracks sold.
- Other notable genres: Punk, Metal, Blues, and Pop.

### 2. 👨‍💼 How do employees perform in terms of sales?
- **Jane Peacock** leads in total sales.
- Variance in performance closely aligns with hire date.

### 3. 🌍 Which countries are most profitable?
- **USA** and **Canada** are top in sales volume.
- **Czech Republic**, **India**, and **UK** show high **customer lifetime value**, worth small test campaigns.

### 4. 💿 Do customers prefer full albums or individual tracks?
- **Only 18.6%** of purchases are full albums.
- Majority (81.4%) buy single tracks — but ignoring albums risks losing 1/5th of revenue.

---

## 📝 Key Recommendations

- Focus inventory on **Rock albums**.
- Support top-performing reps with insights from Jane’s strategy.
- Run **small-scale marketing tests** in high-LTV countries with smaller customer bases.
- **Purchase full albums** from record companies instead of individual tracks.

---

## Database File Note
The `chinook.db` file is too large to be uploaded directly to GitHub.

To use this notebook:
- Upload your own `chinook.db` file manually
- OR download from [Google Drive / Dropbox link]
- OR use the `.zip` version and extract it in the notebook


