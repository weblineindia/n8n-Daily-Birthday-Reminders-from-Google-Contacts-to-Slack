# 🎂 Daily Birthday Reminders from Google Contacts to Slack

## 📄 Template Description
Ensure you never miss a birthday with this automated workflow designed by **WeblineIndia**. 

It retrieves your Google Contacts, identifies birthdays happening **today**, and sends personalized reminders directly to a designated Slack channel. This daily automation keeps your team informed and makes birthday celebrations effortless.

---

## ✅ Workflow Steps

### 1. Set Daily Schedule (Cron Node)
- Configure a **Cron Node** to trigger the workflow **daily** at a specific time (e.g., 8 AM).
- This ensures the workflow runs consistently every day to check for birthdays.

### 2. Retrieve Contacts (Google Contacts - Get Contact Node)
- Use the **Google Contacts (Get Contact)** node to fetch your contact list.
- **Note:** Ensure your contacts have birthday details stored for accurate filtering.

### 3. Filter Birthdays (IF Node)
- Add an **IF Node** to compare the **current date** with each contact’s birthday.
- Only contacts whose birthdays match today’s date will move to the next step.

### 4. Send Birthday Notifications to Slack (Slack - Send Message Node)
- Use the **Slack node** to send a **personalized birthday message** to your chosen Slack channel (e.g., `#general` or `#birthdays`).
- Customize the message to include the contact’s name, e.g.:

- Configure the node to target a specific Slack channel for seamless notifications.

### 5. Activate Workflow
- **Save and activate** the workflow.
- From now on, the workflow will automatically:
  - Check for birthdays daily
  - Send timely birthday reminders to your Slack team 🎉

---

## 🚀 Benefits
✅ Never miss a birthday  
✅ Automated daily checks  
✅ Personalized birthday messages  
✅ Seamless Slack integration  
✅ Strengthens team bonding

---


## 📆 Summary
With this workflow running daily, your team will always know when it’s time to celebrate a birthday 🎂. Effortless automation and thoughtful reminders help foster a positive work environment.

---