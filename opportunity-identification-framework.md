# Consultative Discovery with AI

**For:** Cisco Sales Engineers — **generalist SEs** with little to no prior contact center or collaboration expertise.
**Use:** Spot Contact Center / Customer Experience opportunities inside accounts that don't necessarily *look* like CC accounts.

> **Plain-language framing.** This guide uses some industry terms (CCaaS, IVR, omnichannel, AHT, NPS, deflection, Webex AI). Each is defined the first time it appears. You do **not** need to be a CC specialist to use this. Your job here is to *recognize* an opportunity and pull the right Cisco people in — not to become the technical expert.

## About this workshop

### What it is

- A 1-hour module within a half-day Cisco workshop.
- Designed for **generalist** Cisco Sales Engineers — no prior CC/CX or collaboration expertise required.
- A guided, AI-assisted flow that takes the SE from a cold customer name to four ready-to-use artifacts: a customer pre-brief, a chosen opportunity with use case, a tailored intro email + 5 discovery questions, and a customer-facing proposal.
- Built around a single chat thread in **[Cisco CIRCUIT](https://circuit.cisco.com)** so each generated prompt builds on the prior one with full customer context.

### What it does

- Teaches how to identify CC/CX opportunities at any account — including **internal** contact centers like IT help desk, HR shared services, and employee support, not just external customer-facing ones.
- Translates the Cisco CC/CX portfolio into plain language a generalist SE can actually use: Webex Contact Center, Webex AI Agent, Webex AI Agent Assist, Webex Connect, and Webex Calling.
- Produces concrete, account-specific artifacts in the session — not abstract frameworks.
- Equips the SE to open a credible CC/CX conversation with a named persona at a real account, then take the resulting proposal back to the AM and the CC/AI specialist for refinement.

### What it is not

- **Not** a deep-dive into Webex Contact Center features, CCaaS architecture, or implementation detail — that remains the specialist's job.
- **Not** a replacement for the CC/AI specialist team — this is the qualification and door-opening motion that happens before the specialist gets engaged.
- **Not** a one-size-fits-all script — every artifact is tailored to the specific customer, opportunity, and persona being pursued.
- **Not** a substitute for human judgment — the AI generates strong starting drafts, but the SE and account team validate, correct, and refine before anything goes to the customer.

---

## 0. Start here — tell us about your customer, then let AI do the homework

Before you work through the rest of this guide, spend 5 minutes giving an AI assistant some context about your customer so it can pre-load you with what's worth pursuing. You'll bring that output into the rest of the workshop as your starting point.

### Step 0a — Capture what you know about the customer

Fill in as much as you can. Don't worry about gaps — even just the customer name is enough to get value.

- **Customer name:**
- **Industry / vertical:**
- **HQ location and major regions of operation:**
- **Subsidiaries, brands, business units (if known):**
- **Specific locations relevant to your account (offices, branches, plants, contact centers, retail, dealer networks):**
- **Existing Cisco footprint in the account (collaboration, networking, security, anything you know):**
- **How they serve customers today — external *and* internal.** External = end customers, members, policyholders, patients, citizens, dealers, brokers. Internal = employees served by IT help desks, HR shared-service centers, finance / payroll service desks, facilities, employee benefits centers, technical support desks. Many large companies run **internal contact centers** that are bigger than their external ones — these are real opportunities. Note both if you can:
  - **External-facing channels:** (call center, mobile app, web chat, branches, field techs, agents/dealers/brokers, etc.)
  - **Internal-facing service organizations:** (IT help desk, HR service center, employee support, finance/payroll desk, facilities, etc.)
- **Specific focus area you want to pursue (optional).** If you already have a hypothesis about *where* to lead — e.g. "I want to focus on their internal IT help desk," or "I want to lead with AI self-service for their member services line," or "let's pursue dealer support in EMEA" — capture it here. The AI will weight its recommendations toward this focus. Leave blank if you want a fully open-ended scan.
- **Any current pain, news, or initiative you're aware of** (vendor change, M&A, AI mandate, layoffs, regulatory, customer-experience push):

### Step 0b — Generate your AI pre-brief

Based on what you entered in Step 0a, the workshop tool builds a **customized AI prompt** for *your* customer — not a generic one. Click **Generate prompt**, then **Copy** it into **[Cisco CIRCUIT](https://circuit.cisco.com)** — Cisco's internal, sanctioned AI chat (preferred for any work involving customer or account context). You can also paste it into ChatGPT, Claude, Copilot, or Gemini if that fits your workflow, but **CIRCUIT is the recommended starting point**, especially when the input includes specific customer names or account information. The prompt instructs the AI to:

1. **Customer snapshot** — short profile of industry, approximate size (employees, revenue, customers served, internal users), known footprint, and the 1-2 most relevant CC/CX dynamics for this kind of business (external and internal). 4-5 bullets max.
2. **Top 2 opportunities** — the strongest 2 to pursue at this customer, with for each:
   - Why it's a top 2 pick (fit, urgency, low friction, strategic alignment, vendor disruption, AI mandate)
   - **Customer financial impact** — quantified annual value to the customer with brief math (assumptions × scale = $) and a low / likely / high range
   - **Cisco opportunity size** — estimated agents/users/interactions in scope and approximate ARR + 3-year TCV range for Cisco
   - Relevant Cisco solutions (Webex CC, Webex AI Agent, Webex AI Agent Assist, Webex Connect, etc.)
   - Best persona to engage (by role) and one door-opener for the next conversation
3. **Confidence & verification** — what the AI is guessing vs. inferring vs. what you need to verify before quoting any of the figures externally.

Total response is constrained to roughly one page. The AI is told to quantify wherever possible and give ranges with assumptions instead of "it depends."

If you specified a **focus area** in Step 0a (e.g. internal IT help desk, dealer support, AI self-service), the AI will weight its recommendations toward that area while still surfacing other strong opportunities for situational awareness.

> The full prompt text is generated for you on the workshop page from the fields above — you don't have to write it. Just fill in 0a, click Generate, and copy.

### Step 0c — Use the output as your starting point

Take the AI's ranked opportunity list into the rest of this guide. As you walk through the discovery scan, persona map, and qualification checklist below, use the AI's output to:

- Pick **one opportunity** to focus on for this exercise
- Identify **one persona** to target an introduction to
- Draft **one discovery conversation** you would actually try

> ⚠️ The AI output is a *starting hypothesis*, not the truth. Treat it as a research head-start. You and your account team validate and correct it.

---

## 1. Match Cisco solutions to the opportunity

> **Translation up-front.** When we say *contact center* (CC) or *customer experience* (CX), we mean **anywhere a customer interacts with the business** — phone calls, web chat, mobile app messages, in-branch visits, field technicians, dealer/broker/agent networks, even back-office service teams. It is not just the room with headsets and dashboards. And remember: **internal** service organizations (IT help desk, HR shared services, employee support) count too — often bigger than the external ones.

Now that you have a ranked list of opportunities from your AI pre-brief (Step 0b), the next move is to **start matching Cisco's solutions to the opportunity you want to pursue**. You don't need to be the technical expert — you just need to recognize which Cisco capability fits where, and pull in the right specialist when it's time to go deeper.

### What a CC/CX opportunity looks like

**Signals to watch for**
- Vendor renewal coming up (CCaaS / UCaaS), failing IVR, or obvious platform pain
- AI mandate from the C-suite, agent attrition, or productivity pressure
- Channel fragmentation across voice / chat / digital
- M&A consolidation or a new digital-channel push (WhatsApp / RCS / outbound service)

**Buying windows**
- Incumbent contract renewal or fiscal-year planning
- Post-M&A platform consolidation
- Regulatory deadline (recording, privacy, service controls)
- Service incident or AI-transformation budget cycle that has executive attention

**Internal AND external examples**
- **External:** retail customer service, insurance claims, banking call center, telco support
- **Internal:** IT help desk, HR shared services, employee benefits support, internal facilities / employee service desk

**What to ignore (for now)**
- Pure calling / UCaaS refresh with no service angle
- Individual agent tools with no platform play
- Single-team chatbot experiments with no enterprise scope

Park those for now — they may be real projects, but not necessarily CC/CX deals.

### The three Cisco solutions you'll lead with

**Webex Contact Center (Webex CC) — the cloud platform for customer conversations.**
- *What it is in plain terms:* The cloud-delivered system that runs the customer's contact center — handles inbound calls, routes them to the right agent or queue, integrates with their CRM (e.g. Salesforce), gives supervisors dashboards, and provides reporting on what happened. Replaces or modernizes whatever they're using today (Genesys, Five9, NICE, Avaya, Cisco UCCE, or homegrown).
- *Examples of where it fits:* Customer wants to move off an aging on-prem contact center. Customer is consolidating multiple regional CC vendors. Customer is standing up a new internal help desk and wants a real CC platform under it (not just a phone tree). Customer's current CCaaS vendor is up for renewal and they're shopping.
- *When to lead with it:* Anywhere there's a contact center buying decision in the next 12-18 months — vendor renewal, M&A consolidation, platform refresh, or "we're tired of what we have."

**Webex AI — AI capabilities purpose-built for the contact center.**
- *What it is in plain terms:* Cisco's AI portfolio for the contact center, including:
  - **AI Agent** — AI handles the conversation directly (voice or chat self-service). Used for things like "check my balance," "reset my password," "schedule an appointment," "what's my claim status."
  - **AI Agent Assist** — AI sits next to the human agent in real time, listening, suggesting answers, summarizing the call, and pre-filling notes after the call ends. Cuts call time, reduces ramp time for new agents.
  - **AI-powered analytics & coaching** — AI scores every interaction, surfaces themes, identifies coaching moments. Replaces the "we manually QA 2% of calls" model.
- *Examples of where it fits:* Customer is under deflection pressure (too many calls, not enough agents). Customer has high agent attrition and wants to ramp new hires faster. Customer wants to extend service hours without adding headcount. Customer has been told "do something with AI" by the CEO and doesn't know where to start.
- *When to lead with it:* When the customer says "AI" first. When deflection, AHT, agent productivity, or first-call resolution is named as a target. When you're up against a competitor's AI story.

**Webex Connect — digital channels and customer journey orchestration.**
- *What it is in plain terms:* The platform that lets the customer engage their customers on **digital channels** (SMS, WhatsApp, RCS, email, push, web chat, mobile in-app) and **orchestrate the journey across them** — e.g. send an appointment reminder by SMS, then escalate to chat if the customer replies, then escalate to a live agent if needed. Programmable flows. No per-channel point solutions.
- *Examples of where it fits:* Customer wants to launch WhatsApp / SMS / RCS for service. Customer is running 3-4 different vendors for SMS, chat, and email and wants to consolidate. Customer wants proactive outbound (appointment reminders, payment reminders, fraud alerts, delivery updates). Customer wants to deflect from voice into digital but doesn't have the tools.
- *When to lead with it:* When the conversation is about *digital* — SMS/WhatsApp/RCS, mobile app messaging, omnichannel — or about *proactive* customer communication, not just inbound voice.

### How they fit together (the "One Cisco" story)

These three are **designed to work together as one platform**. A typical mature deployment looks like:

- A customer calls in → Webex CC routes it.
- Webex AI Agent answers first and handles 30-50% of intents end-to-end (no human needed).
- For everything else, Webex CC routes to a human agent — and Webex AI Agent Assist sits next to that agent in real time.
- Webex Connect runs the digital side (SMS reminders, WhatsApp service, proactive outbound) — and any digital interaction can be escalated into Webex CC if the customer wants to talk to a human.
- All of it produces unified data the customer can act on.

That's the story. You don't need to memorize every product detail — you need to recognize which of those three a customer's pain points point to, and bring the right specialist (CC SE, AI/Connect SE, CX engineering) in to go deeper.

### Generate your "match Cisco to my opportunity" prompt

Pick one opportunity from your AI pre-brief output (Step 0b) — the one you want to actually pursue with this customer. Enter it in the field on the workshop page, then click **Generate matching prompt**. The page will build a customized follow-up prompt that you paste into the **same chat thread** you started in Step 0b (so the AI already has all the customer context).

The follow-up prompt is **focused on developing use cases** in executive summary format. It asks the AI to deliver:

1. **Opportunity frame** — business problem in customer language, who feels it, success metrics, applicable Cisco solutions (3-4 bullets max).
2. **Top 3 use cases** — the core of the response. For each: scenario at *this specific customer*, Cisco solution mapping, **quantified business outcome** with assumptions × scale = $ math and a low/likely/high range, why this use case wins at this customer, and **1-3 industry references** (news articles, customer success stories, press releases, analyst reports) that support that specific use case in the customer's industry — with real URLs, or "No supporting references found" if none exist.
3. **Next step** — best persona to engage (by role), most credible door-opener for the next conversation, 1-2 discovery questions to validate the strongest use case.
4. **Risks & verification** — top gaps, risks, competitive considerations, and what the SE needs to verify before quoting use case figures externally.

The AI is constrained to a one-page response, plain language, and quantified ranges instead of "it depends."

Take the AI's response into the rest of the workshop as your **opportunity playbook draft**.

> ⚠️ Same rule as Step 0b — the AI output is a strong starting point, not the truth. You and your account team validate, correct, and refine it. Bring in your CC/AI specialist when you're ready to go deeper.

---

## 2. The 5-question discovery scan

Use these in any meeting — even meetings that aren't about CC. They take ~3 minutes and tell you whether to pull the thread. None of them require you to be a CC expert.

Use the static 5 questions in your **first** conversation when you know very little about the account. Use the persona-tailored generator once you know who you are meeting and already have customer context loaded in the same CIRCUIT thread. The static questions surface the opportunity; the tailored questions advance it.

1. **"Where in your business do people — customers OR employees — go when they need help?"**
   → Surfaces every service path the organization runs, including customer-facing journeys and internal support motions that IT may not fully own.

2. **"What does the experience look like today across those channels — for customers AND for employees who need internal support?"**
   → Surfaces fragmentation, channel silos, and inconsistency across voice, chat, digital, in-person, and internal-service journeys. Cisco's *omnichannel* story lands here.

3. **"What are you measuring — and what are you being asked to improve this year?"**
   → Surfaces the business outcome (retention, deflection, AHT, NPS, cost-to-serve, or internal-support efficiency). This is what the proposal will be tied to, not features.

4. **"Where are you using — or thinking about using — AI to help customers OR employees get answers faster?"**
   → Surfaces opportunities for **AI Agent** and **AI Agent Assist** across both customer-facing and internal-service environments. Maps to Webex AI directly.

5. **"What's getting in the way today — vendor, platform, integration, cost, agent experience?"**
   → Surfaces the wedge: CCaaS / UCaaS renewal, a failing **IVR** (Interactive Voice Response — the "press 1 for…" phone menu), an internal help-desk platform gap, a Salesforce integration issue, or unsustainable per-agent / per-channel cost pressure.

**How to read answers**

- **Strong signal:** the customer names a specific business problem, mentions a metric, references vendor/platform pain, or asks what Cisco would do.
- **Weak signal:** answers stay generic, no metric appears, or the customer says they're merely exploring.
- **Non-answer:** they deflect to IT, procurement, or have no real view. That's often a persona-targeting problem, not a qualification fail.

If your contact cannot answer 3 of the 5, you are probably talking to the wrong person. Use the persona generator to identify who you should be meeting and ask the AM for that intro.

### Advance / Hold / Park rubric

Check for these four before you move beyond discovery:

1. **Problem** — named service problem with at least one metric or business outcome
2. **Person** — known owner, or at least a specific target persona to engage first
3. **Trigger** — a credible why-now: renewal, AI mandate, fragmentation, cost pressure, service issue, consolidation, regulatory deadline
4. **Path** — a plausible Cisco capability mapping and a clear specialist to bring in

- **All 4 ✓ → ADVANCE** — generate the proposal in Section 4 and engage the specialist now
- **2-3 ✓ → HOLD** — stay in discovery; the proposal is internal-only, not customer-ready
- **0-1 ✓ → PARK** — not a CC/CX opportunity yet; move on or come back when a trigger appears

### Specialist routing

- **CC platform, routing, supervisor experience, CCaaS renewal, migration** → Webex Contact Center specialist
- **AI Agent, AI Agent Assist, conversation analytics, coaching** → Webex AI specialist
- **SMS / WhatsApp / RCS, proactive outbound, journey orchestration, digital deflection** → Webex Connect specialist
- **Telephony, calling architecture, PSTN, calling-adjacent consolidation** → Webex Calling / Collaboration specialist

### Handoff packet to the specialist

- Chosen opportunity (1 line)
- Target persona + status (engaged / introduced / cold)
- Evidence from discovery (what they said)
- Assumptions still unverified
- Expected outcome / metric
- Specialist type requested
- Requested next step (joint discovery, demo, scoping call)

The workshop page also lets the SE pick from a buyer-prioritized persona list and generate a persona-tailored AI prompt that produces 5 customized discovery questions. The prompt is designed as a **continuation of the same chat thread** started in Step 0b — the AI reuses the customer context AND the use cases developed in Section 1, and anchors every question to the **specific opportunity the SE chose to pursue**. Questions are tailored to all three: the persona's worldview, this customer specifically, and the chosen opportunity. Output structure: a 1-2 line anchor statement, then per question — the question itself, why it works for this persona at this customer for this opportunity, what a strong signal sounds like, the Cisco capability it maps to, and the best follow-up move.

---

## 3. Draft the introductory email

The workshop page now turns Section 3 into an email-drafting generator. The SE picks a recipient title from the same 20-title list used in Section 2, chooses one of 5 tone options (Formal & executive, Professional & consultative, Conversational & warm, Direct & concise, Peer-to-peer technical), and selects either a **Brief** or **Detailed** outreach length. The generated prompt continues the same chat thread from Step 0b / Section 1 / Section 2 and asks the AI to draft a tailored intro email with a specific subject line, an opening anchored to something real about this customer, use case framing tied to the chosen opportunity, plain-language Cisco capability mapping, a low-friction next step with proposed time windows, and a sign-off placeholder for the SE.

---

## 4. Draft the customer proposal

Before generating the proposal, confirm the four qualification checks from Section 2 — **Problem / Person / Trigger / Path**. If you have all 4, the proposal is ready for customer-facing refinement. If you have 2-3, treat the output as internal-only. If you have 0-1, go back to discovery first — the proposal will be hollow.

Section 4 now generates the customer-facing proposal as a continuation of the same chat thread. The SE picks a proposal format (**Executive summary (1 page)**, **Detailed proposal (3-5 pages)**, **Pilot scoping document**, or **Business case / ROI-focused**), chooses a commercial framing (**Per-unit / buyable slice**, **Single platform deal**, **Pilot then expand**, or **Phased rollout**), and decides whether to include pricing placeholders. The AI then drafts a proposal anchored to the chosen Section 1 opportunity, structured around executive summary, business problem, proposed solution, business outcome, commercial shape, pilot / first phase, expansion path, why Cisco, and next steps. Format-specific rules compress or expand those sections based on the selected document type.

---

## 5. What to leave the workshop with

The workshop now produces four concrete downstream artifacts around one account and one opportunity:

- **One AI pre-brief** — the Step 0b output with the top 2 opportunities, customer financial impact ranges, and Cisco TCV estimates in the same CIRCUIT thread.
- **One chosen opportunity + use case** — the Section 1 use case selected to pursue, with quantified outcome, Cisco mapping, and supporting industry reference(s).
- **One persona + intro email + 5 discovery questions** — the Section 2 and Section 3 outputs ready to use for outreach and the first meeting.
- **One proposal draft** — the Section 4 customer-facing proposal, in the format and commercial shape that match the customer's buying motion, ready for AM / CC specialist refinement.

That is the unit of progress: one account, one opportunity, four ready-to-use artifacts, one next move.
