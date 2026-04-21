# Bug Report: Admin Not Notified of Registered Losses

## 📄 Description
When a promoter records a product as "Loss" during a visit, the system fails to send the automatic notification to the Administrator and does not display the loss report in the dashboard.

## ✅ Expected Behavior
Upon saving a checklist with "Loss" items, the system must:
1. Notify the Administrator immediately.
2. Display the data in a "Loss Review Table" (Product, Batch, Quantity, Expiry, Price).

## ❌ Actual Result
The visit is saved, but no alert is issued, and there is no record/history of the loss available for the Admin to review.

## 🔁 Steps to Reproduce
1. Log in as **Promoter**.
2. Start a **Visit** > **Checklist**.
3. Scan a product and mark it as **Loss (Perda)**.
4. Save the checklist and check for Admin notifications/reports.

## 🔥 Severity
🔴 **High** (Financial impact and lack of inventory control)
