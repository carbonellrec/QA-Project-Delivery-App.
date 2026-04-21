# Bug Report: Missing Validation for Expired Products

## 📄 Description
The system accepts any date in the expiration field (including "09/09/9999") and fails to trigger alerts for expired products or items nearing their expiration date.

## ✅ Expected Behavior
1. **Expired:** If a date is in the past, show: "Product Expired! Please check batch and date."
2. **Near Expiration:** If the product is 5 days or less from expiring, show: "Product near expiration! Remove from sales area. Save as loss?"

## ❌ Actual Result
The system accepts any input and does not analyze the date, allowing expired products to remain in the active system without alerts.

## 🔁 Steps to Reproduce
1. Log in as **Promoter**.
2. Go to **Visit** > **Checklist**.
3. Enter an expired date (e.g., yesterday) or a future invalid date (09/09/9999).

## 🔥 Severity
🔴 **High / Critical** (Health and Compliance Risk)
