# AI Email Analyzer with n8n

An AI-powered email analysis workflow built using self-hosted n8n, Docker, OpenRouter, Gmail API, Google Sheets, and Telegram Bot API.

## Overview

This project automatically monitors incoming Gmail messages, analyzes their content using an LLM, extracts useful insights, stores the results in Google Sheets, and sends real-time notifications via Telegram.

The workflow is fully automated and runs on a self-hosted n8n instance deployed with Docker.

## Features

* Monitor incoming Gmail messages automatically
* Analyze emails using OpenRouter LLMs
* Classify email category
* Assign priority levels (Low, Medium, High)
* Generate concise email summaries
* Store analysis results in Google Sheets
* Send real-time Telegram notifications
* Self-hosted deployment using Docker

## Workflow Architecture

```text
Gmail Trigger
      ↓
OpenRouter AI Analysis
      ↓
JSON Parsing
      ↓
Google Sheets
      ↓
Telegram Notification
```

## Tech Stack

* n8n (Self-Hosted)
* Docker
* OpenRouter
* Gmail API
* Google Sheets API
* Telegram Bot API

## Workflow Overview

<img width="1700" height="581" alt="workflow-overview" src="https://github.com/user-attachments/assets/149b0d66-573c-415f-935d-f6500df53ba7" />

## Google Sheets Results

The analyzed emails are automatically categorized and stored in Google Sheets for reporting and tracking purposes.

<img width="1573" height="311" alt="google-sheets-results" src="https://github.com/user-attachments/assets/32d7ba56-6ff3-4771-a31c-6b546e22fb07" />

## Telegram Notifications

Real-time notifications are delivered through Telegram whenever a new email is processed.

<img width="1043" height="470" alt="telegram-notification" src="https://github.com/user-attachments/assets/8e12aacd-f5e1-4faa-aed6-2f102485f5a9" />

## Use Cases

* Customer support email triage
* Recruitment email monitoring
* Business communication categorization
* Personal inbox automation
* Notification and alerting systems

## Getting Started

1. Configure Gmail OAuth credentials
2. Configure OpenRouter API credentials
3. Configure Google Sheets OAuth credentials
4. Configure Telegram Bot credentials
5. Import the workflow into n8n
6. Activate the workflow

## Project Highlights

* End-to-end workflow automation
* AI-powered email classification
* Real-time notifications
* Cloud service integrations
* API integrations and OAuth authentication
* Self-hosted infrastructure with Docker
