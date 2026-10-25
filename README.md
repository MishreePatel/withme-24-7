# WithMe 24/7

**An AI-powered personal safety app with incident-triggered wellbeing aftercare.**

WithMe 24/7 is a mobile safety app built on a simple idea: safety apps shouldn't stop caring the moment an alert goes out. Most existing apps solve *half* the problem — family location tracking, emergency dispatch, or mental wellbeing — but none of them follow up with you after an incident actually happens. WithMe 24/7 does.

📺 **[Watch the demo video](https://youtu.be/HCI0wqdgAe0)**

 ## 🔗 Connect

   - 💼 LinkedIn: [Post about this series](https://lnkd.in/p/gj8CeNRc)

---

## The Problem

- **61.5M** U.S. adults experienced a mental illness in 2024 — only ~52% received treatment *(SAMHSA, 2025 National Survey on Drug Use and Health)*
- **32%** of women surveyed have felt unsafe with no way to reach anyone for help *(LogicMark national survey of U.S. women, 2025)*
- **26-point gap** between women (58%) and men (84%) who feel safe walking alone at night *(Gallup Global Safety Report, Nov. 2025)*

Two urgent needs — physical safety and wellbeing support — and no single product serves both.

## What Makes WithMe 24/7 Different

| | Life360 | Noonlight | Wysa | **WithMe 24/7** |
|---|:---:|:---:|:---:|:---:|
| Physical safety | ✅ | ✅ | ❌ | ✅ |
| Automatic detection | ✅ | ❌ | ❌ | ✅ |
| Multi-channel SOS | ❌ | ❌ | ❌ | ✅ |
| Pro emergency dispatch | ✅ | ✅ | ❌ | ❌ |
| Wellbeing awareness | ❌ | ❌ | ✅ | ✅ |
| **Post-incident aftercare** | ❌ | ❌ | ❌ | ✅ |
| Built for individual (not family) | ❌ | ✅ | ✅ | ✅ |
| No extra hardware needed | ✅ | ✅ | ✅ | ✅ |

WithMe 24/7 is the first of the four to treat the moment **after** a safety incident as part of the product — not the end of it.

## Core Features (MVP)

- **Walk Mode** — automatic incident detection while you're on the move
- **Trusted Circle** — multi-channel SOS to the people you choose
- **Wellbeing Aftercare** — a check-in that follows up after an incident resolves, not just before it

## Roadmap

- [x] Foundations — setup, architecture, wireframes
- [x] Core safety detection & SOS
- [ ] Contacts, notifications, polish
- [ ] Incident-triggered wellbeing check-ins
- [ ] Extended modes — Drive/Transit mode, gesture SOS, wake-phrase SOS, child-in-car check reminder

## Tech Stack

- **React Native (Expo)** — one codebase for iOS + Android
- **TypeScript** — type safety across the codebase
- **TensorFlow Lite** — on-device detection, keeps camera/voice data private
- **Firebase** — auth, database, and push in one managed service
- **Android Studio** — native Android builds and testing
- **Figma / Draw.io** — free, portable design and diagramming formats

## Status

🚧 Early development — follow along for updates.

## Sprint 1: Proposal and Initial Build

WithMe 24/7 is a personal safety app with incident-triggered wellbeing aftercare: automatic detection, multi-channel SOS, and post-incident check-ins.

**Sprint 1 delivered:** a login screen, welcome screen, database connections, an About Us screen, and a Welcome Back splash screen that stays on for 10 seconds before the About Us page.
**Tech stack:** React Native (Expo), TypeScript, Firebase, TensorFlow Lite, Android Studio

**Links**
- 📺 Sprint 1 video: https://youtu.be/0XEYzFIfla0
- 💼 LinkedIn post: https://lnkd.in/p/g4tKWF6C

## Sprint 2: Dashboard, Trusted Circle, and SOS Alert

WithMe 24/7 is an AI-powered personal safety application with incident-triggered wellbeing aftercare.

**Client feedback addressed (8 of 8)**

| # | Feedback | Status |
|---|---|---|
| 1 | Replace rust color theme | Addressed: deep teal and soft gold |
| 2 | Bigger icons; pages felt empty | Addressed |
| 3 | Post-login landing becomes a Dashboard | Addressed |
| 4 | About Us as an optional link on Welcome | Addressed |
| 5 | Remove timed Welcome Back screen | Addressed |
| 6 | Remember me with device passcode | Addressed |
| 7 | Reset Password page | Addressed |
| 8 | Same page names in app and diagrams | Addressed |

**Testing:** 12 manual test cases on an iPhone (Expo Go) against a live Firebase project. All passed.

**Links**
- 📺 Sprint 2 video: https://youtu.be/0cblgx2zO4Q
- 💼 LinkedIn post: https://lnkd.in/p/gu-6gn5Y

**Next sprint:** Check-in and Wellbeing Journal feature

Built by Mishree Patel
