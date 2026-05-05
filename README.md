
# Playwright-testing-suite-Assignment-1


📌 Project Overview
This repository contains the automation script and test cases for IT3040 – IT Project Management (Year 3, Semester 1).
The project focuses on evaluating the accuracy of a Singlish-to-Sinhala transliteration system by executing structured test cases and identifying conversion failures.
🔗 Tested System: __https://www.pixelssuite.com/chat-translator__
🎯 Objectives

* Evaluate the accuracy of Singlish → Sinhala conversion
* Identify failure scenarios in transliteration
* Automate test execution using Playwright
* Record results directly into an Excel file
* Analyze inconsistencies in real-time UI behavior
🛠 Technologies Used

* Python
* Playwright (Browser Automation)
* OpenPyXL (Excel handling)
📂 Project Structure

```
IT3040_Assignment_1/
│
├── test_automation.py              # Main automation script
├── Assignment1_TestCases.xlsx      # Excel test cases & results
├── requirements.txt                # Python dependencies
├── README.md                      # Project documentation

```

⚙️ Prerequisites
Make sure you have:

* Python 3.8+
* pip (Python package manager)
* Internet connection
📥 Installation
1. Clone Repository

```
git clone <your-repo-link>
cd <your-project-folder>
```

2. Install Dependencies

```
pip install -r requirements.txt
```

3. Install Playwright Browsers

```
playwright install chromium
```

▶️ Running the Automation Script
Use the following command:

```
python test_automation.py --excel "C:\path\to\Assignment1_TestCases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```

📊 Output

* Results are written directly into the Excel file:
   * Actual Output
   * Status (PASS / FAIL / UI Error / COLLECTED)
* Script automatically:
   * Reads test cases
   * Inputs Singlish text
   * Captures Sinhala output
   * Compares results
🧪 Test Coverage
✔ Functional Testing

* Question forms
* Commands and responses
* Greetings and casual phrases
* Mixed Singlish + English inputs
* Numbers, dates, currency
* Emojis and symbols
* Spelling variations
✔ Negative Testing

* Incorrect spacing
* Typographical errors
* Slang inputs
* Mixed language complexity
* Formatting issues
✔ UI Behavior

* Real-time Sinhala output updates
* Input/output synchronization
⚠️ Important Notes

* Strict comparison is used → Even small differences = FAIL
* Some failures are expected due to:
   * Transliteration inconsistencies
   * Informal Singlish variations
   * UI timing delays
* Tests run sequentially to ensure stability
❗ Troubleshooting
Script Issues

* Check Python version:

```
python --version
```

* Reinstall dependencies:

```
pip install -r requirements.txt --force-reinstall
```

Playwright Issues

```
playwright install --force chromium
```

Common Errors

* No output detected → Increase `--wait-ms`
* UI not updating → Increase `--slow-mo-ms`
* Wrong selectors → Website structure may have changed
👨‍🎓 Student Information

* Student ID: IT23367326
* Module: IT3040 – IT Project Management
* Assignment: Assignment 1 (Option 1)
📌 Final Status
✔ Automation script implemented ✔ Excel-based validation completed ✔ 50+ test cases executed ✔ Failure scenarios identified
📜 License
This project is created for academic purposes only.


use this structure and create my readme file for my project dont copy this and use my info
my IT no is IT23367258 i want to reame directly copy and paste gie all in one
