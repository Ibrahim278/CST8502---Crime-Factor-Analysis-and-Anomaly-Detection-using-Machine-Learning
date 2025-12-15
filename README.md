# CST8502---Crime-Factor-Analysis-and-Anomaly-Detection-using-Machine-Learning
This project focuses on analyzing the Dallas Police Dataset using machine Learning techniques to identify key factors that affect crime and detect anomalies in Police Data.

In this group-based project, we sampled 10000 instances from the Dallas Police Dataset. Preprocessing was done on the sampled data such as clustering X and Y Coordinates into Zones, Removing redundant DateTime data, dropping missing data and duplicate instances. 

The raw data can be found at: https://www.dallasopendata.com/Public-Safety/Police-Incidents/qv6i-rri7/about_data

The models used were:
- Decision Trees and Random Forest for classifying the type of incident.
- Clustering to group similar incidents together.
- Local Outlier Factor, Isolation Forest, Mahalanobis-Distance and One-Class SVM to identify anomalies within the data.

The tools used were:
- Python
- VS Code - This was chosen over Jupyter Notebook due to its integration with LLM Agents.
- MS Office to present our work and type our final report.
