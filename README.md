# GreatExpectationsTask
Hello! It's my GX task for program DQE Intermediate Level.

To run this task on your machine, you need:
1. Clone repository
2. Download and install ODBC Driver 17 for SQL Server
3. Set virtual environment. Activate. 
	pip install virtualenv
	python -m venv env
	source ./env/Scripts/activate
4. Go to /greatexpectationstesttask/ProjectFiles/ and run 'pip install -r requirements.txt'
5. Run 'great_expectations docs build'

# Data Docs
Data Docs in Great Expectations are used to create an interactive documentation site for your data. They provide a convenient and comprehensive way to browse your data assets and examine their properties, statistics, and validation results.
Data Docs are generated automatically by Great Expectations and can be customized and augmented with additional information such as descriptions, example queries, visualizations, and other metadata.
Some of the benefits of using Data Docs in Great Expectations are:

Increased data quality and trustworthiness by making validation results and metadata transparent and accessible.
Improved communication and collaboration among data stakeholders by providing a common and interactive documentation site.
Enhanced data exploration and analysis by providing a comprehensive view of data assets and their properties.
Reduced development and maintenance costs by automating the creation and updating of documentation and validation results.

# Report example
It's preview:

![image](https://user-images.githubusercontent.com/104168878/236620776-1424874c-aa09-492b-9e16-03e81769bc76.png)

# If not work and problem like from db side:
1. Check settings in  SQL Server Configuration Manager -> SQL Server Network Configuration -> Protocols for <SQLEXPRESS> -> TCP/IP Properties -> IP Addresses
2. At least one ip address could be active and enabled.
