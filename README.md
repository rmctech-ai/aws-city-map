# Raul's AWS City Map

A hand-drawn, clickable mind map for reviewing the **AWS Certified Cloud Practitioner (CLF-C02)** exam. AWS is treated as a city you rent: compute are the workers, storage the warehouses, databases the record keepers, networking the roads and gates, and so on.

## What's inside

- **Mind map** of core services in 8 districts. Click a service for a plain explanation, an analogy, a memory hook, exam keyword triggers, and which services it works with.
- **Show the flow**: a website request and a serverless invoice pipeline, traced on the map step by step.
- **Don't mix these up**: 24 groups of look-alike services (CloudWatch vs CloudTrail vs Config, SQS vs SNS vs EventBridge, KMS vs CloudHSM vs Secrets Manager, and more).
- **All exam services**: one card for every service on AWS's CLF-C02 in-scope list.
- **Keyword finder**: type an exam phrase, get the service.
- **14-day review plan** with tick boxes saved in your browser.

## Run it

Open `index.html` in any browser. No build step. It loads Google Fonts and rough.js from a CDN for the hand-drawn look.

To publish it with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Note

Analogies are memory aids, not exact definitions. The service list follows the [official CLF-C02 in-scope services](https://docs.aws.amazon.com/aws-certification/latest/userguide/clf-02-in-scope-services.html), which AWS says is not exhaustive.
