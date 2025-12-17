# Exploratory & Compatibility Testing – Tokopedia

## 📌 Project Overview

This project contains documentation of **Exploratory Testing** and **Compatibility Testing** conducted on the **Tokopedia** website. The purpose of this testing is to identify functional defects, UI/UX issues, and compatibility problems across a specific user environment. The testing was performed without formal test cases (exploratory approach) and focused on real user experience.

---

## 🧪 Scope of Testing

The testing covered several core features of the Tokopedia website, including:

* Homepage (navigation, banners, categories)
* Search bar and search results
* Product Detail Page
* Add to Cart
* Checkout
* Account & Address Management
* Top Up & Bill Payment

---

## 🔍 Exploratory Testing

### 🎯 Objective

To identify functional defects, UI/UX inconsistencies, and potential usability issues through hands-on exploration without relying on predefined test cases.

### 🧠 Testing Approach

* User flow exploration
* Focus on input validation, data synchronization, and UI behavior
* Structured bug documentation including steps to reproduce, expected result, actual result, severity, and priority

### 🐞 Findings Summary

* Total Bugs Found: **8 Bugs**
* Highest Severity: **Medium**
* Types of Issues Identified:

  * Improper input validation (phone number & e-money fields)
  * Cart item count not updating in real-time
  * Product images and banners not displayed correctly
  * Broken images on category and store pages

---

## 🖥️ Compatibility Testing

### 🎯 Objective

To ensure the Tokopedia website functions consistently and displays correctly across a specific user environment.

### ⚙️ Test Environment

* **Operating System**: Windows 10
* **Browser**: Google Chrome (latest version)
* **Device**: Desktop

### 🔎 Testing Focus

* UI layout consistency
* Behavior of interactive elements
* Loading and rendering of product images, banners, and brand logos

### 📌 Findings Summary

* Some product and brand images failed to load properly
* Banner and product images overlapped on certain pages
* Grey placeholders appeared instead of actual product images

---

## 🛠️ Tools Used

* Google Chrome
* Chrome DevTools
* Inspect Element

---

## 📄 Documentation

All testing activities and results were documented in the following artifacts:

* Exploratory bug reports
* Evidence (screenshots)
* Test Closure Report

---

## 📊 Test Closure Summary

| Testing Type          | Total Issues | Highest Severity | Status                       |
| --------------------- | ------------ | ---------------- | ---------------------------- |
| Exploratory Testing   | 8 Bugs       | Medium           | Closed (Recommended for Fix) |
| Compatibility Testing | UI Issues    | Medium           | Closed                       |

---

## ✅ Conclusion

Overall, the Tokopedia website works well from a functional perspective. However, several issues were identified related to input validation, visual consistency, and UI behavior, which may impact user experience. Improvements in these areas and regression testing after fixes are highly recommended to ensure application stability.

---

## 👤 Author

**Ahmad Farichin**
Quality Assurance Engineer

---

📌 *This project was created as part of a QA Manual portfolio for learning and professional development purposes.*
