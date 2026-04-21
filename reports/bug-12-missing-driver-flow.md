# Bug Report: Missing Exchange and Loss Workflow for Drivers

## 📄 Description
The driver application fails to implement **Requirement 3.13**, which should allow drivers to verify and record product exchanges or losses during the delivery process.

## ✅ Expected Behavior
1. If a loss was previously flagged by a promoter, an icon should appear for the driver.
2. The driver clicks the icon to verify products/photos.
3. System presents fields for: *Product Check, Exchange Picked Up, and Return Invoice.*

## ❌ Actual Result
The entire requirement is missing from the driver's interface. There is no icon or workflow for handling exchanges during delivery.

## 🔁 Steps to Reproduce
1. Log in as **Driver**.
2. Open **Routes (Roteirização)**.
3. Select a **Client** known to have pending exchanges.
4. Observe the lack of "Exchange" or "Loss" icons/options.

## 🔥 Severity
🟢 **Low** (Feature Request / Missing Implementation)
