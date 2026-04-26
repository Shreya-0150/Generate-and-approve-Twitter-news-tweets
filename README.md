# AI Tweet Generation & Approval Workflow

Workflow Link: https://n8n.io/workflows/14842-generate-and-approve-twitter-news-tweets-with-groq-google-sheets-and-telegram/

---

## Overview

This project is an automated workflow built in n8n to generate tweets from trending news and manage their approval before publishing.

---

## What it does

* Fetches latest news from Google News
* Generates multiple tweet variations using AI
* Sends tweets to Telegram for review
* Allows approval or rejection via buttons
* Stores and updates data in Google Sheets

---

## Flow

1. Scheduled trigger runs the workflow
2. News articles are fetched and processed
3. AI generates tweets in different styles
4. Tweets are sent to Telegram
5. User approves or rejects
6. Status is updated in Google Sheets

---

## Tools Used

* n8n
* Google Sheets
* Telegram Bot
* Groq (LLM)

---

## Output

* 5 tweet variations per article
* Status tracking (Approved / Rejected)
* Organized data in Google Sheets

---

## Notes

* Avoids duplicate articles
* Uses unique IDs for tracking
* Includes error handling for AI output

---

## Author

Shreya Bhingarkar
