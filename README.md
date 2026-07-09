# 🤖 AI Appointment Booking System

An AI-powered Appointment Booking Automation built using **n8n**, **Google Calendar**, **Gmail**, **JavaScript**, and **Webhook Automation**.

This workflow automatically displays available appointment slots, accepts customer bookings through a custom HTML form, creates Google Calendar events, sends confirmation emails, and returns a success page.

---

# 🚀 Features

- 📅 Fetch existing Google Calendar events
- 🧠 Detect available appointment slots
- 🌐 Generate a custom HTML booking form
- 🔗 Webhook-based booking system
- 📌 Automatically create Google Calendar events
- 📧 Send confirmation email to customers
- ✅ Display booking confirmation page
- ⚡ Fully automated using n8n
- 🔄 Auto redirect back to booking page after confirmation

---

# 🛠 Tech Stack

- n8n
- Google Calendar API
- Gmail API
- JavaScript
- HTML
- Webhooks

---

# 📋 Workflow Overview

## Step 1

Webhook receives a request to open the booking page.

↓

## Step 2

Google Calendar retrieves all existing events.

↓

## Step 3

JavaScript processes busy slots and prepares available booking data.

↓

## Step 4

A custom HTML Appointment Booking Form is generated dynamically.

↓

## Step 5

The HTML page is returned to the browser.

↓

## Step 6

Customer fills out the appointment form.

↓

## Step 7

A second Webhook receives the submitted booking details.

↓

## Step 8

JavaScript formats customer information.

↓

## Step 9

Google Calendar creates a new appointment.

↓

## Step 10

Gmail sends a confirmation email to the customer.

↓

## Step 11

A success page is displayed and automatically redirects back to the booking form.

---

# 📧 Customer Information Collected

- Name
- Email
- Selected Time Slot

---

# 🔄 Automation Flow

```
Customer

↓

Webhook

↓

Google Calendar

↓

JavaScript

↓

Dynamic HTML Form

↓

Customer Submission

↓

Webhook

↓

JavaScript

↓

Google Calendar Event

↓

Confirmation Email

↓

Success Page
```

---

# 📸 Workflow Screenshot

<img width="758" height="277" alt="Screenshot 2026-07-09 193628" src="https://github.com/user-attachments/assets/54b2cccd-7e65-4170-9411-94437b4a3562" />


> Add your workflow image here.

Example:

```

# 🎯 Use Cases

- Clinics
- Hospitals
- Real Estate Agencies
- Consultants
- Salons
- Coaches
- Law Firms
- Travel Agencies
- Freelancers
- Small Businesses

---

# 🔮 Future Improvements

- WhatsApp Confirmation
- SMS Notifications
- Zoom Meeting Links
- Stripe Payment Integration
- AI-powered Scheduling Assistant
- Multi-user Calendar Support

---

# 👨‍💻 Author

**Afaq Khan**

AI Agent Engineer | AI Automation Specialist

Building AI Agents, WhatsApp Automation, Business Workflows, and Intelligent Systems.

LinkedIn:
https://linkedin.com/in/afaq-khan-a47674289

GitHub:
https://github.com/AfaqKK
