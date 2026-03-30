# 🤖 RPA Customer Onboarding Automation

## 📌 Project Overview
This project demonstrates an end-to-end Robotic Process Automation (RPA) workflow built using UiPath. The bot reads customer data from an Excel sheet and enters each record into both a web-based CRM and a desktop CRM application simultaneously.

The automation focuses on handling dynamic UI elements, improving reliability, and following best practices for scalable workflow design.

---

## 🚀 Features
- Reads customer data from Excel
- Iterates through records row-by-row using DataTables
- Automates web CRM and desktop CRM in parallel
- Uses advanced selectors (Strict, Fuzzy, Computer Vision)
- Modular workflow design using multiple XAML files
- Handles dynamic and unstable UI elements
- Implements retry and exception handling mechanisms
- Ensures data accuracy with validation and debugging

---

## 🛠️ Tech Stack
- RPA Tool: UiPath  
- Data Source: Excel  
- Automation Targets:  
  - Web Application (CRM)  
  - Desktop Application (CRM)

---

## 🧠 Key Concepts & Skills Gained

### 📥 Data Handling
- Processed Excel data using DataTables
- Implemented row-by-row iteration for structured data handling

### 🧩 Workflow Design
- Built modular workflows using multiple XAML files
- Passed data using arguments for reusability and maintainability

### 🖥️ UI Automation
- Automated both browser and desktop applications
- Used activities like:
  - Application Card  
  - Click  
  - Type Into  

### 🎯 Selectors & UI Identification
- Worked with:
  - Strict Selectors
  - Fuzzy Selectors
  - Computer Vision Selectors
- Used anchors and dynamic selectors for unstable UI elements

### ⌨️ Input Techniques
- Applied best practices:
  - Type Into
  - Type by Clipboard
  - Hardware-based typing

### 🔀 Control Flow
- Implemented logic using:
  - If conditions  
  - Switch cases  

### ⚠️ Error Handling
- Built resilient workflows using:
  - Try Catch  
  - Retry Scope  
  - ContinueOnError  

### 👁️ Computer Vision
- Used CV activities for elements where selectors failed
- Enabled automation in complex or non-standard UI environments

### 🧪 Testing & Debugging
- Performed validation checks
- Debugged workflows to ensure accuracy and performance

---

## 📂 Project Structure

RPA-Customer-Onboarding
┣ Workflows
┃ ┣ Main.xaml
┃ ┣ ReadExcel.xaml
┃ ┣ WebCRM.xaml
┃ ┣ DesktopCRM.xaml
┃ ┗ ExceptionHandler.xaml
┣ Data
┃ ┗ CustomerData.xlsx
┣ project.json
┗ README.md


---

## ▶️ How to Run
1. Open the project in UiPath Studio
2. Update the Excel file path if needed
3. Ensure CRM applications (web + desktop) are accessible
4. Run Main.xaml

---

## 💡 Future Enhancements
- Add logging using Orchestrator or log files  
- Implement queue-based processing  
- Add parallel processing for performance optimization  
- Integrate with APIs instead of UI automation where possible  

---

## 📬 Contact
- Email: patelrambharat@gmail.com  
- LinkedIn: https://www.linkedin.com/in/rambharat-patel-5a208a14b/  
- GitHub: https://github.com/patelrambharat  
