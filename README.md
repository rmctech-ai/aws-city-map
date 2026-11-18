# Raul's AWS City Map

> 🏠 Part of **[Raul's Cloud Learning Hub](https://rmctech-ai.github.io/)** · Live: https://rmctech-ai.github.io/aws-city-map/ · Original concept and design by Raul (rmctech-ai).

A hand-drawn, clickable mind map for reviewing the **AWS Certified Cloud Practitioner (CLF-C02)** exam. AWS is treated as a city you rent: compute are the workers, storage the warehouses, databases the record keepers, networking the roads and gates, and so on.

## What's inside

- **Mind map** of core services in 8 districts. Click a service for a plain explanation, an analogy, a memory hook, exam keyword triggers, and which services it works with.
- **Show the flow**: a website request and a serverless invoice pipeline, traced on the map step by step.
- **Don't mix these up**: 26 groups of look-alike services (CloudWatch vs CloudTrail vs Config, SQS vs SNS vs EventBridge, KMS vs CloudHSM vs Secrets Manager, and more).
- **All exam services**: one card for every service on AWS's CLF-C02 in-scope list.
- **Design principles & Well-Architected**: the six pillars with their design principles, trigger words and key services, the classic cloud design principles, and a "Which pillar?" quick check.
- **Keyword finder**: 4–7 triggers for every service (606 in total). View them by service or by keyword.
- **Two-week sprint**: 14 days of 6–8 hours across all four domains. Every block links straight to its topic in the hub, Field Guide, Atlas or this map. You can change the start date, and tick boxes are saved in your browser.
- Updated for **exam guide v1.3 (Oct 29, 2026)**: new support plan names, Amazon Quick, pricing and partner skills; services AWS lists as out of scope or no longer lists are marked low priority.

## AWS Architecture Atlas (`/atlas`)

A companion study page in the [`atlas/`](atlas/) folder: five real-world system designs (typhoon alerts, clinic records, delivery tracking, real estate, OFW remittance) built from interconnected AWS services. Each design has a clickable architecture diagram (tap a service for its meaning, tap a numbered arrow to play the request step by step), a 4-domain map, decision records (chosen service vs. closest distractor) and 5 batches of 15 multiple-choice questions (375 in total). Exam mode runs full 75-question batches in a 1 → 5 cycle and tracks a readiness streak (five batches in a row at 80%+), with scores and flags saved in your browser. Batch 6 is a 65-question timed mock exam weighted like CLF-C02, with Choose TWO questions, reshuffled on every attempt, and a domain breakdown. Batch 7 is a 132-question trainer for Select TWO, Select THREE and NOT / odd-one-out questions, with feedback on every option. The trigger-word table covers every service on the official in-scope list. It also has a searchable trigger-word and memory-hook table and a CLF-C02 coverage check.

These are design-only case studies for exam review; nothing in them is deployed.

Live: `https://rmctech-ai.github.io/aws-city-map/atlas/`

## Run it

Open `index.html` in any browser. No build step. It loads Google Fonts and rough.js from a CDN for the hand-drawn look.

To publish it with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Note

Analogies are memory aids, not exact definitions. The service list follows the official CLF-C02 exam guide v1.3 (Oct 29, 2026) in-scope list, which AWS says is not exhaustive.

## Service Field Guide (`/field-guide`)

One card per service (120), with what it does, use case, keywords, memory hook, analogy and the look-alike to tell it apart. Concepts, exam traps, an "Exam guide v1.3: what changed" section and a Quiz me mode that only asks about in-scope services. Cards for services outside the v1.3 list are badged.
