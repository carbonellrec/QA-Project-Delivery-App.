# Bug Report: Failure in Batch (Lote) Field Validation

## 📄 Description
The system accepts empty, repetitive, or incorrectly formatted Batch (Lote) numbers during manual order entry.

## ✅ Expected Behavior
*   Fields must not be empty.
*   No duplicate batch numbers allowed.
*   Format must be 8 digits (DDMMYYYY).
*   System should display: "Invalid format. Use 8 digits (DDMMYYYY)".

## ❌ Actual Result
The system allows empty fields and any numerical input (not following the date format) without validation errors.

## 🔁 Steps to Reproduce
1. Log in as **Admin** > **Orders** > **Manual Entry (+)**.
2. Go to **Order Info** > **Order Products**.
3. Enter an invalid or empty batch number.

## 🔥 Severity
🟡 **Medium**
