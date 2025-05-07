# Automated Data Collection Pipeline with n8n

This project showcases an **Automated Data Collection Pipeline** built with **n8n**, designed to scrape trending content from **Reddit** and **Hacker News**, store it in **Google Sheets**, and send daily summaries via **Gmail**.

The pipeline performs the following:
- Pulls the **top 5 Reddit posts** and **latest Hacker News stories**.
- Extracts key details such as **title**, **score**, **URL**, and **author**.
- Saves the data into **separate sheets** in Google Sheets.
- Merges the data to create a unified summary.
- Sends **personalized daily email updates**.

![Reddit and Hacker News Workflow](스크린샷%202025-05-03%20151918.png)

### Key Features
- 🔗 **API Integration**: Connects to Reddit and Hacker News APIs to fetch real-time content.
- 📊 **Google Sheets Automation**: Automatically logs and organizes data into sheets.
- ✉️ **Dynamic Email Generation**: Crafts personalized daily emails using data summaries.
- 📦 **JSON Parsing**: Efficiently extracts structured information from API responses.
- 🔁 **Fully Automated**: Designed to run daily with no manual input required.

This project demonstrates practical use of **n8n's workflow automation capabilities** and is a great template for automating content monitoring and reporting tasks.
