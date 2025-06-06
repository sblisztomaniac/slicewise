# 📋 SliceWise – MVP Backlog

This backlog outlines all actionable tasks derived from the 5-hour MVP sprint plan for **SliceWise**, organized by feature group and priority.

---

## 🧭 Epic 1: Hero Page + Onboarding

### ✅ User Story: As a first-time visitor, I want to understand what SliceWise is and how to start

* [ ] Set up React + Tailwind base project
* [ ] Build hero section with:

  * [ ] Title and subheadline
  * [ ] CTA: "Start My Cap Table"
  * [ ] 3-step explainer (Add → Simulate → Understand)
* [ ] Ensure mobile responsiveness

---

## 🧍 Epic 2: Team & SAFE Input System

### ✅ User Story: As a founder, I want to add my team and a SAFE investor

* [ ] Build team input block

  * [ ] Name + Shares input fields
  * [ ] \[Add Founder] button
* [ ] Build SAFE input block

  * [ ] Investor name
  * [ ] Amount
  * [ ] Valuation cap
* [ ] Store inputs in React state
* [ ] Add basic validation + share normalization

---

## 📊 Epic 3: Cap Table Visual Output

### ✅ User Story: As a user, I want to see the ownership breakdown live

* [ ] Build cap table view:

  * [ ] Name, Shares, % Ownership
* [ ] Add dynamic pie chart (Recharts)

  * [ ] Color-coded slices
* [ ] Recompute % ownership on input change
* [ ] Auto-render or scroll to visualization

---

## 🤖 Epic 4: AI Copilot + Tooltips

### ✅ User Story: As a non-finance founder, I want AI to explain what happened in plain English

* [ ] Add text input box for user questions
* [ ] Preload sample prompts (e.g., "What happens if I raise \$1M?")
* [ ] Inject cap table state + user query into Claude/OpenAI
* [ ] Show markdown-style AI replies clearly
* [ ] Build tooltip system for:

  * [ ] SAFE ❓
  * [ ] Dilution ❓
  * [ ] Shares ❓
  * [ ] Valuation cap ❓

---

## 📘 Epic 5: Learn Mode + MVP Polish

### ✅ User Story: As a learner, I want to get guidance at each step and try a sample

* [ ] Build collapsible or sticky "Learn Sidebar"

  * [ ] Display last explanation or inline coaching
* [ ] Add \[Clear Table] button
* [ ] Add \[Load Sample Scenario] button

  * [ ] Preload Nova + SAFE investor
* [ ] Final mobile tweaks and layout polish

---

## 🧪 Bonus (Post-MVP)

* [ ] Add ESOP pool support
* [ ] Enable export as image or CSV
* [ ] Save/share cap table snapshots
