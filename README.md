<div align="center">
<h1> Tanmay Saini </h1>
</div>

---

## About me

CS 2nd year at VIT Vellore. I build systems where the model is part of the product, but not the product itself - a scoring engine, a search pipeline, a couple of things driven by agents.

This year I’m going deeper on the bits that decide if any of it actually works: retrieval and how to evaluate it properly, backends that can handle load, why agents fail in ways that look like success, and the algorithms that nothing gets past an interview without. The goal is simple enough to say out loud. Be really good at building standard artificial intelligence systems, and be able to prove it rather than just claim it.

I learn more from deadlines than I do from courses, so what I want most is to be doing this on a team. Real problems, people who will tell me when I’m wrong, and something that ships at the end of it.

---

## Selected work

### [life-score](https://github.com/tanmaysainighy/life-score) · TypeScript

Write what you did in plain language, get a deterministic score. One rule holds it
together: **the model interprets, it never scores.** It sees a shortlist of candidate
names — never a rate, never a number — and any id it returns that wasn't on that list
gets rejected. Next.js, Postgres, and a test suite that runs against Postgres compiled
to WASM, so it needs no database server at all.

[Live app](https://life-scoring-app.onrender.com)

### [student-events-hub](https://github.com/tanmaysainighy/student-events-hub) · JavaScript

Student events across India, assembled per request from live web search instead of a
database. Search is the easy half — most results aren't events, they're blog posts and
directory pages, so most of the code is a ranking function deciding what to throw away
before extraction. Nothing errors; every stage degrades to a worse answer.

[Live](https://student-events-hub.vercel.app)

### [vehicle-scout-mino](https://github.com/tanmaysainighy/vehicle-scout-mino) · JavaScript

Six used-car marketplaces searched at once by six browser agents. Runs take a minute, so
results stream back per platform over SSE and the page fills as each finishes — including
a live view of the browser each agent is driving. One timeout doesn't take the other five
down.

[Live](https://vehicle-scout-mino.vercel.app)

### [skills](https://github.com/tanmaysainighy/skills) · Agent skills

Six research skills that fan agents across sources in parallel and synthesise one report:
OSS bounties, company hiring signals, open CFPs, research landscapes. Two of them read a
market sideways — what a company is *hiring for* says more about its next year than its
careers page does.

---

## Toolkit

**Building with:** Python · TypeScript · Postgres · Next.js · Node · Docker · Git

**Learning properly this year:** PyTorch · retrieval evaluation · inference cost and
latency · agent reliability

I write up what I got wrong and why, on the repo it came from. Those are usually the
parts worth reading.

---

## Open to

**AI/ML and software engineering internships** — India-based or remote. Second-year, so
I'm looking for the kind of team where I'd own something end to end and learn faster than
a structured programme would let me.

**If you're a small team, here's an easier offer:** point me at a real problem and give me
two weeks. I'll ship something, free, no obligation either way. You get a fix or you lose
nothing, and we both find out whether I'm any good without either of us guessing from a
resume.

That's genuinely how I'd rather be evaluated.

<p align="center">
  <a href="https://www.linkedin.com/in/sainitanmay">LinkedIn</a> ·
  <a href="mailto:tanmay.saini2025@vitstudent.ac.in">tanmay.sainighy@gmail.com</a>
</p>
