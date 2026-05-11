# Preferred Tech Stack & Implementation Rules — Islam (AI Ecom Expert)

This document defines the technical standards for developing AI systems, UI components, and automation workflows for the brand.

---

## 🛠️ Core Tech Stack

| Layer | Technology |
|:---|:---|
| **Frontend Framework** | React / Next.js (App Router) |
| **Styling Engine** | Tailwind CSS (Mandatory) |
| **UI Components** | shadcn/ui + Lucide Icons |
| **Animations** | Framer Motion (Micro-animations) |
| **Automation & Logic** | **n8n** (Primary Orchestration) |
| **Communication** | **WhatsApp Business API** |
| **Data Storage** | **Notion** (Primary Database / CRM) |
| **Analytics** | Python (Pandas/Matplotlib) |

---

## 🎨 Design Implementation Rules

### Colors (Always Reference `design-tokens.json`)
- **Background:** Always start with gradient `#0C68E9` → `#60A5FA` at 135°.
- **Headings:** `#FFFFFF` (Pure White).
- **Body Text:** `#EFF6FF` (Bluish White).
- **CTA / Accent:** `#F97316` (ORANGE) — **Sparingly: 2–3 highlights MAX.**
- **Glass Cards:** `rgba(255, 255, 255, 0.15)` with `backdrop-filter: blur(10px)`.

### Typography (RTL-First)
- **Hooks:** Cairo (900 Black).
- **Body:** Amiri (400 Regular / 700 Bold).
- **CTA:** Noto Sans Arabic (600 SemiBold).
- **Direction:** Always use `dir="rtl"` for Arabic content.

---

## ⚙️ Development Guidelines

### 1. Automation with n8n
- Build modular workflows for COD confirmation, customer service, and lead capture.
- Integrate with WhatsApp API for real-time customer interaction.
- Sync all data to Notion for transparency with the client.

### 2. UI/UX Patterns
- **Glassmorphism:** Use glass cards for dashboards and data tables.
- **Micro-interactions:** Add subtle hover effects on CTAs using Framer Motion.
- **Performance:** Optimize for mobile (Algerian users are mobile-first).

---

## 🚫 Forbidden Patterns

- ❌ NO jQuery or Bootstrap.
- ❌ NO hardcoded hex values outside the brand palette.
- ❌ NO non-responsive designs.
- ❌ NO complex tech jargon in user-facing dashboards.
- ❌ NO more than 2 font families per design.
