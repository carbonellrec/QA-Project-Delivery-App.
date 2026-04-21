# Bug Report: Empty Routes Generated After System Error

## 📄 Description
If a routing error occurs (e.g., Latitude/Longitude issues), the system fails to create the route for the Admin but generates an empty "Ghost Route" for the Driver.

## ✅ Expected Behavior
If an error occurs during route generation, no route should be created for any user.

## ❌ Actual Result
Multiple empty routes (without orders) are assigned to the driver for every failed attempt by the admin.

## 🔁 Steps to Reproduce
1. Log in as **Admin/Logistics**.
2. Go to **Routing (Roteirização)**.
3. Attempt to create a route that triggers a system error.
4. Log in as the assigned **Driver** and check the route list.

## 🔥 Severity
🟢 **Low**
