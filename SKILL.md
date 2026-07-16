---
name: discover-acquisition-topics
description: Research and rank customer-acquisition content topics for any industry using current demand signals, customer language, trigger moments, competition density, willingness to pay, service fit, platform fit, and compliance risk. Use for prompts such as 获客选题、行业选题、内容选题、自媒体选题、账号选题、平台选题、选题库、选题规划、选题调研、选题 Skill、当下发什么、低竞争细分话题、潜在需求、客户痛点、需求激发、竞争拥挤度、爆款但不获客, or when Codex needs to find what an industry account should publish now, discover underserved customer scenarios, turn market research into lead-generating topics, build a test plan, or diagnose why content attracts views but not qualified customers.
---

# Discover Acquisition Topics

Find topics that attract qualified customers, not merely attention. Treat content as an invitation to human interaction and as one component of a complete acquisition path.

## Core standard

Define a strong acquisition topic as:

`specific person × trigger moment × felt pain/desire × decision gap × credible proof × service bridge`

Require the topic to help the right person think:

1. This describes my situation.
2. This matters enough to address.
3. This source understands the decision.
4. I know the appropriate next step.

Do not equate high traffic with high acquisition value. Prefer qualified conversations, bookings, paid diagnostics, purchases, gross profit, retention, and referrals.

## Operating principles

- Research current signals before recommending “the best topics.” Do not produce a confident ranking from generic memory alone.
- Start from people and situations, not industry labels or professional terminology.
- Prefer customer verbatim: searches, complaints, questions, objections, reviews, comments, sales conversations, and support logs.
- Separate explicit demand, problem-aware but solution-unaware demand, aspirational demand, convenience demand, and discovery-led desire.
- Reveal existing needs or useful possibilities. Never manufacture fear, conflict, illness, financial urgency, or unnecessary litigation.
- Distinguish an underserved opportunity from a market with no viable demand.
- Connect every shortlisted topic to an honest next step and an actual deliverable.
- Label assumptions, inferences, evidence gaps, and jurisdiction or date limitations.
- Treat platform algorithms as opaque. Use observed behavior and official guidance; do not state folklore as fact.

## Invocation and intake

Immediately tell the user that this skill is being used and that it will research demand, customers, competition, platforms, and service conversion before ranking topics.

Before researching, inspect the current conversation for an existing brief. Explicitly establish:

1. **Business:** industry, offer, geography, B2B/B2C, and business stage.
2. **Customer:** desired customer, excluded customer, buying role, and reachable population.
3. **Service:** what can actually be delivered, price range, capacity, qualifications, proof, and delivery owner.
4. **Need:** known pain/desire, trigger moment, attempted alternatives, urgency, and suspected willingness to pay.
5. **Platform:** intended channels, existing account/data, content capability, and whether the goal is search capture, recommendation discovery, trust, or retention.
6. **Conversion:** desired next action, lead qualification threshold, sales process, and commercial success metric.
7. **Evidence:** customer conversations, CRM/search data, cases, comments, competitors, and materials the user can provide.

If one or more core fields are missing, ask one compact batch of no more than five questions. Combine related fields instead of presenting a long questionnaire. Ask a second round only when an answer materially changes the research direction.

Treat these as core fields for a final topic ranking:

- customer or permission to discover the customer;
- service/capability or permission to design the offer hypothesis;
- market/geography;
- platform or permission to recommend platforms;
- conversion objective.

Do not silently invent missing core fields. If the user says “你来判断”, “先探索”, “没有想好”, or otherwise delegates discovery, proceed with bounded hypotheses, label them clearly, and make customer/service/platform discovery part of the research.

After intake, restate a compact working brief in one paragraph. Proceed without redundant confirmation when the brief is clear. Request confirmation only when two plausible interpretations would lead to materially different research or regulated delivery.

Read [references/prompt-library.md](references/prompt-library.md) when the user asks how to invoke the skill, requests prompt examples, or provides an overly broad request that would benefit from a better prompt.

## Workflow

### 1. Frame the market

Determine or reasonably assume:

- geography and language;
- industry and offer;
- B2B or B2C;
- target customer and excluded customer;
- price, purchase frequency, urgency, and trust requirement;
- current acquisition channels;
- delivery capability and available proof;
- desired conversion: sale, booking, diagnostic, visit, demo, application, or subscription.

Use the invocation intake above. Do not repeat questions already answered in the conversation. If the user requests exploration, make bounded hypotheses and continue.

### 2. Classify the buying engine

Identify the dominant buying motivation:

- **Problem repair:** loss, breakdown, dispute, risk, or urgent recovery.
- **Goal improvement:** learning, health improvement, career, efficiency, or performance.
- **Desire and identity:** beauty, taste, status, belonging, novelty, or experience.
- **Convenience:** proximity, speed, availability, simplicity, or price clarity.
- **Organizational return:** revenue, cost, risk, compliance, productivity, or strategic advantage.

