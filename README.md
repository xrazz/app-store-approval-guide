# iOS App Store Approval Checklist
**Legal, Payments & Transparency — Pass Review on the First Try**


This guide covers what gets apps **rejected after the build is done** — missing links, unclear pricing, and broken trust signals. It assumes you have already handled ASO, core functionality, and a working app.


## Before You Even Submit

**Create a landing page / website for your app.** This is not optional. It is where your legal links live, it gives reviewers something to verify, and it makes you look like a real product rather than a side project. It does not need to be complex — one page with your app name, a short description, Privacy Policy, Terms of Service, and a support email is enough.


## The Checklist

### 1. Legal Links

Have these three URLs ready and live before submission:

- Privacy Policy
- Terms of Service
- Support URL

Place all three in your **App Store Connect listing**, **inside the app** (Settings screen), and on your **website**. URLs must match exactly across all locations.


### 2. Support Page

Your support page should show a visible **support email** and whether you are an individual developer or a business. Reviewers check this. If they cannot find a way to contact you, the submission fails.


### 3. In-App Legal Access

In Settings (or an About screen), users must be able to reach Privacy Policy, Terms of Service, and Support in **one tap**. Do not hide these in sub-menus or use small text.


### 4. Paywall Clarity

Every plan on your paywall must clearly show the **exact price, billing frequency, and what the user gets**.

| Good | Bad |
|---|---|
| Start Monthly — $4.99/month | Go Premium |
| Yearly Plan — $39.99/year, billed annually | Best Value |

If you offer a free trial, state the trial length and what happens at the end — next to the button, not in fine print.


### 5. Restore Purchases

A visible **Restore Purchases** button is mandatory for any app with in-app purchases. It must work. Missing this is a near-certain rejection.


### 6. Cancellation Instructions

You do not need an in-app cancel flow, but you must tell users how to cancel. Add a line like:

> Cancel anytime from Settings > Apple ID > Subscriptions

Put this on the paywall or in subscription settings.


### 7. No Deceptive UI

Reviewers are trained to spot manipulative patterns. Avoid countdown timers that reset, misleading price anchoring, and paywall dismiss buttons that are intentionally hard to find. If it looks designed to trick the user, it will be rejected.


### 8. Reviewer Credentials

If any part of your app requires a login, provide a **working test account** in the App Review Notes field in App Store Connect. This is required, not optional.


## Pre-Submission Check

Run through these before you hit submit:

- [ ] All legal links are live and consistent across listing, app, and website
- [ ] Support page has a visible email
- [ ] Privacy Policy and Terms are reachable in one tap inside the app
- [ ] Every paywall option shows exact price and billing frequency
- [ ] Free trial terms are stated clearly next to the CTA
- [ ] Restore Purchases button exists and works
- [ ] Cancellation instructions are visible
- [ ] Test account provided in review notes (if login required)


## If You Get Rejected

1. Read the rejection notice — Apple cites the specific guideline violated
2. Fix only what was cited, nothing else
3. Use **Reply to App Review** in App Store Connect if the reason is unclear — this often gets you specific guidance
4. For clear-cut errors on Apple's part, file with the **App Review Board**


## Common Rejection Causes

| Issue | Fix |
|---|---|
| Missing or broken support URL | Add a live support page |
| No Privacy Policy in-app | One-tap link in Settings |
| No Restore Purchases button | Add to paywall or Settings |
| Vague pricing | Show price, currency, billing frequency |
| No cancellation info | Add instructions near the paywall |
| No test account provided | Add credentials in review notes |


*If this helped, consider contributing additions via PR.*
