# KaamSetu — Beyond the Waiting Line
> **"Your skills deserve opportunities."** / **"आपके हुनर को मिले सही काम।"** / **"तुमच्या कौशल्याला मिळो योग्य संधी."**

A mobile-first web application connecting informal workers, skilled tradespeople, daily-wage labourers, and employers with dignity, transparency, and accessibility.

Built for the hackathon problem statement: *"Beyond the Waiting Line: Connecting Hawkers to Better Employment Opportunities."*

---

## 🌟 Key Features

### 1. Dual Connected Experience (Worker & Employer)
- **Worker Journey**:
  - Welcome experience with zero-barrier demo exploration.
  - Progressive 4-step onboarding (no formal résumé or certificates demanded).
  - Signature Worker Home Screen with real-time location selection, "Available Today" toggle, search & filter by distance, trade, and wage.
  - Detailed Job Specifications with **Neutral Wage Comparison Widget** comparing employer rates with worker expectations without pressure.
  - Anti-duplicate application flow with celebration and direct tracking.
  - **My Work**: 3-stage tracker (*Applied*, *Confirmed & Ongoing*, *Completed & Paid*) with authentic settlement tracking.
  - **Worker Profile**: Skills credentials, photo gallery of past work, and verified client feedback.
  - **Rights & Welfare Schemes**: Verified Indian welfare schemes (*e-Shram*, *PM-SVANidhi*, *BOCW Welfare Board*, *Ayushman Bharat PM-JAY*, *PM-SYM Pension*), document checklists, official links, and national labour helplines (14434).

- **Employer Journey**:
  - Employer hiring hub with active job metrics, applicant counts, and shortlist tallies.
  - Multi-step **Post a Job** wizard with real-time worker view preview.
  - **Find Workers Directory**: Filterable by trade, minimum experience, and daily wage with instant shortlisting.
  - **Applicant & Job Management**: Review applicant profiles, shortlist, contact via simulated phone/WhatsApp, and hire candidates (instantly updating the worker's *My Work* to confirmed status!).

### 2. Multilingual Accessibility
- Full UI translations for **English**, **Hindi (हिन्दी)**, and **Marathi (मराठी)**.
- Every label, button, modal, error message, and scheme is translated into human-reviewed vernacular.
- Persisted locally across sessions.

### 3. Elderly-Friendly Mode
- High-contrast visual scheme with deep forest green borders (`#244D3B`).
- Increased base font size (20px) and headings (28–34px).
- Generous touch targets (60px+) and simplified controls.
- Reduced decorative motion and audio read-aloud buttons.

### 4. Voice Assistance & Text-To-Speech (TTS)
- Web Speech API voice search supporting `en-IN`, `hi-IN`, and `mr-IN`.
- Natural intent parsing for trades (e.g. *"Mala javal electrician cha kaam pahije"*, *"Mujhe paas mein plumber ka kaam chahiye"*).
- Graceful fallback with editable text input if microphone permissions are denied.
- Built-in Text-To-Speech audio buttons on job listings, welfare schemes, and welcome greetings.

### 5. Pastel-Yellow Design Tokens
- Primary background: `#FFF9E9`
- Warm cream surface: `#FFFDF6`
- Pastel yellow: `#FFE8A3`
- Primary yellow: `#FFC94A`
- Deep forest green: `#244D3B`
- Muted green: `#E1F0E4`
- Soft peach accent: `#F8D7BD`
- Primary text: `#27352E`
- Secondary text: `#68736A`
- Borders: `#E8E0CF`
- Error background: `#FBE7E2`, text: `#8C2F24`

---

## 🚀 Running Locally

```bash
# Install dependencies
npm install

# Start Vite development server
npm run dev

# Build production bundle
npm run build
```

The application runs on `http://localhost:5173/`.

