# Copilot DAX Development Notes

## 1. Total Sales

### Copilot suggestion
Copilot suggested a SUM-based measure to calculate total sales.

### Final version
The final measure uses SUM(Fact_Sales[sales_amount]).

### Changes
No major correction was required.

---

## 2. MoM Growth %

### Copilot suggestion
Copilot suggested using CALCULATE and DATEADD to compare current month sales with the previous month.

### Final version
The final measure calculates the percentage difference between current and previous month sales.

### Changes
I checked the date column and adjusted the calculation to use Dim_Date[date].

---

## 3. Running Total Sales

### Copilot suggestion
Copilot suggested a CALCULATE and FILTER approach for cumulative sales.

### Final version
The final measure uses ALLSELECTED and MAX date to calculate cumulative sales.

### Changes
I adjusted the date context so the running total responds correctly to report filters.

---

## 4. City Sales Rank

### Copilot suggestion
Copilot suggested using RANKX over the city dimension.

### Final version
The final measure ranks cities according to Total Sales.

### Changes
I used DESC and DENSE ranking so the highest-selling city receives rank 1.

---

## 5. Average Transaction Value

### Copilot suggestion
Copilot suggested dividing total sales by the number of transactions.

### Final version
The final measure uses DIVIDE to safely calculate average transaction value.

### Changes
I checked the measure against the transaction count.
