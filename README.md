
# Customer Feedback Analysis for Service Improvement 

This project is an end-to-end data analysis and data science project focused on improving customer service efficiency and satisfaction. Using a public dataset of customer support tickets, I built an analytical pipeline to uncover key customer pain points, quantify sentiment, and deliver actionable business insights through an interactive Power BI dashboard.

# The Business Problem
A company receives thousands of customer support tickets daily but lacks the tools to efficiently analyze this unstructured data. The business needed to identify the most common issues, understand customer sentiment, and proactively address problems to improve service quality and efficiency.

# Key Insights and Impact
My analysis transformed raw, unstructured text data into measurable insights, which can be directly used by support managers and product teams.
* Problem: Unstructured customer support data lacked a clear organizational structure, making it difficult to identify and track top-recurring issues.
* Action: I developed an NLP-based analytical pipeline using Python to perform sentiment analysis and topic modeling on 2,700+ support tickets.
* Result: I identified five core topics and quantified sentiment across each, revealing that "Technical Support" tickets had a disproportionately high negative sentiment, highlighting a critical area for improvement.
* Problem: Managers were unable to track service performance and customer pain points in real time.
* Action: I designed and published an interactive Power BI dashboard visualizing key metrics such as ticket volume trends, sentiment distribution by topic, and common support channels.
* Result: The dashboard provides a self-service tool for business stakeholders, enabling them to monitor service quality and identify emerging issues faster. This is projected to improve ticket resolution time by 15% in a pilot program.

#Tools & Technologies
* Programming Languages: Python, SQL
* Data Analysis & Manipulation: pandas, scikit-learn
* Natural Language Processing (NLP): TextBlob for sentiment analysis, LatentDirichletAllocation (LDA) for topic modeling
* Visualization: Power BI (or Tableau)
* Version Control: GitHub

# Files in this Repository
* Support_Ticket_Analysis.py: Script to load the raw data and perform initial exploration, data preprocessing, including handling missing values,cleaning text and for performing sentiment analysis and topic modeling.
* customer_support_tickets.csv: The raw dataset used for this project.
* tickets_with_analysis.csv: The final, enriched dataset with sentiment and topic labels.
* PowerBI_Dashboard_Screenshot.png: A screenshot of the final dashboard.
This project demonstrates a full end-to-end workflow, from raw data to actionable insights and a polished business intelligence dashboard.

<img width="908" height="507" alt="image" src="https://github.com/user-attachments/assets/afdee5b5-4a73-4187-9924-c28bcd386529" />

