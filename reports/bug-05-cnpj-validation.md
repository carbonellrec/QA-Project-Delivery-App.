# Bug Report: Lack of CNPJ Format and Authenticity Validation

## 📄 Description
The system accepts any 14-digit sequence as a CNPJ without validating its existence in the Federal Revenue (Receita Federal) database.

## ✅ Expected Behavior
The system must validate the CNPJ format and check its uniqueness and status via API/Federal Revenue portal.

## ❌ Actual Result
The system only checks for a 14-digit length, allowing non-existent or fake CNPJs to be registered.

## 🔁 Steps to Reproduce
1. Log in as **Admin** > **Registration** > **Client**.
2. Enter a random 14-digit number in the CNPJ field.
3. Observe that the registration is accepted.

## 🔥 Severity
🔴 **Critical**
