# AI-Powered Customer Feedback Automation

## Project Overview
This project is an AI-powered customer feedback automation system built using n8n. It automatically collects customer feedback, classifies it using AI, stores the results in Airtable, and sends notifications through Slack and Gmail.

## How It Works
1. Customers submit feedback through an online form.
2. An AI model analyzes the feedback.
3. Feedback is classified into one of three categories:
   - Complaint
   - Compliment
   - Future Addition Request
4. The workflow routes the feedback to the appropriate Airtable table.
5. Notifications are sent through Slack and Gmail.

## Tools & Technologies
- n8n
- Ollama (Llama 3.2)
- Airtable
- Slack
- Gmail

## Key Features
- Automated customer feedback collection
- AI-powered feedback classification
- Automatic Airtable record management
- Slack notifications
- Gmail notifications
- Automated workflow routing

## Project Screenshots
Screenshots of the workflow, feedback form, Airtable records, Slack notification, and Gmail notification are available in the `screenshots` folder.

## How to Import the Workflow
1. Download the `user feedback.json` file.
2. Open your n8n instance.
3. Import the workflow JSON file.
4. Configure your own Ollama, Airtable, Slack, and Gmail credentials.
5. Test the workflow before activating it.

## Project Purpose
This project demonstrates how AI and workflow automation can reduce manual work and improve customer feedback management.

## Important Note
This is a demonstration project. You must configure your own credentials before running the workflow.
