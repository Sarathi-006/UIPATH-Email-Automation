# UiPath – Gmail Email Automation (Send Emails via SMTP)

This repository contains a **UiPath automation workflow** that demonstrates how to:  
- **Send emails automatically** using Gmail SMTP  
- **Attach files to emails**  
- **Send customized messages**  
- **Handle errors gracefully**  

---

## Step 1: Set Up Gmail
1. Go to your [Google Account Security](https://myaccount.google.com/security).  
2. Enable **2-Step Verification** if it’s off.  
3. Generate an **App Password** for Mail (use this instead of your normal Gmail password in UiPath).  

---

## Step 2: Open UiPath Studio
1. Create a **New Process** → Name it `GmailSMTPAutomation`.  

---

## Step 3: Use Send SMTP Mail Message
1. Drag **Send SMTP Mail Message** activity (from **Activities → Mail**).  
2. Configure the following **properties**:

| Property           | Value |
|-------------------|-------|
| Port              | 587   |
| Server            | smtp.gmail.com |
| Email             | Your Gmail (e.g., yourname@gmail.com) |
| Password          | App Password (not your normal Gmail password) |
| SecureConnection  | Auto  |
| To                | Recipient email |
| Subject           | "Test Email from UiPath" |
| Body              | "Hello! This is automated email." |
| Attachments       | Optional: `C:\Users\Bala\Documents\file.pdf` |

---

## OUTPUT
![Uploading Screenshot 2025-11-17 214321.png…]()




