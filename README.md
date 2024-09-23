# **NYC Neighborhood Insights Platform**
Explore the heart of New York City with our NYC Neighborhood Insights Platform. This comprehensive guide provides detailed, hyper-localized information on each of NYC's boroughs—from housing and crime stats to amenities. Our platform is tailored to meet the needs of residents, visitors, and urban planners with a dynamic search interface, interactive maps, and an AI-powered chatbot.

### **Features:** 

- Dynamic Search Interface: Search by borough or zip code to access detailed insights.
- Interactive Visualizations: Engaging maps and charts provide clear visualizations of data.
- AI Chatbot: An AI-powered chatbot offers interactive, user-specific responses.


### **NYC Data's ETL Process**
File in the repository named : Group 8 - ETL Process - NYC Neighborhood Assessment

This Jupyter Notebook is part of the NYC Neighborhood Insights Platform project, detailing the ETL (Extract, Transform, Load) process for handling data related to New York City neighborhoods. The notebook is designed to extract data from various sources, transform it for consistency and analysis readiness, and load it into a structured format for further use in our platform.

### **Description**
The notebook includes:

- Extraction of borough-level information from municipal databases, real estate listings, Kaggle datasets, and demographic surveys.
- Transformation of data to align with analysis requirements, such as cleaning and normalizing data.
- Loading the processed data into MongoDB, utilizing GridFS for large file management if necessary.

### **Requirements**
- Python 3.x
- Jupyter Notebook
- MongoDB

**Libraries:** pandas, numpy, matplotlib, pymongo

**Setup**
Ensure you have Python and Jupyter Notebook installed on your system.
Install the necessary Python libraries: pandas, numpy, matplotlib, pymongo

>  pip install pandas numpy matplotlib pymongo

> jupyter notebook

> git clone https://github.com/your-username/nyc-neighborhood-insights.git


### **Data Sources**
The data used in this notebook is sourced from public databases and includes: 
Housing prices
Crime statistics
Demographics
(Data Zip File can be found on this link : https://drive.google.com/file/d/1vcyX4zkXFy_wJK8TxmFN4oWj-H4TJonB/view?usp=drive_link)

**Contributing**
Contributions are welcome. If you have improvements or bug fixes, please open a pull request.
