# Keyword RSS Alert System (n8n Automation)

An automated workflow built in **n8n** that monitors RSS feeds, filters articles based on target keywords, and delivers responsive, styled HTML email alerts without manual intervention.

## 🚀 Overview

- **Trigger:** Scheduled Cron Trigger (Runs periodically on an interval).
- **Data Ingestion:** Fetches real-time feeds using the native RSS Read node.
- **Filtering Logic:** Evaluates article titles and descriptions for designated keywords using conditional nodes.
- **Delivery:** Dispatches custom, mobile-responsive HTML cards via Gmail/SMTP with publication metadata, summaries, and direct source links.

## 🛠️ Tech Stack

- **n8n** (Workflow Automation Engine)
- **RSS / XML** (Data Feed)
- **HTML5 & Inline CSS** (Responsive Email Card Template)
- **Gmail / SMTP** (Notification Dispatch)

## 📸 Workflow Architecture

<img width="1485" height="656" alt="assignment_workflow_3" src="https://github.com/user-attachments/assets/c8c52093-ffba-4fd6-a3b6-3f829a0913cf" />

## 📬 Sample Email Alert

<img width="1111" height="546" alt="assignment_output_3" src="https://github.com/user-attachments/assets/b6ae9bc7-3308-4d84-8742-7e40b247d356" />
## ⚙️ How to Use

1. Clone this repository.
2. Open your n8n instance and navigate to **Workflows** -> **Import from File**.
3. Select `workflow.json`.
4. Configure your target RSS URL and keyword filter in the respective nodes.
5. Set up your Gmail/SMTP credentials and activate the workflow.
