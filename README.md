# Astrofact


# Google Sheets Form Submission with HTML, JavaScript & Apps Script

## 📌 Overview
This project lets you collect form submissions from a website and automatically save them into a **Google Sheet** along with the **exact date and time** the form was submitted.

It uses:
- **HTML + Tailwind CSS** → Modern, responsive form UI
- **JavaScript (Fetch API)** → Sends form data securely to Google Apps Script
- **Google Apps Script** → Receives and stores data into Google Sheets

---

## 🚀 How It Works
1. The user fills out the form on your web page.
2. JavaScript validates:
   - **Phone number** must be exactly 10 digits.
   - **Email address** must be valid.
   - All required fields must be filled in.
3. The form sends the data to a **Google Apps Script Web App**.
4. Google Apps Script records:
   - Name  
   - Phone  
   - Email  
   - Address  
   - **Current Date & Time of submission** (timestamp)  
   into your Google Sheet.

---

## ⏳ About the Timestamp
- The script automatically logs the **exact submission time**.
- Helps track when each person submitted their form.
- Example format:
