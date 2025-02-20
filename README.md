This Automated Data Pipeline simplifies the process of data preprocessing, exploratory data analysis (EDA), and report generation in Google Colab. It helps users by automating tedious tasks, enabling them to focus on deeper data analysis and model development.

**Key Features & Benefits**

**📂 Seamless Data Upload & Handling**
- Supports CSV, Excel (.xls, .xlsx), and JSON file formats.
- Automatically detects the file type and loads it into a Pandas DataFrame.
- Helps users avoid manual file conversions and formatting issues.

**🛠 Data Cleaning & Preprocessing**
- Removes duplicates, ensuring clean and reliable data.
- Handles missing values:
- Numeric columns: Filled with the mean value.
- Categorical columns: Replaced with "Unknown" to avoid data loss.
- Encodes categorical variables using Label Encoding.
- Reduces time spent on cleaning and ensures data consistency.

**📊 Feature Scaling for Improved Model Performance**
- Uses StandardScaler to standardize numerical columns.
- Helps in maintaining uniform scale for better ML model accuracy.

**🚨 Outlier Detection for Better Data Quality**
- Identifies potential outliers using Z-score analysis.
- Highlights records with outlier scores greater than 3.
- Ensures better decision-making by filtering extreme values.

**📈 Automated Data Visualization**
- Histograms for numerical distributions.
- Box plots to identify outliers.
- Correlation heatmap to detect relationships between features.
- Helps in quick pattern recognition and feature selection.

**📑 Comprehensive Dataset Summary & Insights**
- Displays total records, column details, missing values, and basic statistics.
- Generates an interactive HTML report using ydata_profiling.
- Saves time by providing ready-to-use insights for analysis.

**🔍 Automated GroupBy Analysis**
- Automatically selects the first categorical column and computes mean - aggregations for numeric features.
- Helps users quickly analyze trends and patterns without manual intervention.

**⚡ Google Colab Integration for Effortless Execution**
- Uses files.upload() to prompt users to upload their dataset.
- Displays results directly within Colab, making it easy to analyze data.
- Generates a downloadable HTML report for deeper exploration.
