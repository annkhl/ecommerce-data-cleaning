# Data Source

**Dataset:** [UCI Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

Real transactional data from a UK-based online retailer, covering 2009-2011. This project uses the **"Year 2009-2010"** sheet — 525,462 rows, 8 columns (InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country).

## Why the raw file isn't included in this repository

The original `online_retail_II.xlsx` file is large due to the high row count, which exceeds convenient limits for storage and browsing on GitHub. Instead:

- The original dataset can be downloaded directly from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
- This repository includes the **processed file** (`excel/ecommerce_analysis.xlsx`) containing the `clean_data` and `summary` sheets, which demonstrate the analysis results
- A detailed breakdown of the data quality issues found is available in [documentation/data_quality_report.md](../documentation/data_quality_report.md)
------------------------------
# Джерело даних

**Датасет:** [UCI Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

Реальні транзакційні дані британського онлайн-магазину за 2009-2011 роки. У цьому проєкті використано лист **"Year 2009-2010"** — 525 462 рядки, 8 колонок (InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country).

## Чому сирий файл не додано в репозиторій

Оригінальний файл `online_retail_II.xlsx` важить понад 25-70 МБ через велику кількість рядків, що перевищує зручні ліміти для зберігання та перегляду на GitHub. Замість цього:

- Оригінальний датасет можна завантажити напряму з [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
- У репозиторії міститься **оброблений файл** (`excel/ecommerce_analysis.xlsx`) з листами `clean_data` та `summary`, які й демонструють результат роботи
- Детальний опис виявлених проблем якості даних — у [documentation/data_quality_report.md](../documentation/data_quality_report.md)
