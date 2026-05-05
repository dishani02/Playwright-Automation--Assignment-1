<<<<<<< HEAD
# Playwright-testing-suite-Assignment-1
=======
# IT3040 Assignment 1 – Singlish Transliteration Testing (Playwright Automation)

>>>>>>> dba22e0 (Initial commit - Playwright automation project)
---

## 📌 Project Overview

This project is developed for **IT3040 – IT Project Management (Year 3, Semester 2)**.

It automates the testing of a **Singlish-to-Sinhala transliteration system** using Playwright and Python.  
The framework reads test cases from Excel, performs UI automation on the translator web application, captures outputs, compares results, and writes back test status.

🔗 Tested Application:  
https://www.pixelssuite.com/chat-translator

---

## 🎯 Objectives

- Evaluate accuracy of Singlish → Sinhala transliteration
- Detect incorrect or failed translations
- Automate UI testing using Playwright (Python)
- Store test results in Excel
- Analyze system behavior under different inputs

---

## 🛠 Technologies Used

- Python  
- Playwright  
- OpenPyXL  
- Excel (Test Data Source)  

---

## 📂 Project Structure

```

IT23367258/
│
├── test_automation.py
├── IT23367258_Assignment1_TestCases.xlsx
├── IT23367258_GitRepoLink.txt
├── IT23367258_requirements.txt
├── README.md

````

---

## ⚙️ Prerequisites

Before running the project, ensure you have:

- Python 3.8 or above
- pip installed
- Stable internet connection

---

## 📥 Installation Steps

### 1. Open project folder
Extract the ZIP file and open terminal inside the project folder.

### 2. Install dependencies
```bash
pip install -r requirements.txt
````

### 3. Install Playwright browser

```bash
python -m playwright install chromium
```

---

## ▶️ How to Run the Automation

Run the script using:

```bash
python test_automation.py --excel "IT23367258_Assignment1_TestCases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```

---

## 📊 Output Results

The Excel file will be updated automatically with:

* Actual Output (Generated Sinhala Text)
* Status:

  * PASS
  * FAIL
  * UI ERROR
  * COLLECTED

---

## 🧪 Test Coverage

### ✔ Functional Testing

* Sentences and questions
* Commands and responses
* Greetings and conversations
* Mixed Singlish + English input
* Numbers, dates, and currency
* Emojis and symbols

### ✔ Negative Testing

* Typing mistakes
* Spacing errors
* Slang and informal input
* Mixed or invalid formats

### ✔ UI Testing

* Real-time translation updates
* Output rendering accuracy
* UI response timing validation

---

## ⚠️ Important Notes

* Strict comparison is used → small differences may result in FAIL
* Some failures are expected due to:

  * Transliteration limitations
  * Informal Singlish variations
  * UI response delay

---

## ❗ Troubleshooting

### Install issues

```bash
pip install -r requirements.txt --force-reinstall
```

### Playwright issues

```bash
python -m playwright install --force chromium
```

### Common fixes

* No output → increase `--wait-ms`
* UI delay → increase `--slow-mo-ms`

---

## 📦 Submission Instructions

### Step 1: Rename folder

```
IT23367258/
```

### Step 2: Ensure files included

* test_automation.py
* Excel test case file
* requirements.txt
* Git repo link file
* README.md

### Step 3: Create ZIP file

```
IT23367258.zip
```

### Step 4: Upload to CourseWeb

---

## 👨‍🎓 Student Information

* Student ID: IT23367258
* Module: IT3040 – IT Project Management
* Assignment: Assignment 1 (Singlish Transliteration Testing)

---

## 📜 License

This project is developed for **academic purposes only**.

```
