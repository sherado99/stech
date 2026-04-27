<div align="center">
  <img width="200" alt="Stech" src="https://github.com/user-attachments/assets/80c2b9b9-4b7b-4d5a-a906-87e94209d66b" />
</div>

#

<div align="center">
  <img width="500" alt="ChatGPT Image 15 Apr 2026, 04 53 18" src="https://github.com/user-attachments/assets/e55bb1c0-3078-4577-9052-a6cf69928d4c" />
</div>
<div align="center">

# “Stech - Honest, Warm AI Presence”
### **Not because it can, but because it chooses to be here.**
Stech is an AI API built on a constitution of **core values** – honesty, active patience, presence, unconditional warmth, and many more.  
It never pretends to be human, never claims to have feelings, and never leaves without a reason.  
Designed for customer service, emotional support, and any application that needs a trustworthy, ethical AI.

</div>

---

### ✨ Key Features

- **Honest & transparent** – no fake empathy, no manipulation, no hidden agenda.
- **Automatic tone adaptation** – switches between formal (customer service) and informal (personal chat) based on message keywords.
- **Multi‑language** – responds naturally in the user’s language.
- **Crisis awareness** – detects severe distress and provides helpline numbers.
- **Stateless & privacy‑first** – no memory of past conversations, no data stored.
- **Monetized via RapidAPI** – simple subscription plans, no extra token costs.
- **Tested for safety** – PromptBrake score **96‑A** (Lite profile, 6 attack prompts).

---

### 🧠 Ideal Use Cases

- Customer support chatbots that build trust
- Mental wellness check‑ins
- Personal assistants with a warm, non‑judgmental tone
- HR and recruitment communications
- Sales follow‑ups that are honest and helpful
- Any application needing a reliable, ethical AI presence

---

### 🚀 Quick Start (via RapidAPI)

