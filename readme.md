# VoiceFunnel AI™

> **Turn your website into 1,000 warm voicemails.**

VoiceFunnel AI™ is an AI-powered voicemail funnel engine for service businesses and agencies.  
Paste a business website URL, and VoiceFunnel AI™:

1. Scans the site to understand the offer, location, and tone  
2. Writes a natural 30–40 second voicemail script  
3. Separates and highlights a clear, editable **offer line**  
4. (Planned) Generates audio and sends ringless voicemail campaigns to targeted prospect lists  
5. (Planned) Builds matching SMS/email copy so callbacks land in a consistent mini funnel  

This repo currently focuses on the **marketing/landing page** (`index.html`) that explains the product and collects early access leads.

---

## Core Concept

**VoiceFunnel AI™** is built for:

- Service businesses who want more callbacks without manual cold calling  
- Agencies who want a repeatable voicemail + follow-up funnel they can deploy for clients  

Instead of forcing users to write and record their own pitch, VoiceFunnel AI™ starts from the **business website** and does the heavy lifting:

- **Website → Script**: AI writes the voicemail  
- **Script → Offer**: A dedicated offer line is extracted and editable  
- **Offer → Funnel**: (Planned) Matching SMS and email follow-ups are generated from the same offer  

---

## Current Features (Landing Page)

The current `index.html` includes:

### 🎯 Hero Section

- Product branding for **VoiceFunnel AI™**
- Headline & subheadline explaining the core promise
- A **URL input box** to “Paste your website and generate a voicemail script” (front-end only for now)
- Primary CTAs:
  - **Generate Voicemail Script** (placeholder)
  - **Join Early Access**
  - **Watch Demo** (placeholder)

### 📊 App Preview Card (Mock UI)

A right-side visual that simulates the future app experience:

- Example campaign (“Local Acupuncture – Pain Relief Offer”)
- AI voicemail script preview block (with offer line highlighted)
- Simple metrics:
  - Drops sent
  - Callbacks
  - Qualified leads
- Short explainer showing VoiceFunnel’s role in writing, voicing, and scoring campaigns

### 🧩 Feature Grid

Six feature cards describing the intended product:

1. **Website → Script in one step**  
   Paste a URL and get an AI-written voicemail script with a clear, editable offer line.

2. **AI voices that sound human** *(planned)*  
   Clone the owner’s voice or use a natural AI voice to turn the script into audio.

3. **Ringless voicemail campaigns** *(planned)*  
   Upload or connect a lead list and send voicemails at scale without manual dialing.

4. **Offer-aware mini funnel** *(planned)*  
   Generate matching SMS and email follow-ups from the same offer.

5. **Callback insights, not just delivery stats** *(planned)*  
   Track callbacks and use AI summaries to understand lead quality.

6. **Built for ethical, respectful outreach** *(planned)*  
   Quiet hours, frequency limits, and friendly opt-out language.

### 📬 Early Access CTA

A dedicated section for:

- Short pitch for early adopters (agencies + service businesses)
- Email input + “Join Early Access” button (front-end only for now)

### 🦶 Footer

- Simple footer with:
  - Dynamic current year
  - “A NOFA AI Factory™ invention” credit line
  - Placeholder links for Terms / Privacy

---

## Tech Stack (Current)

Right now the project is a **static landing page**:

- **HTML5**
- **Tailwind CSS** via CDN

No build tools, frameworks, or backend are required at this stage. You can open `index.html` directly in a browser or host it on any static hosting provider (e.g., Vercel, Netlify, S3).

---

## Project Status

- **Status:** Not Started (core product) / Landing page prototype ready  
- **Stage:** Idea

What exists now:

- A polished `index.html` that:
  - Explains VoiceFunnel AI™
  - Shows the website → script → voicemail concept
  - Captures emails for early access (UI only)

What’s planned (not implemented yet):

- Backend API: `/api/generate-voicemail-script`  
- AI integration to:
  - Fetch website content
  - Summarize the business
  - Generate voicemail script + offer line  
- Voice generation & ringless voicemail delivery integration  
- Callback tracking & analytics dashboard  
- Ethical outreach guardrails (quiet hours, frequency caps, opt-out language)

---

## Getting Started (Landing Page Only)

1. **Clone or download** this project.
2. Open `index.html` in your browser.
3. Customize:
   - Headlines, copy, and example campaign text
   - Branding (logo initials, colors, etc.)
   - Early access form action (when backend/Email service is ready)

To host it on **Vercel**:

1. Create a new GitHub repo and push `index.html`.
2. Create a new Vercel project connected to that repo.
3. Deploy with default static-site settings.

---

## Roadmap (High-Level)

1. **Brick 1 – Landing & Early Access**
   - ✅ `index.html` marketing page
   - ☐ Wire early access form to a backend (e.g., Firebase, Supabase, simple API)

2. **Brick 2 – Website → Script Engine**
   - ☐ `/api/generate-voicemail-script` endpoint
   - ☐ Front-end section for script + editable offer line

3. **Brick 3 – Voice & Campaigns**
   - ☐ Voice cloning / AI voice integration
   - ☐ Ringless voicemail provider integration
   - ☐ Campaign creation & scheduling UI

4. **Brick 4 – Funnel & Insights**
   - ☐ SMS/email follow-up generation
   - ☐ Callback tracking, summaries, and quality scoring  
   - ☐ Dashboard metrics and basic ROI view

---

## License

TBD – choose and add a license once the repo is created (e.g., “All rights reserved” for proprietary NOFA AI Factory™ code or a standard open-source license if desired).
