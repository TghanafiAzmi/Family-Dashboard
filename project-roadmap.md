# 🏠 Family Split-Bill Dashboard
A chapter-based roadmap to complete the project step by step.

---

# 📘 CHAPTER 1 — Project Foundation

## 🎯 Goal
Set up a clean and professional development environment.

## ✅ Tasks
- [ ] Create Next.js project (TypeScript + App Router + ESLint + Tailwind)
- [ ] Configure import alias (`@/`)
- [ ] Set up folder structure
- [ ] Remove default template content
- [ ] Create base layout (sidebar + topbar placeholder)
- [ ] Verify dev server runs successfully

## 🏁 Result
Structured blank dashboard ready for development.

---

# 📘 CHAPTER 2 — UI Skeleton (No Database Yet)

## 🎯 Goal
Build static dashboard UI before connecting backend.

## ✅ Tasks
- [ ] Create Layout component
- [ ] Create Sidebar navigation
  - Dashboard
  - Utilities
  - Contributions
  - Summary
- [ ] Create pages:
  - `/dashboard`
  - `/utilities`
  - `/contributions`
  - `/summary`
- [ ] Create reusable components:
  - Card
  - Table
  - Button
- [ ] Use dummy/mock data for testing

## 🏁 Result
Fully navigable dashboard with static data.

---

# 📘 CHAPTER 3 — Supabase Setup (Backend)

## 🎯 Goal
Connect frontend to real database.

## ✅ Tasks
- [ ] Create Supabase project (free tier)
- [ ] Create database tables:
  - `people`
  - `utilities`
  - `contributions`
- [ ] Add environment variables (`.env.local`)
- [ ] Create `supabaseClient.ts`
- [ ] Test database connection

## 🏁 Result
Frontend connected to live database.

---

# 📘 CHAPTER 4 — Utilities Module (CRUD)

## 🎯 Goal
Allow admin to manage monthly bills.

## ✅ Tasks
- [ ] Fetch utilities from database
- [ ] Create Add Utility form
- [ ] Insert utility into database
- [ ] Edit utility
- [ ] Delete utility
- [ ] Add month/year filter

## 🏁 Result
Admin can fully manage bills.

---

# 📘 CHAPTER 5 — Contributions Module (CRUD)

## 🎯 Goal
Track who paid what.

## ✅ Tasks
- [ ] Fetch contributions
- [ ] Add contribution form
- [ ] Link contribution to person
- [ ] Edit contribution
- [ ] Delete contribution
- [ ] Add month/year filter

## 🏁 Result
Payment tracking system working.

---

# 📘 CHAPTER 6 — Calculation Engine

## 🎯 Goal
Implement split-bill logic.

## ✅ Tasks
- [ ] Calculate total utilities
- [ ] Calculate total contributions
- [ ] Calculate expected share per person
- [ ] Calculate balance per person:
      Balance = Paid - Expected Share
- [ ] Identify:
      - Who owes money
      - Who overpaid

## 🏁 Result
Accurate financial breakdown per month.

---

# 📘 CHAPTER 7 — Dashboard Summary Page

## 🎯 Goal
Make data visual and user-friendly.

## ✅ Tasks
- [ ] Create summary cards:
  - Total Utilities
  - Total Paid
  - Balance
- [ ] Display per-person balance table
- [ ] Add charts:
  - Monthly expense trend
  - Contribution comparison
- [ ] Improve layout responsiveness

## 🏁 Result
Professional dashboard interface.

---

# 📘 CHAPTER 8 — Read-Only Family View

## 🎯 Goal
Allow family members to view but not edit.

## ✅ Tasks
- [ ] Hide edit/delete buttons
- [ ] Disable forms
- [ ] Create view-only route or mode
- [ ] Share deployed link

## 🏁 Result
Safe view-only dashboard access.

---

# 📘 CHAPTER 9 — Receipt Upload (Optional)

## 🎯 Goal
Store proof of bills.

## ✅ Tasks
- [ ] Create Supabase storage bucket
- [ ] Upload receipt image
- [ ] Save receipt URL in database
- [ ] Display receipt preview

### 🔥 Optional Advanced
- [ ] Implement OCR auto-detection for amount

## 🏁 Result
Bills stored with digital proof.

---

# 📘 CHAPTER 10 — Deployment

## 🎯 Goal
Make the dashboard live.

## ✅ Tasks
- [ ] Push project to GitHub
- [ ] Deploy to Vercel (free tier)
- [ ] Add production environment variables
- [ ] Test production build

## 🏁 Result
Live working dashboard accessible online.

---

# 🚀 Recommended Build Order

1 → 2 → 3 → 4 → 5 → 6 → 7 → 10  
Then add optional features (8 & 9).

---

# 🎯 Final Outcome

✔ Single Admin Dashboard  
✔ Real Monthly Bill Splitting  
✔ Per-Person Balance Calculation  
✔ Charts & Summary  
✔ Free Hosting + Free Database  
✔ Clean Professional Structure  

---

**Project Status:** 🟡 In Development  
**Version:** v1.0 (MVP Focus)