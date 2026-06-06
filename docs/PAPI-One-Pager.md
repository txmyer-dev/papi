# Public AI (PAPI) - One-Pager

## Mission
Democratize access to Large Language Models (LLMs) by aggregating the world's free inference capacity into a single, reliable, zero-cost API.

## The Problem
- **AI is expensive**: Proprietary APIs (OpenAI, Google, Anthropic) cost $20-$200+/month, locking out students, indie developers, and non-profits.
- **Free tiers are fragmented**: Every major AI lab (Google, Groq, NVIDIA, Mistral) offers a free tier, but they are isolated, rate-limited, and difficult to manage.
- **The gap**: There is no unified, reliable way to access this collective ~1.7 billion tokens/month of free capacity.

## The Solution
**Public AI (PAPI)** is a non-profit initiative that provides a single OpenAI-compatible API endpoint, aggregating 16+ free LLM providers.

### Core Technology
| Feature | Description |
|---|---|
| **Unified API** | One endpoint (`/v1/chat/completions`) compatible with OpenAI SDKs. |
| **Smart Router** | Automatically picks the best available provider based on uptime, latency, and rate limits. |
| **Provider Fallback** | When one provider hits a rate limit, the request instantly falls back to the next. |
| **Encrypted Keys** | User API keys are stored encrypted; no raw keys are held in plaintext. |
| **Transparent Usage** | Tracks per-key usage to ensure compliance with free-tier limits. |

**Current Providers**: Google, Groq, Cerebras, SambaNova, NVIDIA, Mistral, OpenRouter, GitHub Models, Cohere, Cloudflare, HuggingFace, Z.ai, Ollama, Kilo, Pollinations, LLM7.

## Service Model
| Tier | Access | Model | Price |
|---|---|---|---|
| **Free** | Shared API pool via grant funding. | Access to all 97+ models through the router. | $0 |
| **Premium** | Dedicated managed instance. | Personal API keys, priority routing, guaranteed uptime. | ~$1,500/year |

## Impact
- **For Students**: Access cutting-edge AI for research and learning without financial barriers.
- **For Developers**: Build AI-powered applications with zero API costs during development.
- **For Non-Profits**: Power operations and services with high-quality language models at no cost.
- **For the Ecosystem**: Reduce reliance on a few proprietary gatekeepers by making open-weight models accessible.

## Current Status
- **Live Prototype**: A fully functional aggregation server is running, tested, and routing requests successfully.
- **Next Steps**: Secure 501(c)(3) status, launch public beta, and apply for foundational grants.

## The Ask
We are seeking **partners and funders** who believe in open, equitable access to AI technology.
- **Cloud Credits**: To host the free-tier service for the first 1,000 users.
- **Grants**: To cover operational costs and developer time for the first year.
- **Community**: Developers and researchers to test, provide feedback, and help optimize the router.

---
*Public AI (PAPI) - Building digital infrastructure for the public good.*