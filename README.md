# 📰 NewsScraper & 🎵 NewsToMusic

Two mini–projects combined into one repository — both powered by Python, APIs, and creative automation.

---

## 📌 Overview

This repository contains **two separate tools**:

### **1️⃣ NewsScraper**
A lightweight CLI program that scrapes the latest trending news from **Hacker News** using `BeautifulSoup4`.  
It fetches and displays the most recent and relevant stories directly in your terminal.

### **2️⃣ NewsToMusic**
This program takes **author names** from NewsAPI articles, then searches for them on **Spotify**—returning a matching **song preview URL** for each author.

A fun bridge between **news** and **music discovery**, all automated via APIs.

---

## 🚀 Features

### ✔️ NewsScraper
- Scrapes live news from **Hacker News**
- Shows the latest headlines directly in CLI
- Uses `BeautifulSoup4` + `requests`

### ✔️ NewsToMusic
- Fetches news authors using **NewsAPI**
- Searches Spotify for a track related to the author’s name
- Prints the **author name** + **song preview URL** in console
- Uses **Spotify API**, `requests`, and `user secrets`

---

## 🛠️ Tech Stack

| Component     | Technology Used            |
|--------------|-----------------------------|
| Language      | Python                     |
| Web Scraping  | BeautifulSoup4, requests   |
| APIs          | NewsAPI, Spotify API       |
| Secrets       | python-dotenv / user secrets |

---

## 📂 Project Structure

NewsToMusic.py
newsScraper.py
README.md
requirements.txt
.env (for API keys)


---

## 🔧 Installation & Setup

### **1. Clone the Repository**
```bash
https://github.com/tihamsheikh/News-and-Programming.git
cd News-and-Programming
```

2. Install Dependencies
```
pip install -r requirements.txt
```

4. Add API Keys

  Create a .env file for NewsToMusic:
  
    clientID = your_spotify_client_id
    clientSecret = your_spotify_client_secret
    newsKey = your_news_api_key

▶️ Running Each Program
  - Run NewsScraper
  ```
  python newsScraper.py or py newsScraper.py 
  ```
  - Run NewsToMusic
  ```
  python NewsToMusic.py or py NewsToMusic.py
  ```

🧠 Why This Project?

  This repo explores:

    Web scraping
    
    REST API integration
    
    Data extraction
    
    Music search automation
    
    Practical Python scripting
    
    Perfect for beginners experimenting with APIs and creative automation.

📄 License

  MIT License — free to use and modify.

