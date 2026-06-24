# Alpha Direct Speak-Up — interactive demo

A **presentation demo** of the Alpha Direct Speak-Up whistleblowing portal. It is a
single, self-contained web page that simulates the whole experience in the browser —
no backend, no database, no real data.

**Live demo:** https://prathap-alpha.github.io/alpha-direct-speakup-demo/

> ⚠️ **This is a demonstration only.** It is **not** a live reporting channel.
> Nothing typed into it is transmitted or stored anywhere — it lives only in the
> current browser tab. The real Speak-Up system (with genuine anonymity, encryption
> and KPMG routing) is a separate, **private** application.

## What it shows

- The anonymous **report** form and the one-time **receipt code** a reporter receives.
- **Tracking** a report and the **two-way, anonymous** conversation with KPMG
  (try the sample code `DEMO-1234`).
- The **KPMG console**: how an independent investigator sees sample cases, statuses
  and stats, and replies to a reporter.

Everything is seeded with fake sample cases. A version/build number is shown in the
header chip and the footer.

## Run it locally

Just open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8099
# then open http://127.0.0.1:8099
```

## Relationship to the real system

This repo is **public** and contains only the demo UI and fake data. The production
Speak-Up application — which handles real, sensitive reports — is kept in a separate
private repository and is not deployed from here.
