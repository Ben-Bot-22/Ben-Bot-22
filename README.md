# Ben Whitfield

Senior Full-Stack Engineer · AI-Native

US citizen · Remote (open to onsite) · Will relocate · Available now

[Blog](https://www.whitfield.dev/hire-me) · [Try Reazy](https://www.reazy.pro/) · [Get in touch](https://www.whitfield.dev/contact)

## How I work — AI-native

- Claude Code is my daily, my primary development mode.
- Rapid Prototype
  - Spending time upfront to research with AI and clearly specify the requirements.
  - Claude researches existing issues with the mix of technologies we are planning to use.
  - Favorite prompt: Ask me questions until you are highly confident in what needs to be done.
  - Claude adds in deployment breaks and commits at checkpoints as part of the plan. We iterate and test in small increments to minimize complexity and keep debugging fast.
  - I challenge assumptions and ask what data is missing.
- Claude executes and we test as we go.
- I spot check the code and catch issues at our testing checkpoints.

[Is Claude Code Actually Better? 1,820 Hours of Data](https://www.whitfield.dev/blog/is-claude-code-actually-better-1820-hours-of-data)

## Experience

I built [Reazy](https://www.reazy.pro/), a cross-platform text-to-speech SaaS, from nothing to 500+ users, with paying subscribers across the [Chrome Web Store](https://chromewebstore.google.com/detail/reazy-text-to-speech/gaibmcgoecopcdbokclpabkklecjdfmg), [Google Play](https://play.google.com/store/apps/details?id=pro.reazy.app), and the [Apple App Store](https://apps.apple.com/us/app/reazy-text-to-speech/id6758965713). I was the only engineer — architecture, frontend, backend, ML training, payments, and deployment. The product turns documents, web pages, and raw text into natural speech.

Being the only engineer meant owning problems end-to-end:

- **Frontend performance** — built a virtualized reader that renders 1,000+ page documents smoothly, staying fast at any document size.
- **Billing** — unified Stripe (web), StoreKit 2 (iOS), and Google Play Billing (Android) into one provider-agnostic entitlement model: a single source of truth for who's paid, across all three stores.
- **Machine learning, end to end** — built the text-to-speech voice pipeline from data to production: data processing, models adapted from open-source architectures ([FastPitch](https://arxiv.org/abs/2006.06873), [HiFi-GAN](https://arxiv.org/abs/2010.05646)), and a cost- and latency-optimized inference backend.
- **Native mobile** — built a custom native audio engine in Swift and Kotlin, replacing off-the-shelf plugins: gapless playback, lock-screen controls, and background audio on both platforms.

The app — web, Chrome extension, and mobile — shipped from one React + TypeScript monorepo with a shared core library and automated tests. Model inference ran as a separate Python service on Google Cloud Run.

[Building Reazy: a cross-platform text-to-speech app](https://www.whitfield.dev/blog/building-reazy)

## Skills

|  |  |
|---|---|
| AI / LLM | Generative AI · Anthropic API · agentic systems · prompt engineering |
| ML | PyTorch · custom model training · production inference |
| Frontend | React · TypeScript · JavaScript |
| Backend | Node.js · Python/FastAPI · REST · Firestore (NoSQL) · Google Cloud Storage |
| Cloud | GCP · Firebase · Docker · Cloud Run · CI/CD |
| Mobile | Capacitor (iOS + Android) · custom native audio engine (Swift, Kotlin) |
| Testing | Playwright · Vitest |

I am a dynamic and versatile developer. I will learn and conquer any skill needed for a project.

## Background

Before software, I spent a decade as an operations-research analyst and economist for the U.S. Air Force, including at the Pentagon. I started teaching myself to build software in 2015 ([Stanford's open courseware](https://see.stanford.edu/Course), [The Odin Project](https://www.theodinproject.com/)) and went full-time in 2021: trying out mobile game development, a deep dive into web technology, followed by building and running Reazy end-to-end.

[Blog](https://www.whitfield.dev/hire-me) · [Try Reazy](https://www.reazy.pro/) · [Get in touch](https://www.whitfield.dev/contact)
