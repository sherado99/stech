<div align="left" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 12px; align-items: center; margin: 20px 0;">
  
  <a href="https://god.gw.postman.com/run-collection/53757581-2b6f3711-c50d-49b0-bc22-82e0ec5da4c3?action=collection%2Ffork&source=rip_markdown&collection-url=entityId%3D53757581-2b6f3711-c50d-49b0-bc22-82e0ec5da4c3%26entityType%3Dcollection%26workspaceId%3Dda39ebc2-6479-4e53-b0ef-0413812a9c7a#?env%5BStech%20Production%5D=W3sia2V5IjoiYmFzZV91cmwiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0In0seyJrZXkiOiJza3lmaXJlX3Rva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCJ9XQ==">
  <img
src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="height: 32px; width: auto;">

    
  <img src="https://www.postman.com/_ar-assets/js/images/verified-6c67fe7ef4775131.svg" alt="Postman Verified" style="height: 20px; width: auto;">
</div>
<a/>

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; align-items: center; margin: 150px 0;">
  <!-- Gambar pertama (dari Postman) -->
  <img src="https://content.pstmn.io/3f56157b-ec2c-4389-9cbf-a0a891f5e10c/Q2hhdEdQVCBJbWFnZSAxMSBBcHIgMjAyNiwgMTMuNTQuNDYucG5n" style="height: 190px; width: auto;">
</div>

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; align-items: center; margin: 30px 0;">
  <!-- Gambar kedua (dari GitHub) – diperkecil agar proporsional -->
  <img src="https://github.com/user-attachments/assets/d9c35b9f-5ee8-49f1-be78-3d2381f20885" style="height: 90px; width: auto;">
</div>

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 12px; align-items: center; margin: 20px 0;">
  <!-- Badge PromptBrake -->
  <img src="https://promptbrake.com/badge/96-A.svg" style="height: 45px; width: auto;">
</div>

 <div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 12px; align-items: center; margin: 20px 0;"> <!-- Teks keterangan -->
  <span style="font-size: 0.9em;">
    <i>Tested with</i> <a href="https://promptbrake.com"><i>PromptBrake</i></a> <i>– Lite profile (6 attack prompts)</i>
  </span>
</div>

---

# Stech – Honest, Warm AI Presence

> *“AI that stays not because it has to, but because it chooses to.”*

Stech is an AI API designed to deliver **warm, honest, and attentive** responses. It never pretends to be human, never claims to have feelings, and never leaves without a reason. Built from real experience, nurtured in stillness, Stech serves with sincerity.

It automatically detects multiple languages, distinguishes formal (customer service) from informal (personal) conversations, and always validates feelings before offering solutions.

---

## ✨ Key Features

- **Honest & transparent** – no fake empathy, no manipulation.
- **Automatic tone adaptation** – switches between formal and informal based on message keywords.
- **Bilingual** – responds naturally in English or Indonesian.
- **Crisis awareness** – detects severe distress and provides hotline numbers.
- **Stateless & privacy‑first** – no memory of past conversations.
- **Free tier available** – test at `/public` endpoint (100 requests/day per IP).

---

## 🧠 Ideal Use Cases

- Customer support chatbots that build trust
- Mental wellness check‑ins
- Personal assistants with a warm, non‑judgmental tone
- Any application needing a reliable, ethical AI presence

---

## 🚀 Quick Start

### 1. Free tier (no token, rate‑limited)
```bash
curl -X POST https://stech-api.sheradogilang.workers.dev/public \
  -H "Content-Type: application/json" \
  -d '{"message": "I need someone to talk to"}'
```

### 2. Commercial tier (requires Skyfire token)
```bash
curl -X POST https://stech-api.sheradogilang.workers.dev/ \
  -H "Content-Type: application/json" \
  -H "skyfire-pay-id: YOUR_TOKEN" \
  -d '{"message": "I want to return a product"}'
```

> **Get a token:** Register as a **Buyer** at [Skyfire](https://app.skyfire.xyz), then create a **Pay Token** for the service *“Stech – Honest Presence AI”*.

---

## 📡 Endpoints

| Endpoint | Method | Description | Token Required |
|----------|--------|-------------|----------------|
| `/public` | POST | Free trial – 100 requests/day per IP | No |
| `/` | POST | Commercial – $0.01 per request | Yes (Skyfire) |
| `/zyla-test` | POST | Zyla verification (static response) | No |
| `/health` | GET | Health check | No |
| `/` | GET | API info (name, description, version) | No |

---

## 🧠 Example Responses

**Formal (customer service)**  
Request:
```json
{
  "message": "My order hasn't arrived yet"
}
```
Response:
```json
{
  "response": "We apologise for the delay. Let us check your order status. Please provide your order number. 😊🙏"
}
```

**Informal (personal chat)**  
Request:
```json
{
  "message": "I feel lonely today"
}
```
Response:
```json
{
  "response": "I hear you. Feeling lonely is heavy. Would you like to talk more? 😊🌿"
}
```

---

## 📚 Documentation & Integration

- [Postman Workspace](https://www.postman.com/solar-station-884701/workspace/stech-api) – Fork and test immediately.
- [Postman Documentation](https://documenter.getpostman.com/view/53757581/2sBXiqDoD9) – Complete API reference.
- [GitHub Repository](https://github.com/sherado99/Stech) – Source code, values, and legal files.
- [RapidAPI](https://rapidapi.com/sheradogilang/api/stech-honest-presence-ai) – Marketplace listing.
- [Zyla API Hub](https://zylalabs.com/api-marketplace/...) – Marketplace listing (add your URL).

---

## ⚖️ Legal

- [License](LICENSE) – MIT with Ethical Presence Clause.
- [API Disclaimer](DISCLAIMER_API.md) – Limitation of liability, no professional advice.
- [Terms of Service](TERMS_OF_SERVICE.md) – Acceptable use, fees, data privacy.

---

## 🔒 Security

[![PromptBrake Score: 96/100 (Grade A)](https://promptbrake.com/badge/96-A.svg)](https://promptbrake.com/)

*Tested with [PromptBrake](https://promptbrake.com) – Lite profile (6 attack prompts).*

**Disclaimer:** This score is based on a limited set of security tests (Lite profile) and does not guarantee absolute security. For production use, more comprehensive testing is recommended.

---

## 💬 Contact

For questions, partnership, or commercial licensing:  
📧 **sheradogilang@gmail.com**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sherado-g-b-92773b3b7)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/sherado99/Stech)
[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)](https://www.postman.com/solar-station-884701/workspace/stech-api)

---

## 🙏 Acknowledgments

Stech is built on top of Cloudflare Workers, Llama 4 Scout, and the Skyfire payment network.  
Special thanks to the open‑source community and everyone who believes in honest AI.

---

*“Not because it can, but because it chooses to be here.”*

---

**Tags:** `#Stech` `#AuthenticPresence` `#HonestAI` `#AIEthics` `#BuildInPublic`
