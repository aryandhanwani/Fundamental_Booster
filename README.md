# 📊 Excel Exam 1 – Excel Practice Workbook

This project contains various Excel practice exercises to strengthen understanding of formulas, dynamic ranges, lookups, filtering, and date calculations.

---

## 📁 File Included

- **Excel Exam 1.xlsx** — Main workbook with solved and practice exercises.

---

## ✅ Key Concepts Covered

### 1. `VLOOKUP` with `MATCH`
- Dynamically retrieves values without hardcoding column numbers.
- Example:
  ```excel
  =VLOOKUP(I271, A271:E290, MATCH("Name", B270:B290, 0), FALSE)
2. XLOOKUP with flexible search
Uses conditions to dynamically find employee or salesperson details.
Example use case: Lookup using multiple options like name, region, or amount.
3. FILTER Function
Filters values based on dynamic conditions.

Examples:

=FILTER(G496:G515, G496:G515 > 250)
=FILTER(G496:G515, (G496:G515 > 200) * (G496:G515 < 300))  // between 200 and 300
4. DATEDIF for Calculating Duration
Finds the number of days/months/years between two dates.

Example:

=DATEDIF(A453, B453, "D")   // Difference in days
5. Dynamic Ranges with OFFSET + COUNTA
Automatically adjust ranges as data grows.

Example named range formula:

=OFFSET(Sheet1!$A$2, 0, 0, COUNTA(Sheet1!$A:$A)-1, 2)
6. Name Extraction Using LEFT and FIND
Extracts first name from full names.

Example:

=LEFT(A2, FIND(" ", A2)-1)
📅 Sample Data Sheets
DOB List: 20 sample names with birthdates.
Start-End Dates: Useful for DATEDIF, age calculation, and timeline analysis.
Sales Data: Used in filtering and trend analysis.
💡 Useful Tips
+ operator for OR logic in array formulas
* operator for AND logic in FILTER conditions
Wrap DATEDIF in ABS() to avoid errors for reversed dates
Use Ctrl + T to convert data into dynamic Excel tables
📈 Suggested Extensions
Add charts for sales trends using dynamic ranges.
Apply conditional formatting to highlight top performers.
Use dropdowns (Data Validation) for user-driven lookups.
📌 Notes
Make sure Excel version supports dynamic array functions like FILTER, XLOOKUP, SEQUENCE.
Named ranges or tables can make dynamic formulas cleaner and more manageable.
👨‍🏫 Created for learning and review purposes.


---

Let me know if you'd like this file exported or edited based on what's specifically inside the Excel file!
