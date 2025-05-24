

---

# 🌦️ Weather Logger and Analyser

**Weather Logger and Analyser** is an automated data processing pipeline that collects real-time weather data, stores it in Google Sheets, and generates insightful daily recommendations using the Groq AI model.

---

## 📌 Table of Contents

* [Overview](#overview)
* [Problem Statement](#problem-statement)
* [Objective](#objective)
* [Category](#category)
* [Use Cases](#use-cases)
* [AI Model Concept](#ai-model-concept)
* [Technologies & Integrations](#technologies--integrations)
* [Workflow Summary](#workflow-summary)
* [Benefits](#benefits)
* [Conclusion](#conclusion)
* [Future Enhancements](#future-enhancements)

---

## 🔍 Overview

This project automates the process of fetching hourly or daily weather data, logs it into a Google Sheet, and sends it to an AI model (Groq) to generate natural language weather insights.

---

## ❗ Problem Statement

Manually analyzing weather data for daily planning is time-consuming and inefficient.

---

## 🎯 Objective

To build an automated pipeline that gathers weather data and produces concise, human-readable recommendations for users.

---

## 🗂️ Category

**2. Data Processing Pipelines** – Automating structured data transformation and analysis.

---

## 💡 Use Cases

* Daily personalized weather updates.
* Smart planning for commutes, travel, or events.
* Logging and analyzing weather patterns over time.
* Automated recommendations for agriculture or logistics.

---

## 🤖 AI Model Concept

The system uses the **Groq LLM** to convert structured weather data into a friendly recommendation sentence based on temperature, conditions, etc.

---

## 🛠️ Technologies & Integrations

* **n8n** – No-code automation platform to manage the workflow.
* **OpenWeather API** – Source of real-time weather data.
* **Google Sheets** – Data storage and logging.
* **Groq AI Model** – For summarizing data into a human-readable message.
* **Webhook Nodes** – Trigger and manage external API requests.
* **Code Node** – Custom JS to format data.
* **Respond Node** – Sends confirmation or output.

---

## 🔄 Workflow Summary

* User initiates workflow (manual/scheduled).
* Webhook triggers API call to OpenWeather.
* Extracts weather data (temperature, condition, etc.).
* Appends raw data to Google Sheets.
* Sends structured data to Groq AI model.
* Receives and stores human-friendly message (e.g., “It’s sunny and warm today, perfect for outdoor activities!”).
* Optional: send output via email or chat.

---

## ✅ Benefits

* Saves time by automating data collection and analysis.
* Converts raw data into easy-to-understand messages.
* Enables better planning based on weather.
* Fully no-code/low-code and easy to maintain.

---

## 🧩 Conclusion

Weather Logger and Analyser offers a practical solution to automate data logging and intelligent weather reporting using minimal effort and maximum clarity.

---

## 🚀 Future Enhancements

* Add user input for selecting city or forecast type.
* Store and analyze long-term weather patterns.
* Send daily weather reports via email or messaging bots.
* Improve message quality using sentiment or activity tagging.

---

