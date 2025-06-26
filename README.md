# 📢 Event Announcement System (AWS SNS, Lambda, API Gateway)

A serverless event announcement platform created using AWS services. Users can subscribe via email to receive automatic notifications when new events are announced.

---

## 🧱 Architecture Overview

![Architecture Diagram](architecture-diagram/architecture.png)

---

## ☁️ AWS Services Used

- **Amazon SNS** – Sends email notifications to subscribers.
- **AWS Lambda** – Handles backend logic for subscribing users and announcing events.
- **Amazon API Gateway** – Exposes secure HTTP endpoints for frontend/API integration.
- **IAM** – Provides secure permission-based access.
- **Amazon S3** *(optional)* – For hosting static content or storing logs.

---

## 🧠 Key Features

- ✅ Subscribe users via their email to an event topic.
- ✅ Send announcements to all subscribers with one API call.
- ✅ Automatically notify users via Amazon SNS.
- ✅ Fully serverless (no EC2, no manual scaling needed).
- ✅ Built with reusable and modular code.

---

## 🗂️ Project Folder Structure