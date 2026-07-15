# Phishing Detection & Awareness Report

## Purpose
Phishing emails are fake messages designed to trick people into clicking dangerous links, giving away passwords, or handing over company information. This report analyzes two example phishing emails and explains how to spot similar attacks.

## Risk Classification Key
| Category | Meaning |
|---|---|
| ✅ Safe | Verified sender, no suspicious links. Safe to act on. |
| ⚠️ Suspicious | Has warning signs — verify with sender via a separate channel. |
| 🚨 Phishing | Confirmed fake — do not click, reply, or open attachments. |

## Executive Summary
| No. | Email | Main Trick Used | Risk Level |
|---|---|---|---|
| 1 | "Vanguard Security" — fake camera footage alert | Curiosity + urgency, link + attachment | 🚨 Phishing |
| 2 | "HR Compliance" — fake expense fraud alert | Fear of punishment, urgent link | 🚨 Phishing |

## Email 1 — "Vanguard Security" Impersonation
**From:** alex.lee@alerting-services.com (claims to be Vanguard Security / Contoso Corp)

**Why it's fake:**
- Sender domain doesn't match either claimed company
- Fake urgency disguised as confusion
- Asks reader to confirm personal details
- Offers both a link AND an attachment as backup delivery
- Generic greeting, no account-specific detail

**Risk Classification:** 🚨 Phishing

## Email 2 — "HR Compliance" Impersonation
**From:** human.resources@alerting-services.com (claims to be internal HR / Contoso Corp)

**Why it's fake:**
- Same fake domain as Email 1
- Fear-based pressure ("disciplinary measures", "respond urgently")
- No real details given about the alleged fraud
- Single link is the entire call to action
- Impersonal, generic signature

**Risk Classification:** 🚨 Phishing

## Common Pattern
- Both sent from the same lookalike domain impersonating different identities
- Both use urgency (curiosity vs. fear) to rush the reader
- Both center on a single malicious link

## Prevention Guidelines
**Do's:** Check sender's real domain • Hover links before clicking • Verify urgent requests via a known contact • Report to IT/Security • Slow down under pressure

**Don'ts:** Don't click unexpected links/attachments • Don't enter credentials after clicking an email link • Don't reply to "check if it's real" • Don't assume polish = legitimate

## Summary
Both emails are confirmed phishing attempts relying on urgency and impersonation rather than legitimate company domains. See `evidence.md` for the original screenshots.
