# 📄 Sandikodev Selected Projects Portfolio

> **Tagline**: From SaaS Intelligence to Institutional Platforms — Built for Production.

---

## 👤 About

**Sandikodev** — Fullstack Developer & System Architect  
PT Koneksi Jaringan Indonesia | Jakarta, Indonesia

I build web applications that are clean, scalable, and production-ready from day one.
My focus: SaaS platforms, institutional systems, and developer tooling.

**Stack**: React · Next.js · SvelteKit · Astro · Bun · Turso · Drizzle · Hono · TypeScript

---

---

## PROJECT 1 — MARGIN PRO
### Intelligence Pricing System for F&B Businesses

**Type**: SaaS Platform  
**Status**: Production  
**Stack**: `Koda Zenith` · `React 19` · `Hono` · `Turso` · `Drizzle` · `Tailwind CSS v4` · `Bun`

### The Problem
Indonesian F&B micro-businesses were losing profit margins silently. They had no clear way to calculate Cost of Goods Sold (COGS), simulate margins across delivery apps (GoFood, GrabFood, ShopeeFood), or understand the true net profit after platform commissions.

### The Solution
Margins Pro is a SaaS pricing intelligence platform that:
- Calculates COGS down to the smallest ingredient unit
- Simulates real profit margins per delivery platform commission
- Provides AI-driven pricing recommendations via Google Gemini Flash 2.0

### Architecture Highlights
- **Dual-Mode SSR Engine** (Koda Zenith): Zero-flicker page loads with Resumable Mode
- **Local + Cloud Sync**: Optimistic UI with background Turso synchronization
- **End-to-end Type Safety**: TypeScript strict + Hono RPC contract

### Result
A production-ready SaaS that helps F&B entrepreneurs avoid losses and price their products with precision.

---

---

## PROJECT 2 — AKSESEKOLAH.ID
### School Website Builder & Academic Management System

**Type**: Institutional Platform (Open Source)  
**Status**: Production  
**Stack**: `Next.js 16` · `Headless WordPress` · `Prisma` · `LibSQL` · `Radix UI` · `Tailwind CSS`

### The Problem
Indonesian schools needed modern digital presence and academic management tools but lacked the budget for enterprise software. Most solutions were either too expensive or too technical for non-developer staff.

### The Solution
Aksesekolah is an open-source platform offering:
- School website builder with customizable themes
- Multi-role academic management (Admin, Teacher, Student, Parent)
- Student enrollment, attendance, and grade tracking
- Integration with existing school information systems

### Architecture Highlights
- **Hybrid Architecture**: Next.js for fast frontend + Headless WordPress for CMS flexibility
- **Multi-tenant**: Each school gets isolated data and custom domain
- **Type-safe Data Layer**: Prisma Client + Zod validation throughout

### Result
A platform trusted by educational institutions for managing academic workflows with a clean, modern interface.

---

---

## PROJECT 3 — SIGMABOT PLATFORM
### IoT & Robotics E-Learning with Hardware Bundles

**Type**: E-Learning Platform  
**Status**: Production  
**Stack**: `Astro 5` · `React 19` · `Better Auth` · `Turso` · `Drizzle` · `Midtrans` · `Tailwind CSS v4`

### The Problem
IoT and Robotics learning is fragmented — theory happens online, practice requires physical hardware purchased separately. Learners struggle to bridge the gap between concepts and hands-on implementation.

### The Solution
SigmaBOT bundles hardware kits (Arduino, ESP32, Raspberry Pi) with lifetime course access:
- Hardware-first learning model: buy a kit, unlock its full course
- Rich interactive modules (Mermaid diagrams, KaTeX math, code blocks)
- Aura Points gamification system for engagement
- Integrated payment (Midtrans) and authentication (Google OAuth via Better Auth)

### Architecture Highlights
- **Islands Architecture** (Astro 5): Static pages with selective React hydration for maximum performance
- **Edge Database**: Turso + Drizzle for sub-millisecond data access
- **Comic Book UI Design**: Bold visual identity with 4px borders and halftone patterns

### Result
A unique e-learning platform combining physical product sales with digital education delivery.

---

---

## ⚙️ Technical Standards Applied Across All Projects

| Standard | Implementation |
| :--- | :--- |
| **Type Safety** | TypeScript Strict + ORM/RPC contracts |
| **Database** | Edge SQLite (Turso) + Drizzle ORM |
| **Authentication** | Better Auth / NextAuth / Custom sessions |
| **Deployment** | Vercel / Cloudflare Pages / GitHub Pages |
| **Testing** | Playwright (E2E) + Vitest (Unit) |
| **CI/CD** | GitHub Actions |

---

## 📬 Contact

**GitHub**: github.com/sandikodev  
**Fiverr**: fiverr.com/sandikodev  
**Company**: PT Koneksi Jaringan Indonesia

---
*Portfolio prepared for Fiverr Gig presentation.*
