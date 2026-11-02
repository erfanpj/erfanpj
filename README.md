# Hi, I'm Erfan Pirjahandideh

I focus on **applied machine learning** and **reproducible experiments**—especially brain-signal pipelines with frozen protocols, participant-held-out evaluation, and read-only result viewers backed by committed reports. I also build **full-stack workflow demos**: local review services, audit logs, and labelled static fixtures recruiters can try without credentials.

## Featured projects

### [Brain Signals Lab](https://github.com/erfanpj/brain-signals-lab)

Motor-imagery EEG on a public PhysioNet subset: **50 participants**, **5 participant-held-out folds**, CSP+LDA mean **61.8%** test accuracy (**2.6 pp** fold spread) versus a **50.4%** most-frequent-class dummy baseline (**0.6 pp** spread). Results are saved JSON—not retrained on page load.

- **Try it:** open the [static results viewer](https://erfanpj.github.io/brain-signals-lab/viewer/) and sort participants below chance.
- **Code:** https://github.com/erfanpj/brain-signals-lab

These are pipeline results on one dataset, not clinical or neuroscience claims.

### [OpsDesk AI](https://github.com/erfanpj/opsdesk-ai)

Fictional support desk with handbook citations, human approval, revision, and at-most-once mock execution on the local service path. On a frozen held-out set (**60** tickets, evaluated once), rules reached **37/60** fully correct proposals versus **25/60** for a small local CPU model.

- **Try it:** use the [browser fixture on GitHub Pages](https://erfanpj.github.io/opsdesk-ai/) (simulation only; Python desk stays local).
- **Code:** https://github.com/erfanpj/opsdesk-ai

All Lumen Lane data is synthetic; model output is draft-only until a person approves.

## Working style

- Fix evaluation protocol and splits before modelling; document limits beside every public number.
- Prefer local, testable services and hash-chained audit trails over demo magic.
- Several portfolio repositories were implemented with **AI coding assistants**; each project README states scope, data fiction, and what still requires a local run.

## Verified links

| Demo | URL |
|------|-----|
| Brain Signals viewer | https://erfanpj.github.io/brain-signals-lab/viewer/ |
| OpsDesk fixture | https://erfanpj.github.io/opsdesk-ai/ |
