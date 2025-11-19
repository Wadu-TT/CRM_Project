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
2️⃣ Deploy the Project

You can deploy the metadata to your org using the GitHub Salesforce Deploy Tool:

Open the deploy tool.

Enter your GitHub project details (Owner / Repo / Branch).

Log in to Salesforce when prompted.

Review metadata → Click Deploy.

Wait for deployment to complete.

3️⃣ Create / Assign a User

Assign the included QR-to-Lead User profile
OR

Assign the included permission set to an existing user

4️⃣ Install & Open Salesforce Mobile App

Download on iOS / Android

Log in with the user assigned above

The QR-to-Lead app will appear automatically

📲 How to Use the App

Open the QR-to-Lead app inside Salesforce Mobile

Tap the Scan icon in the bottom navigation bar

Press Scan QR Code

Point the camera at a QR code containing vCard info

The app will:

Scan automatically

Parse the vCard

Create a new Lead

Show a success message

Go to the Leads tab to view/edit your newly created leads

Sample QR Codes

(You can insert your images here if needed.)

🛠 Customization Options
✏️ Text & Message Updates

All user-facing strings are stored in Custom Labels

Setup → Custom Labels

Update values

Refresh Mobile App

🎨 App Branding

Setup → App Manager

Edit QR-to-Lead

Update app name, color, and icon

🗂 Scan Tab Label

Setup → Tabs

Edit Lightning Component Tab

Update label + icon

📖 Technical References

Lead Object API
https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_objects_lead.htm
Summary

QR-to-Lead is a fully functional Salesforce Mobile application I built that demonstrates:

LWC development

Apex backend workflows

QR scanning on mobile

Automated lead creation

Metadata packaging

Real-world CRM engineering concepts

This project represents my ability to build complete Salesforce solutions from UI → backend → deployment.