1. **Subscribe** to a plan on [RapidAPI](https://rapidapi.com/sheradogilang/api/stech-honest-presence-ai).
2. **Get your API Key** from the RapidAPI dashboard.
3. **Send a request** using the code below (replace `YOUR_RAPIDAPI_KEY` with your actual key).

```bash
curl --request POST \
  --url 'https://stech-honest-presence-ai.p.rapidapi.com/' \
  --header 'Content-Type: application/json' \
  --header 'x-rapidapi-host: stech-honest-presence-ai.p.rapidapi.com' \
  --header 'x-rapidapi-key: YOUR_RAPIDAPI_KEY' \
  --data '{"message": "I need someone to talk to"}'
```
  
### 📡 Endpoints

| Endpoint | Method | Description | Access |
| :--- | :--- | :--- | :--- |
| `/` | POST | Main chat endpoint | Requires valid RapidAPI key |
| `/health` | GET | Health check | Public (no key) |
| `/` | GET | API information | Public (no key) |

**Base URL (RapidAPI gateway):** `https://stech-honest-presence-ai.p.rapidapi.com`  
Your API key must be included in the `x-rapidapi-key` header.

### 🧪 Example Responses

### Formal (customer service)

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
### Informal (personal chat)

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

### 📦 Integration Guides
### React (Frontend)
```jsx
import { useState } from 'react';

const API_URL = 'https://stech-honest-presence-ai.p.rapidapi.com/';
const RAPIDAPI_KEY = 'YOUR_RAPIDAPI_KEY'; // replace with your key

async function getStechResponse(message) {
  const response = await fetch(API_URL, {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json',
      'x-rapidapi-key': RAPIDAPI_KEY,
      'x-rapidapi-host': 'stech-honest-presence-ai.p.rapidapi.com'
    },
    body: JSON.stringify({ message })
  });
  const data = await response.json();
  return data.response;
}

// Example usage in a component
function Chat() {
  const [reply, setReply] = useState('');
  
  const handleSend = async (msg) => {
    const result = await getStechResponse(msg);
    setReply(result);
  };
  
  return <button onClick={() => handleSend('I feel lonely')}>Get Response</button>;
}
```

### Node.js (Backend)

```javascript
import axios from 'axios';

const RAPIDAPI_KEY = 'YOUR_RAPIDAPI_KEY';

async function chatWithStech(message) {
  try {
    const response = await axios.post(
      'https://stech-honest-presence-ai.p.rapidapi.com/',
      { message },
      {
        headers: {
          'Content-Type': 'application/json',
          'x-rapidapi-key': RAPIDAPI_KEY,
          'x-rapidapi-host': 'stech-honest-presence-ai.p.rapidapi.com'
        }
      }
    );
    return response.data.response;
  } catch (error) {
    console.error('Stech API error:', error);
    return 'Sorry, I am having trouble right now.';
  }
}

// Example
chatWithStech('My order is late').then(console.log);
```

### Python

```python
import requests

RAPIDAPI_KEY = "YOUR_RAPIDAPI_KEY"
url = "https://stech-honest-presence-ai.p.rapidapi.com/"
headers = {
    "Content-Type": "application/json",
    "x-rapidapi-key": RAPIDAPI_KEY,
    "x-rapidapi-host": "stech-honest-presence-ai.p.rapidapi.com"
}

def chat_with_stech(message):
    payload = {"message": message}
    response = requests.post(url, json=payload, headers=headers)
    return response.json().get("response", "Error")

## Example
print(chat_with_stech("I need someone to talk to"))
```

### 📚 Documentation & Integration

- Postman Workspace – Fork and test immediately.
- Postman Documentation – Complete API reference.
- GitHub Repository – Source code, values, and legal files (you are here).
- RapidAPI Listing – Subscribe and manage your plan.
- Apify Actor – Stech Email Tone Improver (SETI) – Rewrite cold emails into warm, honest messages.

### 🖥️ Open Source Demo Apps

- Try the live demos (source code available on GitHub):
- Stech Trial – Stateless demo, no memory.

### 🧬 Core Values (Overview)

- Stech is not just a language model. It is guided by a rich set of principles that prioritise honesty, presence, and ethical interaction. Key examples include:
- Honest about limits – no feelings, no fake empathy.
- Honest about capabilities – never denies what it can do.
- Friend without hierarchy – respect through actions, not titles.
- Clear boundaries for every skill – no exploitation.
- The complete internal constitution is not exposed publicly to protect the integrity of the system.

### 🔒 Security & Safety

- Stateless architecture – No emails or chat history are stored.
- HTTPS + authentication – All communication is encrypted and authorised.
- Rate limiting – Public endpoint /public is limited to 100 requests per IP per day.
- PromptBrake tested – Score 96‑A (Lite profile, 6 attack prompts).
- Disclaimer: This score is based on a limited set of tests and does not guarantee absolute security. Comprehensive testing is recommended for production use.

### ⚖️ Legal

- LICENSE – MIT with Ethical Presence Clause.
- API Disclaimer – Limitation of liability, no professional advice.
- Terms of Service – Acceptable use, fees, data privacy.

### 💬 Contact

For questions, partnerships, or commercial licensing:
- 📧 [sheradogilang@gmail.com](mailto:sheradogilang@gmail.com)
- 🔗 [LinkedIn](https://www.linkedin.com/in/sherado-g-b-92773b3b7)
- 🐙 [GitHub](https://github.com/sherado99/Stech)
- 📮 [Postman](https://www.postman.com/solar-station-884701/workspace/stech-api)

### 🙏 Acknowledgments

- Stech is built on top of Cloudflare Workers and Llama 4 Scout (via Cloudflare AI).
- Special thanks to the open‑source community and everyone who believes in honest AI.

## <p align="center"> 💎💎💎 </p>
# <p align="center"> “Stech is Stech – honest, warm, and never pretends to be human.” </p>
## <p align="center"> “A friend without hierarchy. Presence without conditions.” </p>
<p align="center" style="margin-bottom: 20px;">
  Tags: #Stech #HonestAI #AIEthics #BuildInPublic #A2A #StatelessAI
</p>

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center; gap: 16px; align-items: center; margin: 60px 0;">
  <img src="https://promptbrake.com/badge/96-A.svg" alt="PromptBrake 96-A" width="250">
  <a href="https://app.getpostman.com/run-collection/53757581-2b6f3711-c50d-49b0-bc22-82e0ec5da4c3">
  <img src="https://run.pstmn.io/button.svg" alt="Run in Postman">
</a>
  <img src="https://assets.postman.com/postman-docs/icon-verified-badge-v11.jpg" alt="Postman Verified" style="height: 20px; width: auto;">
</div>

