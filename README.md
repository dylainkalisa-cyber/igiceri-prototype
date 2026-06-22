# Igiceri — Interactive Prototype

**Live demo:** https://dylainkalisa-cyber.github.io/igiceri-prototype/

Igiceri is an AI-powered money tracker for African businesses. The phone receives money
(MTN MoMo, Airtel Money), Igiceri reads the SMS and surfaces the **current balance** and
**money in / money out** — income first.

This repo hosts the **clickable HTML prototype** so it can be opened on any device (incl. iPhone/iPad).

## What you can try
- Sign up with a name + 5-digit PIN, then sign in
- Home: current balance (read from SMS), Today / Yesterday / This-week money in & out, hide-balance toggle
- Money In/Out: From→To date range, type filters, search by payer
- Reports: Week / Month / Quarter / Year with an In-vs-Out chart and tooltips
- Ask Igiceri: chat that answers about your money
- Live "money in" notification simulation

## Notes
- This is a **mock with sample data** — it does **not** read real SMS. It demonstrates the UX only.
- The real app is a native **Android** build (Android can read MoMo/Airtel SMS; iOS cannot).