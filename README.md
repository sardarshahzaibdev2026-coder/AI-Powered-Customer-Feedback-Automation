# AI-Powered Customer Feedback Automation

## Project Overview

This project is an AI-powered customer feedback automation system built using n8n. It collects customer feedback through an online form, uses Google Gemini AI to classify the feedback, stores the information in Airtable, and sends automated notifications through Slack and Gmail.

## How It Works

1. A customer submits feedback through an n8n form.
2. The form collects:
   - Full Name
   - Email Address
   - Contact Number
   - Feedback
3. Google Gemini AI analyzes the feedback and classifies it into one of three categories:
   - Complaint
   - Compliment
   - Future Addition Request
4. The Merge node combines the customer information with the AI classification result.
5. The Switch node routes the feedback according to its category.
6. Airtable stores the feedback in the corresponding category table.
7. Slack sends notifications to the relevant channel.
8. Gmail automatically sends a category-specific email to the customer.

## Tools & Technologies

- n8n – Workflow Automation
- Google Gemini – AI-Powered Feedback Classification
- Airtable – Customer Feedback Management
- Slack – Automated Notifications
- Gmail – Automated Email Notifications

## Key Features

- Automated customer feedback collection
- AI-powered feedback classification
- Three-category feedback routing
- Automated Airtable record creation
- Category-based Slack notifications
- Automated customer email responses
- Integration of multiple applications through n8n

## Feedback Categories

| Category | Description |
|---|---|
| Complaint | Customer reports a problem or expresses dissatisfaction. |
| Compliment | Customer shares positive feedback or appreciation. |
| Future Addition Request | Customer suggests a new feature or improvement. |

## Project Screenshots

The `screenshots` folder contains five images demonstrating:

1. Complete n8n workflow
2. Customer feedback form
3. Airtable records
4. Slack notifications
5. Gmail notifications

## How to Import the Workflow

1. Download the `user feedback.json` file from this repository.
2. Open your n8n instance.
3. Import the downloaded workflow JSON file.
4. Configure your own Google Gemini, Airtable, Slack, and Gmail credentials.
5. Verify the Airtable tables and Slack channels.
6. Test the workflow with sample feedback before activating it.

## Project Purpose

This project demonstrates how AI and workflow automation can simplify customer feedback management, reduce repetitive manual work, and improve communication with customers.

## Important Notes

- This is a demonstration and portfolio project.
- You must configure your own credentials before running the workflow.
- The workflow may require adjustments depending on your Airtable tables, Slack channels, and account configurations.
- Never share API keys, passwords, access tokens, or private credentials publicly.
