# Omidyar Network Grant Application
**Funder:** Omidyar Network - Responsible Tech Program  
**Project:** The People's AI (PAPI)  
**Amount Requested:** $150,000 (18-month pilot)  
**Date:** 2026-06-05  
**Applicant:** [Your Name], Founder, The People's AI  
**Legal Status:** Applying as individual with intent to form 501(c)(3); open to fiscal sponsorship if required  

---

## Executive Summary
The People's AI (PAPI) builds a simple bridging layer that connects the fragmented "free inference" capacity offered by major AI companies (Google, Groq, NVIDIA, etc.) to students, researchers, and community organizations who currently lack affordable access to powerful language models. For $150,000 over 18 months, PAPI will operate a reliable, OpenAI-compatible API endpoint that aggregates ~1.7 billion tokens/month of free capacity, serving an initial pilot of 1,000 users from underserved communities. This grant will fund core infrastructure, community outreach, and impact measurement to prove that AI access can be democratized without relying on costly proprietary models.

---

## 1. The Problem: The AI Divide
Artificial intelligence is rapidly becoming essential for education, research, and civic participation, yet access remains deeply unequal:
- **Cost Barrier:** Leading proprietary LLM APIs (OpenAI, Anthropic, Google Gemini) cost between $20 and $200+ per month per user. This places them out of reach for students in underfunded schools, independent researchers, and small non-profits.
- **Fragmented Free Tiers:** While every major AI lab offers a free tier, these are isolated, subject to strict rate limits, and require users to manage dozens of separate API keys and accounts—creating a usability barrier that negates the benefit.
- **Underutilized Capacity:** Roughly 1.7 billion tokens per month of high-quality inference capacity sit underutilized because there is no simple, unified way for the public to access it.

This "AI Divide" risks concentrating the benefits of AI in the hands of the wealthy and well-connected, exacerbating existing inequalities in education, innovation, and civic voice.

---

## 2. Our Solution: A Bridging Layer for Public Access
The People's AI (PAPI) does not create new AI models or inference capacity. Instead, we build and maintain a lightweight **bridging layer** that:
- **Aggregates Access:** Provides a single, reliable OpenAI-compatible API endpoint (`/v1/chat/completions`) that routes requests across 16+ free-tier providers.
- **Ensures Reliability:** Uses intelligent routing and automatic fallbacks to maximize uptime and minimize rate-limit errors.
- **Removes Complexity:** Users need only one API key and one endpoint—no need to manage multiple accounts or monitor individual provider limits.
- **Respects User Autonomy:** API keys are stored encrypted; users can bring their own keys for higher limits if desired.
- **Operates Transparently:** Tracks usage to ensure fair-use compliance and publishes aggregate statistics for community accountability.

PAPI is built upon the audited, open-source `FreeLLMAPI` core. Our prototype is live and successfully serves requests across providers including Llama 3, Mistral, and Qwen families.

---

## 3. Why Omidyar Network?
Omidyar Network’s Responsible Tech program seeks to "shape technology to work for people and society." PAPI directly aligns with this mission by:
- **Promoting Digital Equity:** Expanding access to a foundational 21st-century resource (AI) to those excluded by cost.
- **Supporting Open Infrastructure:** Leveraging and amplifying existing open-source and free-tier offerings rather than building proprietary alternatives.
- **Empowering Civic Participation:** Enabling students, researchers, and community organizers to use AI for learning, advocacy, and public-good projects without financial barriers.
- **Mitigating Concentration of Power:** Counters the trend of AI access being gated by a few corporate gatekeepers by mobilizing underutilized capacity for the public.

PAPI is not a speculative technology—it is a pragmatic, immediately deployable solution that uses existing resources to serve an urgent social need.

---

## 4. Impact & Beneficiaries
**Primary Beneficiaries (Pilot Phase):**
- **Students** in under-resourced high schools and community colleges seeking to learn AI concepts or build projects.
- **Independent Researchers** in the social sciences, humanities, and STEM who need language models for analysis but lack grant funding for API costs.
- **Small Non-Profits** working on community organizing, public health, or environmental justice who could use AI for data analysis, outreach, or translation.

