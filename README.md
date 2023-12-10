# UiPath RPA Application - ReFramework
**Overview** 
This UiPath RPA (Robotic Process Automation) application is designed to automate the process of retrieving information about cars from incoming emails. The application listens for emails with specific subjects and attachments, extracts data containing car models and brands, scrapes details from contactcars websites, and organizes the data in an Excel sheet.

**Features**
Email Listener:

Monitors incoming emails for a specific subject.
Processes emails with attachments containing car information.

Data Extraction:
Extracts car models and brands from email attachments.

Web Scraping (contactcars):
Navigates to contactcars website.
Scrapes car details, including name, description, and price.

Excel Sheet Management:
Writes the scraped data into an Excel sheet.

Sends an email to the client with the Excel sheet attached
