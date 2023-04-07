Overview
The AlgaeCrop SQLite database contains information on microalgae and their metabolites, such as lipid content, protein content, fatty acids, amino acids, vitamins, and more. The database consists of two types of tables:

Sources Table: Contains information on the sources of data used in the AlgaeCrop project, such as the reference ID, DOI, Harvard reference, title, link, input data, version, and keywords.

Data Tables: Contains information from various sources on microalgae and their metabolites. Each data table is named by an ID indicating the type of data it contains, such as lipid for lipid content data. Each data table has a column indicating the source it is from (source_id) and the sample number within that source (run_id). Depending on the type of data, the table may contain additional columns for information on the metric unit, method of acquiring data, and data points.

Accessing the Database
The AlgaeCrop SQLite database is available on GitHub as a .sqlite file. To access the database, you will need to download the file and open it using an SQLite client. Here's an example of how to open the database using the SQLite command-line client:
