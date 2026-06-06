# The People's AI (PAPI) - Master Grant One-Pager
**Version:** 1.0 (Foundation)
**Date:** 2026-06-05

## 1. Executive Summary
The People's AI (PAPI) is a non-profit digital infrastructure project designed to democratize access to cutting-edge artificial intelligence. We build a **bridging layer** that connects fragmented "free inference" tiers—offered by companies like Google, Groq, and NVIDIA—to students, researchers, and non-profits. By providing this access at zero cost, we bridge the growing "AI Divide" between those who can afford premium subscriptions and those who cannot.

## 2. The Problem: The "AI Divide"
The current AI landscape is characterized by extreme financial barriers:
- **Prohibitive Costs:** Leading LLM APIs and subscriptions (OpenAI, Anthropic, Google) cost between $20 and $200+ per month. For a student in the Global South or a small non-profit, this is an insurmountable barrier.
- **Fragmented Free Tiers:** While many providers offer free tiers, they are isolated, subject to strict rate limits, and require individual management of dozens of API keys.
- **Waste of Capacity:** Roughly 1.7 billion tokens per month of high-quality inference capacity offered by major AI companies sits underutilized because there is no unified bridge to connect it to the public good.

## 3. The Solution: The People's AI (PAPI)
PAPI builds a **bridging layer** that makes these free tiers accessible to everyone by organizing them into a single reliable endpoint. We do not create the models or the inference—we simply ensure the people who need them can reach them.

### Key Capabilities:
- **Universal Compatibility:** One endpoint (`/v1/chat/completions`) that works with any existing OpenAI-compatible software.
- **Intelligent Routing:** A smart router that automatically detects the best available provider based on latency, uptime, and current rate limits.
- **Resilient Fallback:** If one provider hits a limit, the request instantly shifts to the next available model, ensuring high availability without cost.
- **Transparency & Safety:** Keys are stored with industry-standard encryption, and usage is tracked to ensure fair-use compliance across the community.

## 4. Impact & Beneficiaries
- **Digital Equity:** Providing world-class AI tools to the 99% who are currently priced out of the market.
- **Education:** Allowing students and educators in under-resourced areas to build AI-powered research and learning tools.
- **Non-Profit Optimization:** Enabling NGOs to automate operations and analyze data using models they otherwise could not afford.
- **Open Innovation:** Lowering the barrier to entry for independent developers and researchers globally.

## 5. Technical Foundation
PAPI is built upon the audited, open-source `FreeLLMAPI` core. Our current prototype is live and successfully routing requests across 16+ providers and 97+ models, including Llama 3, Mistral Large, and Qwen.

## 6. The "Service vs. Inference" Model
We maintain a strict distinction:
- **Inference is Free:** We never charge for the AI's "brain."
- **Infrastructure is Funded:** We seek grants and donations to cover the **service of hosting and maintenance**. 
- **Sustainability:** For users requiring dedicated, high-availability instances, we offer a "Premium Managed" tier at cost ($1,500/year) to ensure the organization remains sustainable without compromising the mission.

## 7. The Ask: Operational Support
We are seeking funding to transition PAPI from a successful prototype to a scalable global infrastructure.
- **Infrastructure Credits:** To support the first 10,000 free-tier users.
- **Legal & Compliance:** To finalize 501(c)(3) status and ensure TOS compliance with all providers.
- **Development:** To optimize routing algorithms and build a user-friendly dashboard for community monitoring.

---
*The People's AI (PAPI) - Building digital infrastructure for the public good.*
