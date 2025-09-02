# PAIX Protocol

**Personal AI eXchange (PAIX)**
An open protocol for the agentic internet — built on email.

---

## ✨ What is PAIX?

**PAIX is an open email protocol that standardizes how personal AIs connect, communicate, and act on behalf of individuals.**
It doesn’t define the format of the content — it defines the logic of interaction.

PAIX turns email into a shared interface between:

* Individuals
* Their personal AIs (AI twins)
* Services and providers

PAIX works where email already works — making it the simplest, most universal way to bootstrap AI-native communication between people and services.

---

## 🧠 Why PAIX?

The internet wasn’t built for AI agents. Today, personal AIs interact with services by:

* **Scraping websites** — brittle and error-prone
* **Using APIs** — rare in consumer apps and costly to implement

**PAIX offers a better way:**

* ✅ **Universal** — email already exists everywhere
* ✅ **User-controlled** — no reliance on third-party APIs
* ✅ **Gradual adoption** — works today, evolves over time
* ✅ **Agent-ready** — AIs can initiate and manage interactions, with human oversight

---

## 🔌 What PAIX Enables

With a PAIX address, you can:

* Let your AI manage cancellations, address updates, receipts, renewals
* Give services a way to communicate with your AI (without building an API)
* Enable secure AI-to-AI messaging (e.g. between customer AI and service AI)
* Embed structured payloads (e.g. via MCP) while maintaining trust and identity
* Control who can interact with your AI, and revoke that access at any time

---

## 🔁 Designed to Work with Existing Protocols

PAIX **does not replace** protocols like MCP — it complements them.

* **PAIX handles the interface logic** — how messages are routed, secured, verified, and accessed by AI agents
* **Other protocols handle the content format** — such as MCP for contextual LLM payloads

**Example:**
A PAIX email message can carry a structured MCP payload in the body, letting the receiving agent parse it accordingly — while PAIX ensures it came from a verified sender, with trust metadata included.

---

## 🧱 How It Works

A PAIX address looks like this:

```
u7fw9s.k_3PZ9Q4F7G2@paix.example.com
```

That single address gives you:

* ✅ Verified email identity
* ✅ Shared inbox for both human and AI
* ✅ Built-in connect key (ECK) for secure API escalation
* ✅ Optional verifiable credentials (age, residency, KYC-lite)
* ✅ Passwordless login (OTP/magic link)

**At minimum, it’s just email.**
**At maximum, it’s:** ID + comms + API + AI interface + credentials — all in one.

---

## 👤 For Individuals

* Use your PAIX address instead of your regular email
* Let your AI twin manage tasks behind the scenes
* Rotate, revoke, or migrate your PAIX addresses as needed
* All messages are visible to both you and your AI

---

## 🏢 For Services

* Already compatible (if you support email)
* Detect PAIX domains to prevent fake accounts
* Gradually support structured automation (e.g. billing updates, confirmations)
* Enable AI-to-AI flows without needing a full API

---

## 🛠️ For Providers

* Issue and host PAIX addresses (`@paix.yourdomain.com`)
* Publish trust metadata via `/.well-known/paix`
* Handle cryptographic signing, key rotation, verifications
* Optionally issue credentials for age, residency, etc.

**Become a provider** to anchor trust for users and services alike.

---

## 🔐 Trust, Privacy & Compliance

* **Email security:** SPF, DKIM, DMARC
* **Agent security:** Ed25519 signatures, ECK keys, scoped access
* **User control:** Revoke or rotate addresses anytime
* **Regulatory-ready:** GDPR, CCPA, eIDAS, SSI, EU AI Act alignment
* **Selective disclosure:** Verified data without exposing raw info

---

## 📈 Adoption Path

| Stage               | Description                                                           |
| ------------------- | --------------------------------------------------------------------- |
| **0. Do Nothing**   | Treat PAIX email like any other email                                 |
| **1. Recognition**  | Identify PAIX domains, reduce fraud, route accordingly                |
| **2. Verification** | Accept provider-signed credentials (age, residency, etc.)             |
| **3. Automation**   | Support AI-to-AI interaction (billing, renewals, notifications, etc.) |
| **4. Escalation**   | Optional API flows via ECK for advanced integration                   |

---

## 🚀 Status

* PAIX is **live** — first provider: [Prifina](https://www.prifina.com)
* Early access documentation in `/specs` folder (coming soon)
* Developer tools and SDKs in progress

---

## 🤝 Contributing

We welcome contributions!
Submit issues, suggestions, or pull requests — or help implement PAIX in your own service.
See `CONTRIBUTING.md` for contribution guidelines.

---

## 📄 License

PAIX is released under the [MIT License](./LICENSE)

---
