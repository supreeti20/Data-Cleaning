 Project Overview:

In this project, I performed end-to-end data cleaning using SQL on a real-world dataset containing global tech layoffs. The goal was to transform a raw, inconsistent dataset into a clean, analysis-ready format for better insights and reporting.

🔧 Key Tasks Performed:

Created staging tables to protect original data and enable safe transformation.

Identified and removed duplicate rows using ROW_NUMBER() and CTEs.

Cleaned and standardized the industry and country fields (e.g., resolving naming inconsistencies like 'CryptoCurrency' → 'Crypto').

Converted textual date fields into proper SQL DATE format using STR_TO_DATE().

Used self-joins to fill in missing industry values based on matching company names.

Removed rows with irrelevant null data (both total_laid_off and percentage_laid_off being NULL).

Ensured final dataset (layoffs_staging2) was clean, consistent, and ready for analysis.

📊 Tools & Skills Used:

SQL (Data Transformation & Cleaning)

CTEs & Window Functions

Data Normalization

Error Handling & Null Treatment