**Anticipated Pilot Metrics (18 months):**
- **Users Served:** 1,000 active users in the free tier.
- **Requests Processed:** 5 million API requests (utilizing a small fraction of the available free capacity).
- **Community Engagement:** 200+ active participants in a public Discord forum for support and idea-sharing.
- **Impact Stories:** Document 5-10 detailed case studies of how PAPI enabled a specific educational, research, or community project that would not have been possible otherwise.

**Long-Term Vision:** If successful, PAPI can scale to serve tens of thousands of users, becoming a permanent piece of digital infrastructure for the AI era—akin to a public library for language models.

---

## 5. Budget Request: $150,000 (18 Months)
| Category | Amount | Justification |
|----------|--------|---------------|
| **Infrastructure Hosting** | $45,000 | Covers server costs (compute, storage, bandwidth) for the bridging layer and API gateway. Based on current usage estimates and includes redundancy for reliability. |
| **Community & Outreach** | $30,000 | Funds modest stipends for community moderators, creation of multilingual tutorials, and virtual workshops for target beneficiary groups. |
| **Impact Measurement** | $25,000 | Supports part-time evaluation support to collect usage data, conduct user surveys, and develop case studies. |
| **Personnel (Part-Time Founder Stipend)** | $40,000 | Provides essential living support for the founder to maintain and develop the service, respond to user needs, and pursue sustainability. |
| **Legal & Compliance** | $10,000 | Covers initial legal consultation for 501(c)(3) formation and review of provider Terms of Service to ensure compliant aggregation. |
| **Contingency (10%)** | $0 | Included in above categories. |
| **TOTAL** | **$150,000** | |

*Note: PAPI does not seek to profit from inference. The $150,000 funds the service of hosting, maintaining, and bridging access—not the AI models themselves, which remain free.*

---

## 6. Timeline & Milestones
**Months 1-3: Foundation & Launch**
- Finalize legal structure (501(c)(3) or fiscal sponsor).
- Deploy and monitor production-ready bridging layer with basic analytics.
- Launch waitlist and onboard first 100 beta users from partner organizations (e.g., coding bootcamps in underserved areas, community colleges).
- Begin community Discord and documentation.

**Months 4-9: Growth & Refinement**
- Scale to 500 active users; optimize routing algorithms for better latency and fallbacks.
- Host quarterly virtual workshops on "AI for Community Projects" and "Prompt Engineering for Non-Profits."
- Publish first impact case studies and usage transparency report.
- Apply for follow-on funding and explore AWS/GCP non-profit credits.

**Months 10-18: Sustainability & Scale**
- Reach 1,000 active users; solidify community governance model.
- Develop self-serve dashboard for users to monitor their usage and keys.
- Explore premium managed tier ($1,500/year) for users needing dedicated instances—strictly as cost recovery, not profit.
- Publish final impact report and lessons learned for the Responsible Tech field.

---

## 7. Evaluation & Learning
PAPI will measure success through both quantitative and qualitative metrics:
- **Quantitative:** Monthly active users, total API requests, provider uptime, rate-limit incidents, user retention.
- **Qualitative:** Semi-structured interviews with 20 pilot users, open-ended feedback in community forum, documented case studies.
- **Transparency:** All aggregate usage data (no personal data) will be published quarterly on a public dashboard.

We will partner with an independent evaluator (budgeted above) to ensure rigorous impact assessment and to produce a shareable case study for the Responsible Tech community.

---

## 8. About the Applicant
[Your Name] is a longtime builder of open-source tools and advocate for digital equity. After recognizing the growing inaccessibility of state-of-the-art AI, [you] spent the past 12 hours prototyping a bridging layer using FreeLLMAPI and confirmed its viability through live testing. [You] are committed to building PAPI as a permanent public good and are seeking initial support to transition from prototype to sustainable service.

---

## 9. Attachments (Available Upon Request)
- Link to live prototype: `http://localhost:3001` (demonstration available)
- Link to GitHub repository: `https://github.com/txmyer-dev/papi`
- Master Grant One-Pager: `docs/MASTER-GRANT-ONE-PAGER.md`
- Detailed budget spreadsheet
- Letters of interest from potential community partners (to be secured)

---
*We believe the benefits of AI should not be limited to those who can pay. The People's AI is a bridge to ensure that everyone—regardless of income—can participate in the AI era.*