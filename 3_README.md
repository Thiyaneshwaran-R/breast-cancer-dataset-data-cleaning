This notebook focuses on data cleaning, inspection, and basic exploration of the Breast Cancer Wisconsin (Diagnostic) dataset using Python and Pandas.

### 🔍 Steps Performed:

- ✅ **Loaded the dataset** (downloaded from Google)
- ✅ **Checked structure and summary:**
  - Used `.info()` to inspect column data types and non-null counts
  - Used `.describe()` to get basic statistics (mean, std, min, max)
  - Used `.head()` and `.tail()` to view sample rows
  - Used `.shape` to get number of rows and columns

- ✅ **Accessed specific data:**
  - Retrieved specific **columns** (e.g., `df['column_name']`)
  - Retrieved specific **rows** using `df.loc[]` and `df.iloc[]`
  - Filtered data using basic conditions (e.g., `df[df['column'] > value]`)

- ✅ **Checked for missing (null) values:**
  - Used `df.isnull().sum()` to find missing values
  - Filled or removed null values using `.fillna()` or `.dropna()`

- ✅ **Detected and handled outliers:**
  - Used methods like IQR (Interquartile Range)
  - Replaced outliers with upper/lower thresholds or appropriate values

- ✅ **Visualized data:**
  - Created **histograms** for key numeric columns using `Matplotlib` or `Seaborn`

---

### 📁 Dataset Source:
Breast Cancer Wisconsin (Diagnostic) – available on UCI Repository and various open sources.
