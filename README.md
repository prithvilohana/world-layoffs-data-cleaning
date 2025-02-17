📌 World Layoffs SQL Data Cleaning
This project focuses on cleaning and processing the World Layoffs dataset using MySQL. The dataset contains information about layoffs from various companies worldwide.

🚀 Data Cleaning Process
Key steps performed in SQL: ✅ Removed duplicate records
✅ Standardized date formats
✅ Replaced empty values with NULL
✅ Dropped rows where both total_laid_off & percentage_laid_off were NULL

🛠️ Handling Missing Values
Some total_laid_off and percentage_laid_off values were missing, but after EDA, we found that these missing values did not impact the overall analysis, so they were retained as NULL.
📌 Missing Values Count:
🔹 total_laid_off NULL = 378 rows (16%)
🔹 percentage_laid_off NULL = 422 rows (17%)

❌ 16% rows were dropped where both total_laid_off & percentage_laid_off were NULL because they had no analytical value.
