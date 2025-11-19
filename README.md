📱 QR-to-Lead – Salesforce Mobile Lead Capture App

QR-to-Lead is a mobile-friendly Salesforce application I built to simplify capturing Lead information from QR codes at events, conferences, and business meetups.
The app scans QR codes containing vCard data, parses the content, and automatically creates a Lead record inside Salesforce. It is designed to run directly in the Salesforce Mobile App using Lightning Web Components (LWC) and Apex.

🚀 Features
🔍 QR Code Scanning

Uses the Salesforce Mobile Barcode Scanner API

Reads and processes QR codes containing vCard contact data

🧩 Automatic Lead Creation

Parses vCard fields such as name, phone, email, company, etc.

Creates a Lead record instantly after scanning

Displays a success message and parsed details in-app

📱 Mobile-Optimized UI

Built entirely with Lightning Web Components

Customized mobile record pages

Clean, simple user flow for scanning → preview → lead creation

🔐 Access Control

Includes a dedicated Profile & Permission Set

Ensures users only interact with Lead-related functionality

📊 Reporting

Includes a custom Lead Report to export event leads

🎯 Why I Built This Project

I created this project to gain hands-on experience with:

Lightning Web Components (LWC)

Salesforce Mobile development

Apex backend logic

Parsing vCard data

Working with custom metadata

Deploying a full Salesforce app using GitHub

This project helped me understand how real event lead-capture workflows function and how CRM engineering teams build tools for sales teams.

🧰 Tech Stack

Salesforce Lightning Web Components (LWC)

Apex Classes (parsing + Lead creation)

Salesforce Mobile Barcode Scanner API

Custom Metadata Types

Permission Sets & Profiles

Salesforce Lightning App Builder

📦 Setup & Installation
1️⃣ Prepare a Salesforce Developer Org

Sign up or use an existing org:
➡️ https://developer.salesforce.com/signup
