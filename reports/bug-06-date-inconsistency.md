# Bug Report: System Records Incorrect Order Date

## 📄 Description
When registering a manual order, the system records and displays a date prior to the one selected by the user.

## ✅ Expected Behavior
The system must record and display the exact date selected during the order entry process (e.g., if April 4th is selected, it should show April 4th).

## ❌ Actual Result
Selecting a date (e.g., 04/04/2026) results in the system saving the previous day (03/04/2026).

## 🔁 Steps to Reproduce
1. Log in as **Admin**.
2. Go to **Registration (Cadastro)** > **Orders (Pedido)** > **Manual Entry (+)**.
3. Select a specific date and save.
4. Verify the date displayed in the order list.

## 🔥 Severity
🟢 **Low**
