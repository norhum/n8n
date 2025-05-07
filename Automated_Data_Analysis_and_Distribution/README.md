# Daily Automated Workflow with n8n

This project demonstrates a **daily automated n8n workflow** that integrates data from an **HTTP API** and **Airtable**. The workflow merges and sorts the data, then uses a conditional **'If'** node to route the data through two distinct paths:

- One path converts the data to **JSON** and sends it via **Gmail** and **Discord** for quick alerts.
- The other path processes the data in a loop, converts it to **CSV**, and sends it through a separate **Discord** message for detailed reporting.

This automation ensures real-time alerts for quick insights and detailed reports for in-depth analysis.

![Automated Workflow](스케린샷%202025-05-03%20153619.png)

### Features
- **API and Airtable Integration**: Automatically fetches and merges data from an HTTP API and Airtable.
- **Conditional Routing**: Uses the 'If' node to define paths based on the data.
- **Quick Alerts**: Sends immediate notifications via **Gmail** and **Discord** in JSON format.
- **Detailed Reporting**: Processes and sends detailed reports in CSV format via **Discord**.
  
This workflow is designed for flexibility and can be adapted to various use cases, streamlining daily data processing and reporting tasks.
