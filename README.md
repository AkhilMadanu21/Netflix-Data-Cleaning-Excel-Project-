# Netflix Data Cleaning Project (Excel + Power Query)

This project involves cleaning and preprocessing the Netflix Movies and TV Shows dataset using Microsoft Excel.



## 📌 Objective:
To clean and preprocess the raw Netflix Movies and TV Shows dataset using **Excel Power Query**.

## 🛠️ Tools Used:
- Excel (Power Query)
- Basic Excel formulas (for formatting, date handling)

## 🧹 Cleaning Steps Performed:
1. **Handled Missing Values**:
   - Used filters and Power Query to detect and replace blanks.
   - Filled or removed rows with empty critical data.

2. **Removed Duplicates**:
   - Checked across all columns A–L using `COUNTIF()` and Excel filters.

3. **Standardized Formatting**:
   - Trimmed text, fixed inconsistent casing (e.g., Title Case).
   - Removed extra spaces in all text columns.

4. **Converted Date Formats**:
   - Transformed `date_added` into proper `dd-mm-yyyy` format.

5. **Renamed Column Headers**:
   - Made all column names lowercase and removed extra spaces.

6. **Split Duration Column**:
   - Used `Text to Columns` to separate numeric and unit values from the `duration` column.

7. **Cleaned Rating Column**:
   - Ensured consistency across all rating types (e.g., TV-MA, PG-13).

## 📂 Files Included:
- `netflix_titles_cleaned.xlsx`: Cleaned dataset (final version)


## 📌 Outcome:
Created a clean and consistent dataset ready for further analysis or visualization.

---

## 💡 Bonus:
Want to explore this data further? Try building a Power BI dashboard based on content type, release year, or countries!

