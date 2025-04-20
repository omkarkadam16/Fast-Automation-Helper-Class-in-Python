# Fast-Automation-Helper-Class-in-Python
A reusable and efficient helper class to simplify Selenium automation in Python. Includes smart methods for clicking, dropdowns, auto-complete, retry mechanisms, pop-up handling, alert management, and more.
# Selenium Helper for Python Automation

This project provides a powerful, reusable Selenium helper class for simplifying automation tasks using Python + Selenium.

## 🚀 Features

- Click with retry & JS fallback
- Auto-complete dropdown selector
- Frame switching
- Pop-up and alert handling
- Dynamic waits and visibility checks
- Checkbox automation
- Pagination checkbox selection
- Cleaner syntax for test scripts

## 📦 How to Use

```python
from selenium import webdriver
from selenium_helper import SeleniumHelper

driver = webdriver.Chrome()
helper = SeleniumHelper(driver)

helper.normal_click(By.ID, "submitBtn")
helper.send_keys(By.NAME, "username", "admin")
helper.select_dropdown(By.ID, "dropdown", "Option 1")
