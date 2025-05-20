# TA Score Entry Bot

This is a Python automation tool built using Selenium to automate the task of entering weekly assignment scores for students on the Gachon University Cyber Campus system.

## 🎯 Purpose

As a teaching assistant, I had to enter scores for ~70 students every week. To save time and avoid repetitive manual entry, I created this automation script.

## ⚙️ Features

- Logs into the Cyber Campus system using Selenium
- Navigates to the grading section
- Inputs scores for 3 problems per student
- Easily modifiable for different IDs, score values, and page structures

## 🛠 Technologies

- Python 3.x
- Selenium
- Chrome WebDriver (via `webdriver_manager`)

## 🚀 How to Use

1. Install dependencies:
   ```bash
   pip install selenium webdriver-manager

2. Replace your login info:
   driver.find_element(By.XPATH, 'XPATH').send_keys("YOUR_USERNAME")
   driver.find_element(By.XPATH, 'XPATH').send_keys("YOUR_PASSWORD")

3. Run the script:
   python auto_grade.py
