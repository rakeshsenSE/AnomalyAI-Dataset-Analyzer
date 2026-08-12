# 🚨 AnomalyAI — Universal Data Anomaly Detector & AI Summary Generator

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/)
[![Google Gemini](https://img.shields.io/badge/AI-Google%20Gemini%202.5%20Flash-orange.svg)](https://ai.google.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**AnomalyAI** is an automated data analytics pipeline that identifies numerical outliers/anomalies in **any tabular dataset** (e.g., Sales, Cricket/IPL Statistics, Customer Churn, Financial Data) and leverages **Google Gemini 2.5 Flash** to generate clear, executive business insights and actionable recommendations.

---

## ✨ Features

- 📂 **Universal Dataset Support:** Automatically detects numerical columns in any CSV file (`deliveries.csv`, `churn.csv`, `sales.csv`, etc.).
- 📊 **Dynamic Outlier Detection:** Uses statistical standard deviation ($Mean \pm 2 \times STD$) to pinpoint significant anomalies without hardcoding thresholds.
- 🤖 **AI-Powered Insights:** Automatically prompts **Google Gemini AI** to interpret extreme values, explain potential business risks or performance spikes, and offer 2 concrete action plans.
- 🔒 **Secure Configuration:** Uses environment variables (`.env`) for safe API key management.

---

## 🛠️ Tech Stack

- **Language:** Python 3.9+
- **Data Processing:** Pandas
- **AI Model:** Google Gemini 2.5 Flash (`google-genai` SDK)
- **Environment Management:** Python-Dotenv

---

## 🚀 Getting Started

### 1. Prerequisites
Make sure you have Python installed on your machine. Get a free API Key from [Google AI Studio](https://aistudio.google.com/).

### 2. Installation
Clone this repository to your local machine:
```bash
git clone [https://github.com/YOUR_GITHUB_USERNAME/AnomalyAI-Dataset-Analyzer.git](https://github.com/YOUR_GITHUB_USERNAME/AnomalyAI-Dataset-Analyzer.git)
cd AnomalyAI-Dataset-Analyzer
