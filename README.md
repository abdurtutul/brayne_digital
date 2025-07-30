# 🧪 brayne_digital – SQA Manual Testing Report

This repository documents the manual testing efforts for the **brayne_digital** project. As an **SQA Engineer** at **Softvence Agency**, I conducted functional, UI/UX, and integration testing across mobile and web platforms based on Figma designs, APK builds, and client requirements.

---

## 📌 Project Overview

**Project Name**: brayne_digital  
**Role**: SQA Engineer  
**Workplace**: Softvence Agency  
**Platform**: Mobile App (Customer & Merchant), Web Portal (Advertiser & Admin)  
**Testing Type**: Manual – Functional, UI/UX, Integration

### 🎯 Project Goal

To enhance customer engagement, drive business growth, and create a win-win ecosystem by streamlining the discount redemption process and improving overall usability and business visibility.

---

## 🧭 Key Modules Tested

### 1. 👤 Customers App
- User Registration & Subscription
- Browse Merchant Discounts
- QR Code Generation
- Transaction History
- Profile & Subscription Management
- Push Notifications

### 2. 🏪 Merchants App
- Merchant Registration & Login
- Discount Setup
- QR Code Scanner
- Transaction Log
- Dashboard & Reports
- Push Notifications

### 3. 📢 Advertisers Portal
- Ad Setup & Management
- Categories & Filters
- Performance Tracking
- Payment & Subscription Plans

### 4. 🛠️ Admin Dashboard
- User Management
- Merchant Management
- Advertisement Management
- Analytics & Reports
- Payment Processing
- System Settings & Notifications

---

## 📱 APK File

📦 [Download APK Build](apk/brayne_digital_v1.apk)

---

## 📋 Bug Log & Google Sheet

🧾 [Bug & Test Case Log (Google Sheet)](https://docs.google.com/spreadsheets/d/1gT91kk-IStKj3tsPPcp1vSAUJd9k8RVdmOv-diOwgtQ/edit?usp=sharing)

---

## 🐞 Sample Bug Log Format

| Bug ID | Module | Feature | Bug Type (Flutter/UI/Backend) | Bug Title | Bug Description | Steps to Reproduce | Actual Result | Expected Result | Issue Labels | Severity | Attachment | Dev Status | Testers | Remark | Re-testing | Date |
|--------|--------|---------|-------------------------------|-----------|------------------|---------------------|----------------|------------------|---------------|----------|-------------|-------------|---------|--------|-------------|------|
| #001   | Login  | OTP     | Flutter                       | OTP Crash | App crashes on wrong OTP input | 1. Go to login screen<br>2. Enter invalid OTP<br>3. Tap Continue | App crashes | Error message should appear | Crash, Bug | High | Screenshot.png | Fixed | Tutul | Confirmed | ✅ | 2025-07-25 |
| #002   | Profile | Edit Info | UI                          | Misaligned Text | Text overlaps with button | Navigate to Profile > Edit | Text and button overlap | Proper alignment | UI | Medium | - | In Progress | Tutul | UI issue | ❌ | 2025-07-26 |

> 🔍 *You can find the full list in the [Bug Report Sheet](https://docs.google.com/spreadsheets/d/14C6RpQTsvguC7ouuWNqBF4ZKVkqx8qP1-EV4dquON2c/edit?gid=359680536).*

---

## 📐 UI Interface Preview

You can interact with the latest design prototype below:

[![Figma Preview – brayne_digital](assets/figma_preview_thumbnail.png)](https://www.figma.com/proto/Nmujo7GcxmtjaZG3W8Ezu5/brayne_digital-%7C%7C-Web_genius-%7C%7C--FO313D439DBC3?node-id=1372-1332&p=f&t=Or22jUhZvvRPvYeR-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1)

🔗 [Click here to open the Figma prototype in full screen](https://www.figma.com/proto/Nmujo7GcxmtjaZG3W8Ezu5/brayne_digital-%7C%7C-Web_genius-%7C%7C--FO313D439DBC3?node-id=1372-1332&p=f&t=Or22jUhZvvRPvYeR-1&scaling=scale-down&content-scaling=fixed&page-id=0%3A1)

---

## 🖼️ Screenshots – Mobile App (Scrollable)

<div style="display: flex; overflow-x: auto; gap: 10px;">
  <img src="screenshots/screen1.png" width="200"/>
  <img src="screenshots/screen2.png" width="200"/>
  <img src="screenshots/screen3.png" width="200"/>
  <img src="screenshots/screen4.png" width="200"/>
</div>

> 📌 Place screenshots in a `screenshots/` folder inside your repo.

---

## 🛠️ Tools Used

- ✅ **Figma** – UI/UX Reference
- ✅ **Android APK** – Functional Testing
- ✅ **Google Sheets** – Bug Tracking & Test Logging
- ✅ **GitHub** – QA Documentation Repository

---

## 🙋‍♀️ About Me

**MST Khushi Akter**  
*SQA Engineer @ Softvence Agency*  
🔍 Focused on manual testing, bug reporting, UI/UX evaluation, and ensuring high-quality delivery.

---
