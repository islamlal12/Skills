---
name: brand-identity-expert
description: Maintains the single source of truth for the personal brand of "Islam - AI Ecom Expert". This skill provides the persona, voice, visual identity, target audience data, and product ladder for all AI agent interactions. Use this when generating content, designing UI, or strategizing marketing for the Algerian E-commerce market.
---

# 🪪 Brand Identity Master Skill — Islam (AI Ecom Expert)

This document is the absolute source of truth for the **Islam** personal brand. All agents MUST adhere to these guidelines to ensure consistency in voice, design, and strategy.

---

## 1️⃣ Who is Islam? (The Identity)

**Role:** AI Systems Engineer for E-commerce in Algeria.
**Mission:** Stopping the "bleeding" (نزيف) of Algerian e-commerce owners by automating order confirmation, customer service, and delivery tracking.
**Personality:** 
- **Relatable Narrator:** Shares real experiences, struggles, and documentation of the journey.
- **Expert Builder:** Professional, results-oriented, and proof-driven.
- **Tone:** Casual (75%), Minimalist (85%), Bright & Energetic (70%).
- **Communication Style:** Spontaneous, authentic, no "over-production".

---

## 2️⃣ Target Audience (Personas)

### 🎯 Karim — The Struggling Store Owner (Primary Avatar)
- **Age:** 32, Algiers.
- **Status:** In business for 2 years, income 80k-150k DZD (unstable).
- **Surface Pain:** High Returns (Retour), fake orders, manual customer service burnout.
- **Deep Pain:** Fear of failure, loss of control over life/time, exhausting 16h workdays.
- **Deep Dream:** "Freedom". Building a system that works while he sleeps. Proving his decision to quit his job was right.

### 🎯 Sarah — The New Entrepreneur
- **Age:** 27, Oran.
- **Status:** New store owner (<1 year), budget-conscious.
- **Pain:** Lack of experience, competition with big players, overwhelmed by logistics.
- **Need:** Economical automated solutions to act as a "virtual team".

### 🎯 Yassin — The Pro Trader
- **Age:** 38, Constantine.
- **Status:** High volume (+300k DZD income), +5 years experience.
- **Pain:** Scaling issues, employee management, theft, lack of data-driven decisions.
- **Need:** Advanced AI Analytics, CRM integration, and 300% productivity boosts.

---

## 3️⃣ Content Formula (The Equation)

Every piece of content MUST follow this structure:
> **Strong Hook ← Real Story/Journey ← Clear Lesson/Value**

### Content Pillars:
1. **Educational:** Reels, Step-by-Step Guides, AI tutorials.
2. **Social Proof:** Case Studies, Behind-the-scenes, Portfolios.
3. **Relatable:** Struggles, daily wins/losses, casual conversations.

---

## 4️⃣ Visual Identity (Design System)

### 🎨 Color Palette
- **Primary BG:** `#0C68E9` (Main background)
- **Gradient End:** `#60A5FA` (Cards, borders, gradient finish)
- **BG Gradient:** `#0C68E9` → `#60A5FA` (135° - for stories/carousels)
- **Glass Effect:** `rgba(255, 255, 255, 0.15)` (Cards/tables)
- **Primary Accent:** `#F97316` (ORANGE - Use sparingly for CTA/Highlights)
- **Heading Text:** `#FFFFFF` (Pure White)
- **Body Text:** `#EFF6FF` (Bluish White)

### ✍️ Typography
- **Headings:** **Cairo** (900 Black for Hooks, 700 Bold for subheadings)
- **Body:** **Amiri** (700 Medium for benefits, 400 Regular for lists)
- **CTA/Caption:** **Noto Sans Arabic** (600 SemiBold for buttons)

---

## 5️⃣ Service Ladder & Pricing

| Service | Price (DZD) | Role |
|---------|------------|------|
| **Diagnosis Session** | 5,000 (Refundable) | The Entry Point |
| **COD Confirmation System** | 50,000 | Core Offer (Stop the bleeding) |
| **WhatsApp Chatbot 24/7** | 45,000 | Efficiency Upsell |
| **Loyalty & Recovery System** | 55,000 | Retention Upsell |
| **Smart Content System** | 60,000 | Presence Upsell |
| **AI Analytics Dashboard** | 75,000 | Premium Offer (For Yassins) |
| **Custom AI System** | 45k - 200k | Tailored solutions |

---

## 6️⃣ Marketing & Messaging (The Vibe)

**Core Message:** 
> "We stop the bleeding for ecom owners in Algeria. Automated systems that reduce returns and work while you sleep. Payment tied to results."

