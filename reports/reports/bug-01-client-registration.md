# Bug Report: Missing Mandatory Fields - Client Registration (RF 3.5)

## 📄 Description
The system allows client registration without requiring "Manager" and "Supervisor" contact information, violating the established Business Rule.

## ✅ Expected Behavior
The registration process should only proceed to the next stage if the mandatory fields (Manager and Supervisor contacts) are filled.

## ❌ Actual Result
Mandatory validation is missing. The system allows saving or proceeding without these contact details.

## 🔁 Steps to Reproduce
1. Log in as **Admin**.
2. Go to **Registration (Cadastros)** > **Insert New Registration**.
3. Select **Clients (+)**.
4. Attempt to save without filling Manager/Supervisor contacts.

## 🔥 Severity
🟢 **Low**
