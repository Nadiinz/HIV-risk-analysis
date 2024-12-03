# HIV-risk-analysis


In this project, I analyzed HIV data sourced as a CSV file from the World Health Organization (WHO) using Azure Databricks. The primary objective was to clean, transform, and present the data in an Power BI report for better insights.

The data transformation process involved cleaning the dataset by removing empty rows and ensuring data quality. Additionally, I introduced fictional columns for age and gender to enhance the presentation and provide more context in the Power BI visualizations.

I also implemented automation in Azure Databricks by scheduling a job that runs the notebook daily, ensuring the data remains up to date. The transformed data was saved as a table in the Hive Metastore (Catalog) and exported as a CSV file for integration into Power BI.

In Power BI, I created an report that showcases key insights, including:

* The number of deaths, survivors, and infected individuals.
* A breakdown of cases by country.
* Visualizations such as graphs and charts to represent numbers with location effectively.


