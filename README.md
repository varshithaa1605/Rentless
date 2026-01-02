# RentLess Network

RentLess is a high-fidelity web application designed to facilitate peer-to-peer subscription sharing within student communities. The platform provides a secure, verified environment for users to split premium OTT costs, utilizing a custom-built verification and credential delivery system.

## 🚀 Core Functionalities

* **Identity Verification Layer:** A mandatory onboarding flow requiring institutional ID uploads to ensure community trust and accountability.
* **Fintech-Inspired Payment UX:** A structured payment confirmation system including UPI QR generation, UTR (Transaction ID) logging, and proof-of-payment uploads.
* **The Vault (Credential Management):** A secure post-payment environment that provides granular access to account emails, passwords, and profile-specific PINs.
* **Support Architecture:** A dedicated 'Bhai Help Chahiye' portal featuring pre-configured deep links for rapid incident reporting and admin assistance.

## 🛠 Technical Architecture

* **Design System:** Developed using **Tailwind CSS** with a focus on dark-mode glassmorphism and responsive design principles.
* **Session Management:** Utilizes **Browser LocalStorage** for persistent user sessions and transaction state tracking without the need for a heavy backend for the MVP.
* **Typography & Visuals:** Integrated **Plus Jakarta Sans** and **FontAwesome 6.4** for a modern, high-performance interface.

## 📂 System Map

| File | Purpose |
| :--- | :--- |
| `index.html` | Client Landing Page & Onboarding / Verification Engine |
| `dashboard.html` | Subscription Marketplace & Tier Selection |
| `hub.html` | Secure Credential Vault & Profile Management |
| `helpline.html` | Support Center & Admin Communication Hub |
| `admin.html` | Internal Verification Dashboard for Payment Approval |

## 🔒 Security & Compliance

* **Data Privacy:** All uploaded student data is intended for verification purposes only.
* **Access Control:** The system is built to prevent credential leakage through hidden input fields and 'Tap to Reveal' functionality.

---
© 2026 RentLess Network. Developed for the Student Community.
