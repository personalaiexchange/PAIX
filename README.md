# PAIX Protocol

**Personal AI eXchange (PAIX)**
An open protocol for the agentic internet — built on email.

---

## ✨ What is PAIX?

**PAIX is an open email protocol that standardizes how personal AIs connect, communicate, and act — on behalf of individuals, and with others.**
It doesn’t define the content inside the message — it defines how messages are sent, received, verified, and processed across a shared interface.

PAIX turns email into a universal communication layer between:

* Individuals
* Their personal AIs (AI twins)
* Services and providers
* **Other people’s personal AIs**

It works anywhere email works — making it the most practical and universal path into the agentic internet.

---

## 🧠 Why PAIX?

The internet wasn’t designed for autonomous agents. Today, personal AIs must either:

* **Scrape web pages** — fragile, duplicative, not scalable
* **Use APIs** — rare in consumer services, expensive to build and maintain

**PAIX offers a better way:**

* ✅ **Universal** — works with any email-compatible service
* ✅ **User-controlled** — people (not platforms) initiate and manage relationships
* ✅ **Gradual adoption** — services can do nothing, recognize, or automate
* ✅ **Agent-ready** — built for AI-to-AI communication under human supervision
* ✅ **Interpersonal** — AIs can talk to other people’s AIs, not just services

---

## 🔌 What PAIX Enables

With a PAIX address, you can:

* Let your AI handle tasks like cancellations, address changes, receipts, or renewals
* Give services a way to communicate directly with your AI — without building an API
* **Securely message other people’s AIs — for support, collaboration, negotiation, etc.**
* Enable AI-to-AI communication across users, systems, and services
* Embed structured formats (e.g. MCP payloads) while preserving user identity and control
* Revoke, rotate, or move your address at any time

---

## 🔁 Designed to Work with Existing Protocols

PAIX does **not replace** protocols like MCP — it complements them.

* **PAIX handles the interface logic** — how communication flows between agents, people, and systems
* **Other protocols define content format** — like MCP for LLM-ready context payloads

**Example:**
A service sends a PAIX message to a customer’s AI. That message contains a structured MCP payload. PAIX ensures the message is authenticated, trusted, and directed to the right AI — while MCP handles what the message contains.

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
* Let your AI twin manage repetitive or background tasks
* Rotate, revoke, or migrate your PAIX addresses at any time
* All messages are accessible to both you and your AI
* **Engage with services and other people’s AIs** — not just companies

---

## 🏢 For Services

* Already compatible if you support email
* Recognize PAIX domains to reduce spam and fake accounts
* Support automation (e.g. billing, renewals, notifications) over email
* **Enable direct AI-to-AI communication** — from your system to a customer’s AI
* Adopt gradually: do nothing, recognize, verify, or automate

---

## 🛠️ For Providers

* Host and issue PAIX addresses (e.g. `@paix.yourdomain.com`)
* Route messages to individuals and their AIs
* Anchor trust via SPF, DKIM, DMARC, Ed25519, etc.
* Publish metadata at `/.well-known/paix` for service discovery
* Optionally issue verifiable credentials (e.g. age, residency)
* Let users bring their own domain for full ownership

---

## 🔐 Trust, Privacy & Compliance

* **Security:** SPF, DKIM, DMARC, Ed25519, key rotation
* **Privacy:** user-controlled, revocable, verifiable credentials
* **Compliance:** GDPR, CCPA, eIDAS, SSI, EU AI Act
* **Selective disclosure:** share proofs (e.g. “over 18”) without raw data
* **Human-in-the-loop:** users confirm or supervise critical actions

---

## 📈 Adoption Path

| Stage               | Description                                                            |
| ------------------- | ---------------------------------------------------------------------- |
| **0. Do Nothing**   | Treat PAIX email like any other message                                |
| **1. Recognition**  | Detect PAIX domains, reduce fake users, improve routing                |
| **2. Verification** | Accept provider-signed credentials (age, residency, etc.)              |
| **3. Automation**   | Enable AI-to-AI messaging (invoices, billing updates, feature toggles) |
| **4. Escalation**   | Secure HTTPS/API connection using embedded connect keys (ECK)          |

---

## 🚀 Status

* PAIX is live — first provider: [Prifina](https://www.prifina.com)
* Early access documentation and specs in `/specs` folder (coming soon)
* Developer tools and SDKs in development

---

## 🤝 Contributing

We welcome contributions!
Open an issue or submit a pull request to:

* Improve the protocol
* Suggest new use cases
* Expand example integrations
* Implement PAIX in your own product or service

See `CONTRIBUTING.md` for contribution guidelines.

---

## 📄 License

PAIX is released under the MIT License.
You are free to use, implement, and extend the protocol.

---
