**Overview**    
This project presents an interactive Power BI dashboard analyzing EEG brainwave activity to explore how neural signals change over time following ketamine administration. The analysis compares two key timepoints: 3 minutes (early stage) showing the immediate neurological impact of ketamine and 80 minutes (later stage) showing the longer term therapeutic effects of ketamine, focusing on variations in brainwave power across different frequency bands.
The goal is to transform raw EEG signals into clear, interpretable insights using data cleaning, transformation, and visualization techniques.  

**Dataset Description**  
The dataset contains EEG signal recordings across multiple brainwave bands:
Delta
Theta
Alpha
Beta
Gamma  

Each record includes:  
TimeStamp – recording time  
Delta, Theta, Alpha, Beta, Gamma – EEG signal power values  
Timepoint – 3 minutes or 80 minutes post-administration  
is_artifact – indicator for noisy/invalid signals  

**Data Preparation Steps:**  
Filtered out artifact signals (is_artifact = FALSE)  
Transformed data from wide format to long format using Power Query  
Standardized brainwave bands into a single “Band” column  
Structured data for comparative time-based analysis  

**Tools & Technologies**  
Power BI  
Power Query (Data Transformation)  
Data Visualization  
Time-Series Analysis  
**Key Insights**  
Gamma and Beta activity show a noticeable reduction at 80 minutes compared to 3 minutes  
Alpha activity remains relatively stable across both timepoints  
Distinct shifts in brainwave distribution suggest changes in neural activity over time  
EEG patterns vary significantly between early and later post-administration stages  

**Dashboard Features**  
Interactive slicers for Band and Timepoint  
Clustered bar chart comparing EEG power across conditions  
Time-series line chart showing signal trends over time  
KPI cards for quick summary of brainwave activity  
Clean, research-style UI with structured visual hierarchy  

**Dashboard Features**  
Interactive slicers for Band and Timepoint  
Clustered bar chart comparing EEG power across conditions  
Time-series line chart showing signal trends over time  
KPI cards for quick summary of brainwave activity  
Clean, research-style UI with structured visual hierarchy  

I am continuously improving my data analysis and visualization skills through real-world projects.


