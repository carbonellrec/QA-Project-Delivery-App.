# Bug Report: 24h Time Format Converted to 12h Format

## 📄 Description
The routing system incorrectly converts the 24-hour time format selected by the admin into a 12-hour (AM/PM) format.

## ✅ Expected Behavior
The time should remain in the 24-hour format as selected during the routing process (e.g., 16:08 should remain 16:08).

## ❌ Actual Result
Selecting 16:08 results in the system displaying 4:08 PM, diverging from the project's standard.

## 🔁 Steps to Reproduce
1. Log in as **Admin**.
2. Go to **Routing (Roteirização)** > **Select Driver**.
3. Set the time using the 24h picker and save.

## 🔥 Severity
🟢 **Low**
