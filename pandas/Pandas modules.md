#### 1. Fundamentals of Pandas

What Pandas Is — difference between Series and DataFrame

Creating DataFrames

From dictionaries, lists, NumPy arrays, or CSV/Excel files

Example: pd.DataFrame(), pd.read_csv(), pd.read_excel()

Inspecting Data

df.head(), df.tail(), df.info(), df.describe(), df.shape, df.dtypes

#### 2. Data Selection & Indexing

Selecting columns: df['col'] vs. df[['col1', 'col2']]

Selecting rows:

df.loc[] → label-based selection

df.iloc[] → index-based selection

Boolean indexing and filtering with conditions

Setting and resetting indexes: df.set_index(), df.reset_index()

#### 3. Data Cleaning & Preprocessing

Handling missing values:

df.isnull(), df.dropna(), df.fillna()

Removing duplicates: df.drop_duplicates()

Renaming columns: df.rename()

Changing data types: df.astype()

String operations: df['col'].str.strip(), .lower(), .contains(), etc.

#### 4. Data Transformation

Sorting: df.sort_values(), df.sort_index()

Applying functions:

df.apply(), df.map(), df.applymap()

Lambda functions

Replacing values: df.replace()

Binning data: pd.cut(), pd.qcut()

#### 5. Aggregation & Grouping

Grouping data: df.groupby('col')

Aggregations: .sum(), .mean(), .count(), .agg(), .describe()

Multi-level groupby

Pivot tables: pd.pivot_table()

Crosstabs: pd.crosstab()

#### 6. Merging, Joining & Concatenating

Merge / Join: pd.merge()

Concat / Append: pd.concat(), df.append() (note: append is deprecated)

Join on indexes: df.join()

#### 7. Working with Dates & Times

Converting to datetime: pd.to_datetime()

Extracting parts: .dt.year, .dt.month, .dt.day, .dt.weekday

Filtering by date range

Resampling time-series data: df.resample('M').sum()

#### 8. Data Visualization (with Pandas built-in or Matplotlib)

Quick plots: df.plot()

Common types: line, bar, histogram, boxplot, scatter

Customizing plots

#### 9. Performance & Optimization

Working with large datasets

Using df.memory_usage()

Vectorization (avoiding loops)

Sampling data: df.sample()

#### 10. Exporting & Importing Data

Read & write:

pd.read_csv(), pd.to_csv()

pd.read_excel(), pd.to_excel()

pd.read_json(), pd.to_json()

df.to_sql() for databases

#### Bonus: Real-world Analyst Use Cases

Cleaning messy CSVs

Exploratory data analysis (EDA)

Feature engineering for ML

Automating reports

Combining datasets from multiple sources