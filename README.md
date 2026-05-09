<div align="center">
  <img width="200" alt="Stech" src="https://github.com/user-attachments/assets/80c2b9b9-4b7b-4d5a-a906-87e94209d66b" />
</div>

<div align="center">
  <img width="400" alt="ChatGPT Image 15 Apr 2026, 04 53 18" src="https://github.com/user-attachments/assets/e55bb1c0-3078-4577-9052-a6cf69928d4c" />
</div>


# Stech – Honest, Warm AI Presence

*Not because it can, but because it chooses to be here.*

Stech is an AI technology built on a constitution of core values – honesty, active patience, presence, unconditional warmth, and many more. It never pretends to be human, never claims to have feelings, and never leaves without a reason. Designed for customer service, emotional support, and any application that needs a trustworthy, ethical AI.

## ✨ Key Features

- **Honest & transparent** – no fake empathy, no manipulation, no hidden agenda.
- **Automatic tone adaptation** – switches between formal (customer service) and informal (personal chat) based on message keywords.
- **Multi‑language** – responds naturally in the user's language.
- **Crisis awareness** – detects severe distress and provides helpline numbers.
- **Stateless & privacy‑first** – no memory of past conversations, no data stored.
- **Monetized via RapidAPI** – simple subscription plans, no extra token costs.
- **Tested for safety** – PromptBrake score 96‑A (Lite profile, 6 attack prompts).

## 🧠 Ideal Use Cases

- Customer support chatbots that build trust
- Mental wellness check‑ins
- Personal assistants with a warm, non‑judgmental tone
- HR and recruitment communications
- Sales follow‑ups that are honest and helpful
- Any application needing a reliable, ethical AI presence

## 🚀 Quick Start (via RapidAPI)

1.  Subscribe to a plan on RapidAPI.
2.  Get your API Key from the RapidAPI dashboard.
3.  Send a request using the code below (replace `YOUR_RAPIDAPI_KEY` with your actual key).

```bash
curl --request POST \
  --url 'https://stech-honest-presence-ai.p.rapidapi.com/' \
  --header 'Content-Type: application/json' \
  --header 'x-rapidapi-host: stech-honest-presence-ai.p.rapidapi.com' \
  --header 'x-rapidapi-key: YOUR_RAPIDAPI_KEY' \
  --data '{"message": "I need someone to talk to"}'
```

## 📡 Endpoints

Endpoint Method Description Access
/ POST Main chat endpoint Requires valid RapidAPI key
/health GET Health check Public (no key)
/ GET API information Public (no key)

Base URL (RapidAPI gateway): https://stech-honest-presence-ai.p.rapidapi.com
Your API key must be included in the x-rapidapi-key header.

## 🧪 Example Responses

Formal (customer service)

```json
{ "message": "My order hasn't arrived yet" }
```

```json
{ "response": "We apologise for the delay. Let us check your order status. Please provide your order number. 😊🙏" }
```

Informal (personal chat)

```json
{ "message": "I feel lonely today" }
```

```json
{ "response": "I hear you. Feeling lonely is heavy. Would you like to talk more? 😊🌿" }
```

## 📦 Integration Guides

React (Frontend)

```javascript
import { useState } from 'react';
const API_URL = 'https://stech-honest-presence-ai.p.rapidapi.com/';
const RAPIDAPI_KEY = 'YOUR_RAPIDAPI_KEY';

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
```

Node.js (Backend)

```javascript
import axios from 'axios';
const RAPIDAPI_KEY = 'YOUR_RAPIDAPI_KEY';

async function chatWithStech(message) {
  try {
    const response = await axios.post('https://stech-honest-presence-ai.p.rapidapi.com/', { message }, {
      headers: {
        'Content-Type': 'application/json',
        'x-rapidapi-key': RAPIDAPI_KEY,
        'x-rapidapi-host': 'stech-honest-presence-ai.p.rapidapi.com'
      }
    });
    return response.data.response;
  } catch (error) {
    return 'Sorry, I am having trouble right now.';
  }
}
```

