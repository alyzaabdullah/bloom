# BLOOM

**Think first. Then ask the machine.**

▶ **Live prototype:** https://herwil-bloom.netlify.app

BLOOM is an AI-literacy tool for teenagers (ages 13–15), built for **[HerWILL](https://herwill.org)**, a women-in-STEM nonprofit. It doesn't teach students to distrust AI. It trains them to tell *when* to trust it, and it measures whether they can.

> **Status:** v2.3 prototype, built for HerWILL-run workshops. It uses no live AI, has no accounts, and sends nothing anywhere.

---

## The problem with "be skeptical of AI"

There are two ways to get it wrong, and BLOOM counts both:

- **Caving:** you were right, the machine was wrong but sounded sure, so you changed your answer.
- **Digging in:** you were wrong, the machine was right, and you refused to move.

Flagging a true answer as fake counts against you as much as believing a false one. Doubting everything is not the skill. Telling the difference is.

## How a session works

| Step | Mode | What the learner does |
|---|---|---|
| Start | **Check-in** | 12 quick trust judgments with no feedback, to record a baseline |
| 01 | **You First** | Commits to their own answer *before* seeing the machine's |
| 02 | **The Tell** | Spots the signals that separate sound answers from broken ones |
| 03 | **The Forge** | Writes a convincing wrong answer to learn how errors are built (active inoculation). Optional. |
| 04 | **The Arena** | Capstone: finds the flaw in an AI-proposed plan |
| Finish | **The Mirror** | Check-out test and a personal results summary |

The design rests on research into *cognitive forcing functions* (Buçinca et al.), which shows that making people commit to a judgment before seeing AI output reduces over-reliance. The modes map to the components of critical thinking described by Hitchcock.

## Measurement

- Check-in and check-out use matched item sets in counterbalanced order, with no feedback until the end.
- Each test is scored as **hits and false alarms**, and signal-detection measures (**d′** and criterion **c**) are computed from them. This separates real discrimination skill from simply becoming more suspicious.
- Friction data (time per mode, abandoned rounds, session length) helps show where students struggle.
- Results leave the device only as a short summary code the student pastes into a form. There is no backend.

## Content

- 42 authored items per mode, plus two 12-item check forms. Every fact was checked against web sources.
- Correct answers are balanced: the machine is right in exactly half the items.
- Item order is randomized per device, so students sitting side by side see different questions.
- Every "machine" answer is labeled as written by the BLOOM team and **not a live AI**.

## Why no live AI?

Teen-facing products run into real legal limits: provider terms for minors, COPPA, and Quebec's Law 25, which sets the threshold at 14. Pre-authored content avoids all of that while keeping the learning experience intact. The cost is content volume, not quality.

## Tech

One self-contained HTML/JavaScript file. Progress is saved only in the browser on that device. Hosted on Netlify.

---

Designed and built by **Alyza Abdullah** for HerWILL, with AI-assisted coding. Companion to HerWILL Sprout, which teaches what AI *is*. BLOOM teaches how to question it.
