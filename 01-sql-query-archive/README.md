# 🗃️ SQL Query Archive

A curated archive of SQL queries I've written for real analytical work. The goal isn't to show syntax — it's to show **which business question each query answers**.

## Structure

Each query lives in its own file with a consistent header:

```sql
-- ============================================
-- Title       : Monthly Customer Retention Rate
-- Business Q  : How many customers from last month came back this month?
-- Dataset     : (source / schema)
-- Techniques  : self-join, date truncation, CTE
-- ============================================
```

## Categories

| Folder | Contents |
|--------|----------|
| `01-basics/` | SELECT, WHERE, GROUP BY, HAVING — clean fundamentals |
| `02-joins/` | INNER/LEFT/SELF joins solving real matching problems |
| `03-window-functions/` | RANK, LAG/LEAD, running totals, moving averages |
| `04-ctes-and-subqueries/` | Multi-step logic broken into readable CTEs |
| `05-business-cases/` | Retention, cohort, RFM, funnel, growth metrics |

## Why this matters

Anyone can write `SELECT *`. This archive shows I can **translate a vague business question into a precise, readable query** — and explain the result back in plain language.
