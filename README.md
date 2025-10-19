# AEO (AI-Search Visibility) Tracker

[![Deploy with Vercel](https://vercel.com/button)](https://aeo-tracker-2j9ec0gev-raphels-projects.vercel.app/login)

A full-stack application built with Next.js and Supabase to track a brand's visibility within AI search engine answers. This project was developed as a take-home assignment for the Full-Stack Developer role at Icecreamlabs.

---

## 🚀 Live Demo

**URL:** [https://aeo-tracker-2j9ec0gev-raphels-projects.vercel.app/login](https://aeo-tracker-2j9ec0gev-raphels-projects.vercel.app/login)

**Test Credentials:**
* **Email:** `test@example.com`
* **Password:** `password123`

---

## ✨ Key Features

* **User Authentication:** Secure sign-up and login handled by Supabase Auth.
* **Multi-Tenant Projects:** Users can create projects and add keywords to track, with data secured by Postgres Row-Level Security (RLS).
* **Visibility Checks:** Simulates checks against AI engines (Gemini, ChatGPT, Perplexity) and stores historical performance data.
* **On-Demand Scans:** Users can trigger new checks at any time via a dedicated API route (`/api/checks/run`).
* **Interactive Dashboard:**
    * Displays high-level KPIs (Visibility Score, Average Position, etc.).
    * Visualizes performance trends over time using Recharts.
    * Provides a detailed breakdown of visibility by keyword and engine.
* **AI-Powered Recommendations:** Uses simple heuristics to provide actionable advice for improving visibility.
* **Seed Script:** Includes a script to populate the database with realistic demo data for a sample project.

---

## 🛠️ Tech Stack

* **Framework:** Next.js 14 (App Router, Server Components)
* **Language:** TypeScript
* **Styling:** Tailwind CSS
* **UI Components:** Tremor
* **Database & Auth:** Supabase (Auth, Postgres, RLS, RPCs)
* **Data Visualization:** Recharts
* **Scripting:** `tsx` for Node.js scripts

---

## ⚙️ Local Development Setup

### 1. Prerequisites
* Node.js (v18 or later)
* A Supabase project

### 2. Clone the Repository
```bash
git clone [https://github.com/Haindavi3009/Aeo-Tracker.git](https://github.com/Haindavi3009/Aeo-Tracker.git)
cd Aeo-Tracker
