UPI Payments Synthetic Dataset (2015-01 to 2025-12)
Files in folder:
- transactions_YYYY_MM.csv : monthly transaction attempts (each file ~10000 rows)
- rewards.csv : cashback/reward ledger rows referencing TxnID
- apps.csv : app lookup (AppID, ParentCompany)
- states.csv : state lookup and metadata
- date_dim.csv : calendar dimension
- data_dictionary.csv : describes files and columns

Notes:
- All IDs are synthetic. Amounts and populations are generated for illustrative purposes.
- Use transactions_YYYY_MM.csv files to import monthly partitions into Power BI or to practice incremental loads.
- Total transaction rows generated: approx 1,320,000.