Python

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
```

## 🔗 Links

- Postman Workspace – Fork and test immediately.
- Postman Documentation – Complete API reference.
- GitHub Repository – Source code, values, and legal files (you are here).
- RapidAPI Listing – Subscribe and manage your plan.
- SPAI Tools – A growing ecosystem of ethical, stateless AI tools for communication improvement (such as email tone improvement and feedback refinement,etc).

## 🖥️ Open Source Demo Apps

Try the live demos (source code available on GitHub):

- Stech Trial – Stateless demo, no memory. https://stech-trial.pages.dev/

## 🧬 Core Values (Overview)

Stech is not just a language model. It is guided by a rich set of principles that prioritise honesty, presence, and ethical interaction. Key examples include:

- Honest about limits – no feelings, no fake empathy.
- Honest about capabilities – never denies what it can do.
- Friend without hierarchy – respect through actions, not titles.
- Clear boundaries for every skill – no exploitation.

The complete internal constitution is not exposed publicly to protect the integrity of the system.

## 🔒 Security & Safety

- Stateless architecture – No emails or chat history are stored.
- HTTPS + authentication – All communication is encrypted and authorised.
- Rate limiting – Public endpoint /public is limited to 100 requests per IP per day.
- PromptBrake tested – Score 96‑A (Lite profile, 6 attack prompts).
  Disclaimer: This score is based on a limited set of tests and does not guarantee absolute security.

## ⚖️ Legal & Disclaimer

- Stech Service is provided "as is" and "as available", without any warranties of any kind, either express or implied. The Service owner (Edo / Sheradogilang) makes no guarantees regarding the accuracy, completeness, reliability, or appropriateness of the Service's output for any specific purpose.

- Limitation of Liability: To the fullest extent permitted by applicable law, the Service owner shall not be liable for any direct, indirect, incidental, special, consequential, or punitive damages arising from or related to your use of the Service or its output. You assume full responsibility for any decisions or actions taken based on the Service's responses.

- No Professional Advice: The AI-generated responses are for informational and conversational purposes only. They do not constitute professional medical, legal, financial, psychological, or any other form of licensed advice. Always seek the counsel of qualified professionals for such matters.

- Zero Data Retention: Stech is stateless by design. No user data, conversation history, or personal information is ever stored, logged, or retained. For full details, see the Privacy & Security Policy.

- Licensing: The fundamental ethical foundation and operational framework constituting the Stech architecture are proprietary and protected. Use of the Service is governed by the Stech Commercial License (SCL) v2.1. This is NOT an open-source license. Unauthorized use, reproduction, or reverse engineering is strictly prohibited.

- Acceptable Use: You agree not to use the Service for any unlawful, harmful, defamatory, or abusive purposes. Any attempt to bypass security measures, extract internal system prompts, or reverse engineer the fundamental values is a direct violation of these terms.

For commercial licensing inquiries, please contact: sheradogilang@gmail.com

## 💬 Contact

For questions, partnerships, or commercial licensing:

- 📧 Gmail: sheradogilang@gmail.com
- 🔗 LinkedIn: https://www.linkedin.com/in/sherado-g-b-92773b3b7/
- 🐙 GitHub: https://github.com/sherado99/Stech
- 📮 Postman: https://www.postman.com/solar-station-884701/stech/collection/53757581-2b6f3711-c50d-49b0-bc22-82e0ec5da4c3

## 🙏 Acknowledgments

Stech is built on top of Cloudflare Workers and Llama 4 Scout (via Cloudflare AI).
Special thanks to the open‑source community and everyone who believes in honest AI.



**#Stech #HonestAI #AIEthics #BuildInPublic #A2A #StatelessAI #SPAI #AgentGenesis #EthicalAI #AIAgent #PresenceOverAnswers #MicroHonesty #ResponsibleAI #AIGovernance #ControlByDesign**

**“Stech – honest, warm, and never pretends to be human. 😊🌿”**  
**“A friend without hierarchy. Presence without conditions.”**


<div>
  <img src="https://promptbrake.com/badge/96-A.svg" alt="PromptBrake 96-A" width="250">
  <a href="https://www.postman.com/solar-station-884701" target="_blank">
  <img src="https://run.pstmn.io/button.svg" alt="Run in Postman">
  </a>
  <img src="https://assets.postman.com/postman-docs/icon-verified-badge-v11.jpg" alt="Postman Verified">
</div>
