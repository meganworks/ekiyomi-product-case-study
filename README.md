# Ekiyomi | AI-Native Product Development

**English** | [日本語](./README.ja.md)

### Turning user needs into a shipped product — with multi-AI collaboration

**Product discovery · Product leadership · AI orchestration · Quality management · End-to-end delivery**

[Ekiyomi — Try the Web App](https://densha-ekimei-yomiage.pages.dev/) · [Get it on the App Store](https://apps.apple.com/jp/app/id6833512504)

![Ekiyomi app preview](https://densha-ekimei-yomiage.pages.dev/og.png)

## The opportunity: a small, recurring problem worth solving

Children who love trains often want someone to read aloud the station names on railway maps—sometimes again and again. But parents may be cooking, doing household chores, or otherwise unable to respond immediately.

**The product opportunity was straightforward: what if children could explore a railway map and hear station names whenever they wanted, without having to ask an adult each time?**

That insight became **Ekiyomi**, an interactive station-name reading app designed for young train enthusiasts. A child can select a railway line, tap a station to hear its name, and use a “Next” button for a train-announcement-style experience.

Feedback from children who tried the app reinforced the appeal of choosing familiar or favorite lines: *“I want to do the Yamanote Line!”* and *“I want to hear the line near my home!”*

**The differentiator is not text-to-speech alone. It is a self-directed experience built around what young users actually want to explore.**

## Product at a glance

| | |
| --- | --- |
| **Product** | Railway station-name reading app for young children |
| **Coverage** | **88 railway lines and 1,564 station entries** across the Tokyo rail network |
| **Platforms** | **Web and iOS**, both launched |
| **Core experience** | Tap-to-hear station names, next-stop announcements, animated train movement |
| **Delivery approach** | Claude Code for implementation, Codex for independent review, GitHub for change tracking |
| **My contribution** | Customer discovery, product concept and direction, requirements, AI orchestration, quality and delivery management |

## What this project demonstrates

### 01. Customer discovery → Product strategy

I translated an everyday user need into a concrete product concept: **help young children explore train lines independently through touch, audio, and visual feedback**. The product experience prioritizes intuitive navigation, line selection, and immediate responses.

User feedback highlighted the value of familiar and personally relevant routes, reinforcing the product's emphasis on breadth of line coverage and choice.

[Explore the product discovery case study →](./docs/en/product-discovery.md)

### 02. Multi-AI orchestration → Execution

Rather than treating AI as a single coding assistant, I used different tools for complementary roles:

- **Product lead (human):** define the problem, prioritize features, make UX and product decisions.
- **Claude Code:** implement features, refine the application, and prepare code changes.
- **Codex:** provide a separate review perspective on implementation quality.
- **GitHub:** coordinate changes and document the review-to-improvement process.

This separation turned AI assistance into a **managed delivery workflow**.

[Explore the AI delivery model →](./docs/en/ai-orchestration.md)

### 03. Independent AI review → Quality improvement

A Codex review surfaced **10 improvement areas**, including accessibility, child-appropriate controls, interface clarity, accuracy of route information, and iOS build readiness. Claude Code supported the subsequent improvements, documented through the development workflow.

This demonstrates **turning independent technical critique into actionable quality improvements**.

[Read the cross-AI review case study →](./docs/en/quality-management.md)

### 04. Product leadership → Continuous iteration

I guided iterations to onboarding, voice selection, continuous playback, and app identity. Each improvement connected functional delivery to a coherent user experience across Web and iOS.

[Read the product iteration case study →](./docs/en/product-iteration.md)

## AI-assisted delivery model

```text
User need / Product opportunity
              ↓
Product direction & prioritization [Human]
              ↓
Requirements & implementation [Claude Code]
              ↓
Independent review [Codex]
              ↓
Refinement & documented checks [Claude Code]
              ↓
Product decisions & acceptance [Human]
              ↓
GitHub change management → Web / iOS release
```

*This represents a documented collaboration pattern, not a claim of a fully autonomous, continuously operating multi-agent system.*

## Technology & tools

**Product / delivery:** User needs analysis, requirements definition, UX decisions, GitHub, pull-request-based change management  
**AI:** ChatGPT, Codex, Claude Code  
**Application:** HTML, CSS, JavaScript, Python, Capacitor  
**Voice / deployment:** VOICEVOX, Cloudflare Pages, GitHub Actions

## Case studies

| Case study | Capabilities demonstrated |
| --- | --- |
| [Product discovery & user insight](./docs/en/product-discovery.md) | Finding needs, framing problems, translating insight into requirements |
| [Multi-AI delivery workflow](./docs/en/ai-orchestration.md) | AI orchestration, accountability, execution management |
| [Cross-AI review & quality improvement](./docs/en/quality-management.md) | Review strategy, quality management, corrective action |
| [Product iteration & UX leadership](./docs/en/product-iteration.md) | Feature prioritization, product judgment, continuous improvement |

---

**My approach:** *Find a meaningful user problem. Turn it into a focused product. Orchestrate technology and AI to take it from concept to launch.*

This repository showcases product thinking and delivery practices; the production application's source repository is maintained separately.
