# 🧾 CapTableGuru – MVP Product Requirements Document (PRD)

## 📌 Overview

CapTableGuru is a zero-auth, visual-first, ELI5-powered tool that helps non-finance users (especially startup founders and early employees) simulate cap tables, understand dilution, and build equity literacy — fast.

> It's not just a calculator. It's a learning companion for startup ownership.

---

## 🎯 MVP Goal

Build a one-page, no-login tool where users can:

* Add multiple team members and SAFE investors
* Simulate a funding round
* See how ownership changes instantly (visually + numerically)
* Get a plain-English AI explanation of what just happened

---

## 👤 Target Audience

| Persona            | Motivation                                        |
| ------------------ | ------------------------------------------------- |
| First-time founder | Wants to understand dilution and equity splits    |
| Employee #3        | Curious what their shares could become worth      |
| University hacker  | Learning startup finance the fun way              |
| Angel investor     | Wants clarity on how SAFEs and rounds affect them |

---

## 🧠 Why This MVP Matters

CapTableGuru is the *Trojan Horse* that helps sell OpenCapStack by:

1. **Making the abstract feel real**
   Most people don't understand cap tables until they *see one change*. This tool makes equity visual, interactive, and learnable.

2. **Filtering for ideal clients**
   Users who play with CapTableGuru are clearly:

   * Equity-literate
   * Planning to raise
   * In need of full-stack cap table + compliance tools

3. **Creating a natural sales bridge**
   After a user sees how much equity they're giving away, the natural next step is:

   > "How do I formalize this?"
   > Answer: OpenCapStack.

4. **Enabling virality at the top of the funnel**
   Founders share what they see: screenshots, links, cap tables. Each share = new lead.

5. **Removing fear**
   It’s educational, free, and friendly. Which makes OpenCapStack feel like a helpful next step, not a heavy tool.

---

## 🔑 Key Features

### 1. Team Input (no auth)

* Add multiple team members (name + shares)
* Optional: ESOP pool entry (as %)
* Normalize % of total equity

### 2. SAFE & Round Entry

* Add 1 SAFE investor (amount + valuation cap)
* Add 1 priced round (amount + pre-money)
* Trigger dilution calculation

### 3. Visual Output

* Dynamic equity table
* Color-coded pie chart (responsive to changes)

### 4. ELI5 Explanations

* After every input, show “what just happened” in plain English
* Optional side panel: “Explain what I’m seeing”
* Hover tooltips: dilution, SAFE, valuation cap, etc.

### 5. AI Copilot

* Ask “What if I raise \$1M at \$5M pre-money?”
* Chat-style input box
* Markdown-style reply output

---

## 🚫 Non-Goals (for MVP)

* No authentication or user accounts
* No PDF/CSV export
* No versioning/sharing
* No multi-round logic
* No backend database (local state only)

---

## 🛠 Tech Stack (suggested)

* **Frontend:** React (with Tailwind CSS or Chakra UI)
* **Charting:** Recharts or Plotly
* **AI:** Claude or OpenAI via OpenRouter
* **Hosting:** Vercel, Netlify, or Streamlit (if Python MVP)

---

## ✅ Definition of Done

* Add multiple team members with shares
* Add 1 SAFE or 1 funding round
* See updated ownership instantly (chart + table)
* AI responds to cap table questions in plain English
* No login or backend needed
* Works on mobile + desktop