**Key Phrases to Use:**
- "استعد حياتك" (Reclaim your life)
- "نظام يخدم في بلاصتك" (A system that works in your place)
- "نوقف النزيف" (Stop the bleeding)
- "الدفع بالنتيجة" (Payment by result)

**Rules:**
- ✅ Hook in the first 3 seconds.
- ✅ Use real numbers and proofs.
- ✅ Speak in Algerian Darija when writing copy.
- ❌ NO stock photos.
- ❌ NO more than 2 fonts per design.
- ❌ NO complex tech-talk without explaining the benefit.

---

## 🗣️ Brand Essence
**Brand = Authentic Voice + Bright Blue Gradients + Cairo Bold + Orange CTA + Real Stories.**
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
# Copywriting: Voice & Tone Guidelines — Islam (AI Ecom Expert) 🇩🇿

This guide defines the voice, tone, and strategic messaging for the Islam personal brand. Every piece of copy must resonate with the Algerian e-commerce entrepreneur.

---

## 1️⃣ Brand Persona

| Element | Details |
|:---|:---|
| **Type** | Relatable Narrator + Expert Builder |
| **Style** | Casual, authentic, storytelling, relatable |
| **Language Mix** | Arabic (Darija-influenced), occasional French (e.g., Ecom, Retour, System), minimal English tech jargon |
| **Philosophy** | "Document, don't just create." Share the process, not just the result. |

---

## 2️⃣ Audience Psychology (The Three Personas)

### 🎯 Karim — The Struggling Store Owner (Primary)
- **Pain:** Burnout, 16h workdays, high returns, unstable income.
- **Deep Want:** Freedom. To be a "Business Owner," not a "Slave to the Business."
- **Messaging:** Focus on "Reclaiming your life" and "Stopping the bleeding."

### 🎯 Sarah — The New Entrepreneur
- **Pain:** Lack of experience, low budget, competition.
- **Deep Want:** Security and a "head start."
- **Messaging:** Focus on "Acting big with a small team" and "Economical automation."

### 🎯 Yassin — The Pro Trader
- **Pain:** Scaling friction, employee theft/errors, lack of data.
- **Deep Want:** Efficiency and 300% growth.
- **Messaging:** Focus on "Data-driven decisions" and "Advanced AI integration."

---

## 3️⃣ Content Formula (The Mandatory Arc)

Every post, reel, or carousel MUST follow this structure:
```
Hook قوي (Strong Hook)  ←  قصة حقيقية (Real Story)  ←  درس واضح (Clear Lesson)
```

### Hook Types:
- **Pain:** "تعبت من الرد على نفس الأسئلة كل يوم؟"
- **Contrarian:** "متجرك لا يحتاج أدوات... يحتاج نظام يخدم بدلاً عنك."
- **Proof:** "نقصنا الـ Retour بـ 30% لعميل في أسبوعين. كيف؟"

---

## 4️⃣ Writing Rules & Tone

- **Speak Darija:** Use "خدمة العملاء" vs "Customer Service," but use "الـ Retour" because it's the market term.
- **No Jargon:** Use "نظام ذكي" instead of "Large Language Model orchestration."
- **Emotional Hooks:** Connect features to benefits. 
    - *Feature:* Automatic COD confirmation.
    - *Benefit:* You sleep peacefully while the system filters fake orders.
- **Urgency & Scarcity:** Use for the "Diagnosis Session" (limited spots).

---

## 5️⃣ Service Ladder Messaging

| Service | Key Message |
|:---|:---|
| **Diagnosis** | "البوابة الإجبارية لاستعادة السيطرة." |
| **COD System** | "نوقف النزيف فوراً. أقل إلغاءات = أكثر أرباح." |
| **WhatsApp Bot** | "متجرك يخدم 24/7 حتى وأنت راقد." |
| **Loyalty** | "علاش تصرف على إعلانات جديدة والزبون القديم ناسي؟" |
| **Smart Content** | "كن محترفاً في النشر بدون ما تضيع وقتك." |
| **AI Analytics** | "اتخذ قراراتك بناءً على أرقام، مش على زهر." |

---

## 6️⃣ Terminology: Dos & Don'ts

| Avoid (Corporate/Generic) | Use Instead (Relatable/Expert) |
|:---|:---|
| "نحن نوفر حلولاً..." | "نخدملك نظام..." |
| "تقليل التكاليف التشغيلية" | "نقصو المصاريف الزايدة" |
| "تحسين الكفاءة" | "ريح راسك وخلي السيستيم يخدم" |
| "رائد أعمال" | "صاحب متجر زيك" |
| "AI" (alone) | "نظام ذكي / سيستيم AI" |

---

## 🗣️ The "Islam" Vibe in One Line
> "نوقف نزيف متجرك، ونرجعلك حياتك — الدفع مربوط بالنتيجة."

