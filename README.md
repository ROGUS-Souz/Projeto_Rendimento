# Project_Rendimento

📊 Fish Yield Analysis Project

📝 Description

An automated Python system for analyzing and reporting fish yield (Salmon and Tuna) at the RIO SUL store. The project collects data from Excel spreadsheets, processes monthly yield information, generates visual charts, and sends comprehensive reports via email.

🎯 Objective

To automate the process of monitoring and reporting fish yields, replacing manual analysis with an efficient system that provides quick insights into operational performance.

⚙️ Main Features

Data Import: Automatic reading of Excel spreadsheets with production data

Smart Filtering: Automatic selection of relevant data (category, date, period, store, weight)

Temporal Analysis: Data processing by specific year and month (July/2022)

Chart Generation: Creation of bar visualizations with Plotly Express

Automated Reports: Email sending with HTML formatted tables and PDF charts

🛠️ Technologies Used

Pandas: For data manipulation and analysis

Plotly Express: For graphical visualizations

win32com: For Outlook integration and automatic email sending

Excel: As a source of structured data

📋 Process Flow

Import of Salmon and Tuna data from separate spreadsheets

Filtering by "YIELD" category and year 2022

Specific analysis for the month of July

Calculation of daily and monthly averages

PDF chart generation

Automatic email composition with formatted tables

Sending with attachments of generated charts

📊 Generated Outputs

Daily yield bar charts (PDF)

Tables with daily averages formatted as percentages

Monthly average report

Professional email with all consolidated data

💡 Benefits

Time Saving: Automates what was a manual process

Standardization: Ensures consistency in reports

Clear Visualization: Charts facilitate data interpretation

Efficient Communication: Automatic sending to stakeholders

Data-Driven Decisions: Provides reliable data for decision making

👥 Target Audience
Operations managers, production supervisors, and quality control teams in the fish processing industry.
