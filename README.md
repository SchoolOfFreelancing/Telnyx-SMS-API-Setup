# Telnyx SMS API Setup

Telnyx SMS REST API setup, including A2P 10DLC registration, two-way messaging, bulk SMS integration and testing.

## 📋 Prerequisites

- Telnyx account — [Sign up here](https://telnyx.com)
- API key from Telnyx Mission Control Portal
- A registered phone number (DID) on Telnyx
- Web-based mobile portal and SMS management system
- A Ubuntu Linux server at DigitalOcean, AWS, etc.
- Domain or Sub domain 
- Mobile number to test SMS
- [Required Documents For International](https://support.telnyx.com/en/articles/5469551-international-numbers-required-documents)
- [Local Calling](https://support.telnyx.com/en/articles/6622229-pstn-replacement-local-calling-with-telnyx)

## 📱 A2P 10DLC Registration

Required for sending A2P (Application-to-Person) SMS in the US.

**Steps:**
1. Register your **Brand** in Telnyx Mission Control Portal
2. Create a **Campaign** (use case: marketing, 2FA, alerts, etc.)
3. Link your **phone number** to the campaign
4. Wait for carrier approval (1–5 business days)

⚠️ Unregistered numbers will have SMS filtered or blocked by US carriers.

## ✉️ Send Bulk SMS Local or International
## 🔁 Two-Way Messaging (Webhook)
## 📦 Bulk SMS Integration
## 🔐 Security Best Practices
## ⚙️ Environment Variables

## 📄 License
MIT License
