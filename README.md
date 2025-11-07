# 🎧 spotify_ETL_pipeline  
**Transform Listening Data Into Actionable Insights Instantly**


  <img alt="Python %" src="https://img.shields.io/badge/python-100%25-blue">
</p>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white">
  <img alt="Pandas" src="https://img.shields.io/badge/pandas-DataFrames-150458?logo=pandas&logoColor=white">
  <img alt="SQLAlchemy" src="https://img.shields.io/badge/SQLAlchemy-ORM-d71f00">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-DB-003B57?logo=sqlite&logoColor=white">
  <img alt="Code Style" src="https://img.shields.io/badge/Code%20Style-Black-000000">
</p>

---

## 📚 Table of Contents
- [Overview](#overview)
- [Tech Stack & Languages](#tech-stack--languages)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Testing](#testing)
- [License](#license)

---

## 📖 Overview

The **spotify_ETL_pipeline** automates the extraction, validation, transformation, and loading of Spotify listening data into an analytics-ready format.

### ✨ Key Features  
- 🐙 **Data Extraction:** Pulls recent playback history from Spotify and materializes it into clean DataFrames.  
- 🔍 **Data Validation:** Detects duplicates, missing values, and schema mismatches for high-quality data.  
- 🌀 **Data Transformation:** Aggregates and organizes track data for reliable downstream analytics.  
- 💾 **Data Loading:** Stores curated data into a structured SQLite database.  
- 🌐 **Seamless Integration:** Uses proven Python libraries for API calls, validation, and storage.

---

## 🧩 Tech Stack & Languages

**Primary:** Python (100%)

### **Core Libraries**
<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white">
  <img alt="Pandas" src="https://img.shields.io/badge/pandas-DataFrames-150458?logo=pandas&logoColor=white">
  <img alt="SQLAlchemy" src="https://img.shields.io/badge/SQLAlchemy-ORM-d71f00">
  <img alt="SQLite" src="https://img.shields.io/badge/SQLite-DB-003B57?logo=sqlite&logoColor=white">
  <img alt="Requests" src="https://img.shields.io/badge/requests-HTTP-000000">
  <img alt="Black" src="https://img.shields.io/badge/Code%20Style-Black-000000">
</p>

---

## 🚀 Getting Started

### ✅ Prerequisites
- Python 3.x  
- Pip  
- (Optional) Virtual environment (venv / conda / uv)

---

## 🛠 Installation

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/musaibs/spotify_ETL_pipeline
2️⃣ Navigate to the project directory
cd spotify_ETL_pipeline

3️⃣ Install dependencies
pip install -r requirements.txt

📦 Usage
# Example: Run ETL pipeline
python etl/run.py --since "2023-07-01" --db sqlite:///spotify.db


(Replace with actual instructions once ready.)

🧪 Testing
pytest -q
