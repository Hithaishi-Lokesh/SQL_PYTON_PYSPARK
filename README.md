# SQL_PYTON_PYSPARK
Here’s a quick guide to essential ** Pandas | SQL | PYSPARK ** functions, categorized into: - Data Importing 📝 - Data Cleaning 🧼 - Data Statistics 📊

Here's a quick guide to essential Pandas functions, organized by category:

Data Importing 📝
pd.read_csv(): Load data from a CSV file.
pd.read_excel(): Load data from an Excel file.
pd.read_json(): Load data from a JSON file.
pd.read_sql(): Load data from a SQL database.
pd.read_html(): Extract tables from HTML.
Data Cleaning 🧼
df.dropna(): Remove missing values.
df.fillna(): Fill missing values with specified values.
df.rename(): Rename columns or indices.
df.astype(): Change the data type of a column.
df.replace(): Replace specific values in a DataFrame.
Data Statistics 📊
df.describe(): Get summary statistics for numerical columns.
df.mean(): Calculate the mean of a column.
df.median(): Calculate the median of a column.
df.mode(): Get the mode(s) of a column.
df.corr(): Compute pairwise correlation of columns.


Here's a quick guide to essential SQL functions, categorized by topic:

Data Importing 📝
INSERT INTO: Add new records to a table.
LOAD DATA INFILE: Import data from a file into a table (MySQL).
COPY: Import data from a file into a table (PostgreSQL).
SELECT INTO: Create a new table from the results of a query.
Data Cleaning 🧼
DELETE: Remove records from a table.
UPDATE: Modify existing records in a table.
TRUNCATE TABLE: Remove all records from a table without logging individual row deletions.
WHERE: Filter records based on specific conditions.
CASE: Conditional expressions to handle various cases in data manipulation.
Data Statistics 📊
COUNT(): Count the number of rows that match a specified condition.
SUM(): Calculate the total sum of a numeric column.
AVG(): Calculate the average value of a numeric column.
MIN(): Find the minimum value in a column.
MAX(): Find the maximum value in a column.
GROUP BY: Group rows sharing a property so aggregate functions can be applied.


Here's a quick guide to essential PySpark functions, categorized by topic:

Data Importing 📝
spark.read.csv(): Load data from a CSV file.
spark.read.json(): Load data from a JSON file.
spark.read.parquet(): Load data from a Parquet file.
spark.read.table(): Load data from a database table.
spark.read.jdbc(): Load data from a JDBC source.
Data Cleaning 🧼
df.dropna(): Remove rows with null values.
df.fillna(): Fill null values with specified values.
df.withColumnRenamed(): Rename columns in a DataFrame.
df.withColumn(): Create or update a column in a DataFrame.
df.drop(): Remove specified columns from a DataFrame.
Data Statistics 📊
df.describe(): Get summary statistics for numerical columns.
df.groupBy(): Group data and perform aggregate operations.
df.agg(): Perform aggregate functions on grouped data.
df.count(): Count the number of rows in a DataFrame.
df.select(): Select specific columns and perform operations (like mean, sum, etc.).




