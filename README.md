# 🛡️ FraudShield – Advanced Fraud Detection Platform

[![Live Preview](https://img.shields.io/badge/Live%20Site-Visit--Now-0aa1ff?style=for-the-badge&logo=vercel&logoColor=white)](https://finshield.vercel.app/)

FraudShield is an intelligent financial fraud detection system designed to identify suspicious transaction patterns in real-time. Leveraging powerful machine learning models like **XGBoost** and integrating advanced features such as **bulk upload**, **manual entry**, and **LLM-based insights**, the system aims to protect financial institutions and users from malicious activity.

---

## 🚀 Overview

FraudShield analyzes transactions using a variety of behavioral, temporal, and geographic indicators. It’s built with a modern full-stack architecture to ensure scalability, performance, and a smooth user experience.

This project was built as a collaborative effort during a hackathon by:

- [Krrish Gangajaliya](https://github.com/Krish043)
- [Urmil Gadhiya](https://github.com/urmilgadhiya18)
- [Meet Goti](https://github.com/meetgoti07/)
- [Manav Kakkad](https://github.com/Manav2905)

---

## ⚙️ Key Features

- **XGBoost-based Fraud Detection:** Predicts fraudulent transactions based on a trained ML model.
- **Bulk Upload:** Supports .csv and .xlsx files for mass transaction data input.
- **Manual Entry:** Allows single transaction submission via a user-friendly form.
- **Real-time Anomaly Detection:**
  - Large transactions outside user’s historical range.
  - Same card usage across multiple countries within minutes.
  - High-frequency transaction detection (e.g., 10+ within 2–5 mins).
  - Dormant account activity.
  - Repeated failed login or transaction attempts.
- **LLM-Powered Explanations:** Uses Large Language Models to explain why a transaction was flagged.
- **Dashboard UI:** Clean and responsive frontend with detailed alerts and insights.

---

## 🛠 Tech Stack

| Layer        | Technology                   |
|--------------|-------------------------------|
| **Frontend** | Next.js, TypeScript, Tailwind CSS |
| **Backend**  | FastAPI (Python), XGBoost, LLM integration |
| **Database** | PostgreSQL with Prisma ORM    |
| **Other**    | Excel Parsing, AI-based Fraud Scoring |

---

## Installation

Run Finshield With pnpm

```bash
  npm install -g pnpm
  pnpm install
  pnpm dev
```

Ensure your .env files are configured for both frontend (Next.js) and backend (FastAPI + Prisma + PostgreSQL).

## 📌 Future Scope
---
- Add role-based access and OTP/email verification
- Use real-time socket alerts for fraud flags
- Integrate with real banking APIs for live data
- Full training pipeline for model improvement via feedback loop

## 👨‍💻 Built With ❤️ by

- Krrish Gangajaliya
- Urmil Gadhiya 
- Meet Goti 
- Manav Kakkad
- 
⭐ Like this project?
If you found this useful, drop a ⭐ on the repo and share it with your peers!
