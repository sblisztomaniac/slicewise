# 🚀 SliceWise – 5-Hour MVP Sprint Plan

Build a fully working MVP for **SliceWise** — a visual cap table simulator for non-finance startup founders. This sprint breaks down hour-by-hour deliverables to build and test the full UI with no auth and client-only state.

---

## 🛠️ Tech Stack

* **Frontend**: React + Tailwind CSS
* **Charts**: Recharts (Pie Chart)
* **AI**: Claude or GPT via OpenRouter (Copilot)
* **Hosting**: Local / Vercel (post-sprint)

---

## 🎯 Definition of Done (DoD)

* Add multiple founders with shares
* Add 1 SAFE investor
* See ownership %s and live pie chart
* Ask AI “What happened?” and get ELI5 explanation
* No backend, no login, all local state
* Mobile-responsive and clean UI

---

## ⏱️ Sprint Breakdown – 5 Hours

### 🔹 Hour 1: Project Setup + Hero UI

**Goal**: Create clean entry point and emotional trust

* [ ] Set up React + Tailwind project
* [ ] Create `App.jsx` layout
* [ ] Build hero section:

  * Title: SliceWise
  * Subheadline
  * CTA: \[Start My Cap Table]
  * 3-step guide below
* [ ] Add mobile responsiveness

✅ **Checkpoint**: Hero page loads, CTA works, brand feels safe + friendly

---

### 🔹 Hour 2: Team + SAFE Inputs

**Goal**: Enter team and funding info

* [ ] Build founders input table:

  * Name + Shares
  * \[Add Founder] button
* [ ] Create optional SAFE input block:

  * Name + Amount + Valuation Cap
* [ ] Store inputs in useState arrays
* [ ] Validate entries, normalize shares

✅ **Checkpoint**: Users can add Nova + SAFE investor, values stored and reactive

---

### 🔹 Hour 3: Cap Table Output + Pie Chart

**Goal**: Visualize ownership

* [ ] Build cap table view

  * Columns: Name, Shares, % Ownership
* [ ] Add live pie chart (Recharts)

  * Use color-coded slices
* [ ] Recompute shares and % on input change
* [ ] Auto-scroll or reveal output below inputs

✅ **Checkpoint**: Pie + table update live, ownership is clear

---

### 🔹 Hour 4: AI Copilot + Tooltip System

**Goal**: Answer questions & embed learning

* [ ] Add input box: “Ask about your cap table…”
* [ ] Create system prompt for Claude/GPT:

  > "You are SliceWise, a friendly AI cap table coach. Explain dilution and equity in ELI5 language."
* [ ] On submit:

  * Serialize cap table JSON + question
  * Call OpenRouter, return markdown reply
* [ ] Add tooltip overlay for terms:

  * "SAFE ❓", "Dilution ❓"

✅ **Checkpoint**: Ask AI and get explanation like “You now own 62.5%. The investor owns 37.5%.”

---

### 🔹 Hour 5: Learn Mode + Polish + Sample Loader

**Goal**: Add friendly UX and finish MVP polish

* [ ] Sticky/collapsible Learn Sidebar:

  * Show last explanation or tooltip message
* [ ] Add \[Clear Table] and \[Load Sample Scenario] buttons
* [ ] Mobile cleanup
* [ ] Clean spacing, copy, and final touches

✅ **Final Checkpoint**: MVP done, testable, shareable, educational

---

## 📦 Deliverables

* Working MVP in `captable_frontend/`
* One-click sample load (Nova + SAFE)
* Clean AI Copilot thread
* All ELI5 tooltips active
* Optional: deploy to Vercel and record walkthrough
