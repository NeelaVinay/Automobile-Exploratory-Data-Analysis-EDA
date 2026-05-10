# Automobile-Exploratory-Data-Analysis-EDA

**🚗 Automobile Exploratory Data Analysis (EDA)**

**📌 Project Overview**

This project performs an end-to-end Exploratory Data Analysis on the 1985 Ward's Automotive Yearbook dataset. The primary objective is to understand the technical specifications, insurance risk ratings ("symboling"), and normalized loss payments of various automobile entities to uncover the drivers behind vehicle pricing and safety.

**📊 Dataset Insights**

The dataset encompasses three core dimensions of automotive data:

Specifications: Physical and mechanical characteristics (engine size, horsepower, dimensions, etc.).

Insurance Risk (Symboling): A rating scale from -3 (safe) to +3 (risky) indicating an auto's insurance risk relative to its price.

Normalized Losses: The relative average loss payment per insured vehicle year, adjusted for size classification.

**🛠️ Tech Stack**
Language: Python

Libraries: * Pandas: Data manipulation and structured analysis.

NumPy: Numerical processing.

Matplotlib/Seaborn: Statistical data visualization.

**🚀 Key Analysis Workflow**

Data Ingestion & Profiling: Loading the automobile.csv dataset and performing an initial audit of data types and statistical distributions.

Statistical Summary: Utilizing descriptive statistics to identify central tendencies in pricing (Mean: ~$13,207) and physical attributes.

Data Cleaning: Handling missing values (e.g., filling missing stroke values) and data type normalization.

Feature Engineering: Segmenting data, such as binning horsepower into "Low," "Medium," and "High" categories to simplify comparative analysis.

Multi-dimensional Grouping: Pivoting data by drive-wheels and body-style to analyze price variance across different vehicle configurations.

**📈 Featured Findings**

Price Distribution: Vehicle prices in this dataset range from a minimum of $5,118 to a maximum of $45,400.

Horsepower Impact: The analysis categorizes vehicles into horsepower bins, identifying "Medium" as a common tier for brands like Toyota and Alfa-Romero.

Drivetrain Variance: Significant price differences were observed when pivoting by drive-wheels, with Rear-Wheel Drive (RWD) vehicles generally commanding higher price points compared to Front-Wheel Drive (FWD) alternatives.

**📂 Project Structure**

├── 6_Exploratory Data Analysis.ipynb   # Main analysis notebook
├── automobile.csv                      # Raw dataset
└── README.md                           # Project documentation

👤 Author

Neela Vinay | Data Analyst

⭐ If this project helped you, please consider giving the repository a star!
