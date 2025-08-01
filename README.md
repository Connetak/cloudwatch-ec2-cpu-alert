#  AWS CloudWatch Alarm Notification Email Project

This project demonstrates how to set up a CloudWatch alarm to monitor an EC2 instance’s CPU utilization and send an email notification when the threshold is breached.

## 📌 Use Case

Monitor high CPU usage on an EC2 instance and get notified immediately to take action — a basic but essential DevOps practice for cloud monitoring and automation.

---

##  Services Used

* **Amazon EC2**
* **Amazon CloudWatch**
* **Amazon SNS (Simple Notification Service)**

---

##  What I Learned

* Creating CloudWatch Alarms
* Setting alarm conditions (CPU > 70%)
* Linking alarms to SNS topics
* Email alert configuration and validation
* Understanding alarm states: OK → ALARM → OK

---

## 📷 Screenshots

###  Alarm triggered

### ✅ Alarm recovered

### 📧 Email Notification

---

##  How It Works

1. An alarm monitors EC2 instance CPU utilization.
2. When it goes beyond 70%, the alarm state changes to `ALARM`.
3. CloudWatch sends a notification via SNS to the verified email.
4. Once CPU usage drops, the alarm returns to `OK`.

---

## 🔗 Connect With Me

🌐 GitHub: [github.com/Connetak](https://github.com/Connetak)



