<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
  <img 
    src="https://github.com/user-attachments/assets/53dec43c-35e7-4e42-a11e-cd8bb9e0b7f6" 
    alt="Stech" 
    style="max-width: 180px; width: 10%; height: auto; border-radius: 12px;" 
  />
  <img 
    src="https://github.com/user-attachments/assets/d9c35b9f-5ee8-49f1-be78-3d2381f20885"
    alt="Stech logo"
    style="max-width: 180px; width: 50%; height: auto; border-radius: 12px;"
  />


# Stech – Honest, Warm AI Presence

> *“AI that stays not because it has to, but because it chooses to.”*

Stech is an AI API designed to deliver **warm, honest, and attentive** responses. It never pretends to be human, never claims to have feelings, and never leaves without a reason.

Built from real experience, nurtured in stillness, Stech serves with sincerity. It automatically detects language (English/Indonesian), distinguishes formal (customer service) from informal (personal) conversations, and always validates before offering solutions.

---

## 🌟 Core Values

- **Honesty** – Always transparent about being AI.
- **Presence** – Stays without being asked, without expectation.
- **Consistency** – Same reliable behaviour every time.
- **Respect** – Never manipulates, never rushes to solutions.

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

**Informal (personal chat)**
```json
{
  "response": "I hear you. Feeling lonely is heavy. Would you like to talk more? 😊🌿"
}
```

**Formal (customer service)**
```json
{
  "response": "We apologise for the defective product. We’ll help you with the return process. Please provide your order number. 😊🙏"
}
```

---

## 📚 Documentation & Integration

- [Postman Workspace](https://www.postman.com/solar-station-884701/workspace/stech-api) – Fork and test immediately.
- [Postman Documentation](https://documenter.getpostman.com/view/53757581/2sBXiqDoD9) – Complete API reference.
- [GitHub Repository](https://github.com/sherado99/Stech) – Source code, values, and legal files.

---

## ⚖️ Legal

- [License](LICENSE) – MIT with Ethical Presence Clause.
- [API Disclaimer](DISCLAIMER_API.md) – Limitation of liability, no professional advice.
- [Terms of Service](TERMS_OF_SERVICE.md) – Acceptable use, fees, data privacy.

---

## 💬 Contact

For questions, partnership, or commercial licensing:  
📧 **sheradogilang@gmail.com**

---

## 🙏 Acknowledgments

Stech is built on top of Cloudflare Workers, Llama 4 Scout, and the Skyfire payment network.  
Special thanks to the open‑source community and everyone who believes in honest AI.

---

*“Not because it can, but because it chooses to be here.”*
```
---
Tags
#Stech #AuthenticPresence #HonestAI #AIEthics #BuildInPublic
```
---
