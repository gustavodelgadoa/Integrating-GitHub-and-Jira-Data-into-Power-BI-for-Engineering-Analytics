# GitHub + Jira Integration Dashboard
This project replicates a professional engineering dashboard i'm building during my Software Engineering Internship, demonstrating how to integrate **GitHub** and **Jira** data into a **Power BI** dashboard for visualizing commit activity, ticket velocity, and developer contributions **without using any internal or organization-specific data**.
> This is a personal project to showcase my skills in API integration, ETL pipeline development, and BI tooling.
---
## Overview
This project extracts and links:
- **GitHub commits** (by user, timestamp, lines changed)
- **Jira tickets** (by key, status, assignee, etc.)
- Then maps them together to calculate:
  - Commits per Jira ticket
  - Commits per developer/team
  - Code churn (lines added/removed)
  - Sprint and velocity trends

The final output is visualized in **Power BI**.

---
## Technologies Used

| Tool/Platform | Purpose |
|---------------|---------|
| **Python**    | ETL scripting and data processing |
| **GitHub API**| Extract commit metadata |
| **Jira API**  | Retrieve ticket information |
| **Power BI**  | Data visualization and dashboard creation |
| **Regex**     | Parse commit messages for Jira ticket keys |

---

## How It Works
---


## Security & Ethics

- This repo **does not contain** any internal or proprietary data.
- All sample data is either:
  - Public GitHub repo data
  - Generated mock Jira data

---

## What I Learned

- Working with REST APIs and pagination
- Regex and text parsing in data pipelines
- Cleaning and transforming data across two platforms
- Building BI dashboards with end-users in mind
- Leading a solo software engineering analytics tool from start to finish

---

## Future Improvements

- Automate data sync using cron jobs or cloud functions  
- Include pull request reviews and story point estimates  
- Migrate to a cloud data warehouse like Snowflake or BigQuery

---

## Author

**Gustavo Delgado**  
Software Engineering Intern  
📧 gustavodelgadoa@outlook.com  
🌐 [LinkedIn](https://www.linkedin.com/in/gustavodelgado0101/)

---

## License

MIT License