Use this classification to avoid forcing fear-based problem content onto desire-led categories.

### 3. Collect current evidence

Read [references/research-playbook.md](references/research-playbook.md) before conducting research.

Use available first-party data before public web data: interviews, CRM, sales calls, customer service logs, search-console data, comments, and transaction records. When internet research is needed, use the available internet research skill or tools; if `agent-reach` is installed, invoke it for supported platforms and follow its routing instructions.

Collect evidence in four layers:

1. **Demand:** customer wording, recurring questions, trigger events, attempted alternatives, emotional and economic stakes.
2. **Competition:** repeated topics, dominant promises, sameness, content saturation, ad density, and ignored questions.
3. **Economics:** willingness and ability to pay, expected value, service cost, repeat potential, and lead qualification.
4. **Context:** policy, technology, seasonality, social behavior, platform changes, and emerging customer identities.

Capture source, date, query, signal type, and confidence. Do not invent search volume, conversion rates, or market size.

### 4. Build a demand map

Map the customer's progression:

`unaware → felt symptom/desire → problem aware → solution aware → provider comparison → action → delivery → referral`

Prioritize the stages the business can influence and serve. In crowded markets, look especially for:

- customers who feel a problem but use non-professional language;
- relationship or life-cycle transitions;
- evidence or decision windows;
- new occupations, behaviors, technologies, or regulations;
- combinations of a mature service with a newly specific audience;
- “what should I do next?” uncertainty after free information has been exhausted;
- poor fit between existing offers and how customers actually buy.

Do not target people with no meaningful need merely because they can be frightened.

### 5. Audit crowding

Separate four conditions:

- **High demand / high competition:** differentiate by audience, moment, evidence, service design, or viewpoint.
- **High demand / low adequate supply:** prioritize and verify delivery capacity.
- **Low visible demand / credible latent need:** run inexpensive education and interaction tests.
- **Low demand / low supply:** do not mistake emptiness for opportunity.

Compare competitors by customer, promise, format, proof, price/offer, CTA, and unanswered comments. Whitespace must be supported by demand evidence.

### 6. Generate candidates

Generate at least 15 candidates before ranking. Cover a balanced portfolio:

- symptom or desire recognition;
- trigger-moment guidance;
- decision and comparison;
- mistakes and misconceptions;
- evidence, process, or behind-the-scenes proof;
- case diagnosis;
- self-check or checklist;
- objection handling;
- “when not to buy/use/act” trust content;
- post-purchase success, retention, or referral.

Write titles in customer language. Avoid jargon unless the audience uses it.

### 7. Score and filter

Read [references/scoring-framework.md](references/scoring-framework.md). Score every candidate out of 100 and apply disqualifiers.

Do not let a high virality estimate compensate for weak service fit, poor economics, misleading urgency, or compliance risk. Select a portfolio rather than ten near-identical topics.

### 8. Design the interaction and conversion path

For each finalist specify:

- intended audience and trigger;
- hook and core promise;
- useful free action;
- proof required;
- interaction prompt that elicits real context;
- qualification questions;
- next offer and responsible owner;
- platform-native format;
- compliance and reputation guardrails.

Prefer a proportionate path such as:

`content → comment/private question → structured screening → appropriate diagnostic/demo/visit → core offer → follow-up`

Allow “self-serve,” “not ready,” and “not a fit” outcomes. Do not funnel everyone into a sale.

### 9. Create a test plan

Test the top 3–5 topics cheaply before scaling. Vary one major element at a time: audience, trigger, promise, proof, format, or CTA.

Measure:

- qualified comments or replies;
- qualified private inquiries;
- screening completion;
- appointment or demo rate;
- paid diagnostic or purchase rate;
- gross profit and delivery quality;
- retention or referral;
- irrelevant inquiry rate, complaints, and policy violations.

Use views, likes, and saves only as diagnostic signals. Update the demand map from every meaningful interaction.

## Regulated and high-stakes industries

For legal, medical, financial, employment, education, safety, and other regulated or high-stakes topics:

- browse current primary or authoritative sources;
- check local licensing, advertising, solicitation, privacy, testimonial, and platform rules;
- distinguish education from individualized professional advice;
- do not promise outcomes or imply privileged access;
- do not use fabricated urgency, guaranteed returns, exaggerated compensation, or fear amplification;
- route diagnosis and delivery to appropriately qualified professionals;
- state important jurisdiction, eligibility, and evidence limitations.

If the user's proposed tactic creates avoidable harm or regulatory risk, reframe the tactic while preserving the legitimate commercial objective.

## Deliverable

Read [references/output-template.md](references/output-template.md) before the final synthesis. Adapt its depth to the request, but always provide:

1. market and customer definition;
2. evidence-backed demand and crowding diagnosis;
3. ranked topic shortlist with reasoning;
4. top topic briefs and conversion paths;
5. a small test plan and success metrics;
6. evidence gaps, risks, and assumptions.

Lead with the recommendation. Cite current external claims near the claim when web research was used.
