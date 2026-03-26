# Flipkart Product Scraper API

## 📌 Overview

This project is a **Flask-based API** that scrapes product details from Flipkart using **Selenium** and **BeautifulSoup**.
It allows users to send a product name via a POST request and receive structured product data including **name, price, and image URL**.

---

## 🚀 Features

* 🔍 Search products dynamically on Flipkart
* 🌐 Automated browsing using Selenium WebDriver
* 🧹 HTML parsing with BeautifulSoup
* 📦 Returns JSON response with product details
* 💾 Saves scraped data into `data.json`

---

## 🛠️ Tech Stack

* Python
* Flask
* Selenium
* BeautifulSoup (bs4)
* Chrome WebDriver

---

## 📂 Project Structure

```
├── app.py           # Main Flask application
├── data.json        # Output file storing scraped data
├── README.md        # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd <project-folder>
```

### 2. Install dependencies

```bash
pip install flask selenium beautifulsoup4
```

### 3. Download ChromeDriver

* Download ChromeDriver matching your Chrome version
* Add it to your system PATH
