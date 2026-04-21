# Bug Report: Order Creation Without Mandatory Invoice (NF)

## 📄 Description
Although the "Invoice" (Nota Fiscal) field is marked as mandatory, the system allows orders to be generated without this information.

## ✅ Expected Behavior
The system must validate if all mandatory fields, including the Invoice (NF), are filled before generating an order.

## ❌ Actual Result
Orders are successfully created even when the Invoice field is left blank.

## 🔁 Steps to Reproduce
1. Log in as **Admin**.
2. Go to **Orders (Pedido)** > **Manual Entry (+)**.
3. Leave the Invoice (NF) field empty and attempt to complete the order.

## 🔥 Severity
🟡 **Medium**
