# JobTrackr Pro — Chrome Web Store Submission Package

---

## 1. STORE LISTING COPY

### Extension Name
JobTrackr Pro — Job Application Tracker

### Short Description (132 chars max)
Track job applications, auto-detect jobs from listings, AI resume builder & follow-up emails. Built for foreign job seekers.

### Detailed Description
---
🌏 Built for international job seekers — especially those navigating work pass sponsorship in Singapore.

JobTrackr Pro is your all-in-one job application tracker that lives in your browser. Never lose track of an application again.

─── CORE FEATURES ───────────────────────────

📋 SMART APPLICATION TRACKING
• Log every application with status, date, company, role, and location
• Track Employment Pass (EP), S Pass, Tech.Pass sponsorship status per company
• Star and prioritise your favourite applications
• Dashboard with pipeline overview and interview rate stats
• Kanban board view to visualise your job hunt

🔍 AUTO-DETECT FROM JOB LISTINGS
Open a job listing on LinkedIn, Indeed, JobStreet, MyCareersFuture, or Glassdoor — JobTrackr automatically reads the role, company, and location so you can save it in one click.

✦ AI RESUME BUILDER (Pro)
• Generate a full ATS-optimised resume from scratch
• Tailor your existing resume to any job description
• Optimised for the Singapore job market
• Powered by Claude AI

✉ FOLLOW-UP EMAIL AUTOMATION
• 4 ready-to-send email templates: initial follow-up, post-interview thank you, visa sponsorship enquiry, gentle nudge
• AI-personalised emails that reference your specific application details
• Open directly in your mail app with one click

🛂 VISA & WORK PASS TRACKER
• Track EP / S Pass / Tech.Pass sponsorship status per application
• Built-in Singapore work pass salary reference guide
• Know at a glance which companies will sponsor you

─── SUPPORTED JOB SITES ─────────────────────
✅ LinkedIn
✅ Indeed / sg.indeed.com
✅ Glassdoor
✅ JobStreet / SEEK
✅ MyCareersFuture (Singapore)
✅ Any site with structured job data

─── PRIVACY ─────────────────────────────────
All your data is stored locally in your browser. Nothing is sent to any server except Anthropic's API (only when you use AI features, with your own API key). We never sell or share your data.

─── FREE vs PRO ─────────────────────────────
FREE: Unlimited application tracking, auto-detect, email templates, visa tracker
PRO: AI resume builder, AI-personalised emails, URL job extraction

---

### Category
Productivity

### Language
English

### Tags / Keywords
job tracker, job application, resume builder, job search, career, Singapore, employment pass, work pass, follow-up email, LinkedIn

---

## 2. STORE LISTING ASSETS NEEDED

### Icons (you need to upload)
- 128x128 PNG icon (already in extension/icons/icon128.png)

### Screenshots (1280x800 or 640x400 pixels, up to 5)
Recommended screenshots to take:
1. Popup showing job auto-detected from LinkedIn
2. Full app dashboard with stats
3. Applications table with starred rows
4. AI Resume Builder in action
5. Follow-up email templates

### Promotional tile (optional but recommended)
- Small: 440x280 PNG
- Large: 920x680 PNG

---

## 3. STEP-BY-STEP SUBMISSION GUIDE

### Step 1 — Register as a Developer
1. Go to: https://chrome.google.com/webstore/devconsole
2. Sign in with your Google account
3. Pay the one-time $5 USD registration fee
4. Accept the Developer Agreement

### Step 2 — Prepare your ZIP
- Use the jobtrackr-pro-extension.zip file
- Make sure it does NOT include any test files or node_modules

### Step 3 — Create new item
1. Click "New Item" in the Developer Dashboard
2. Upload jobtrackr-pro-extension.zip
3. Fill in the store listing (use copy above)
4. Upload screenshots and icons
5. Set Category: Productivity
6. Set regions: All regions (or Singapore + selected countries)

### Step 4 — Privacy practices
You MUST fill in the privacy tab:
- Does your extension collect user data? → NO (all local)
- Single purpose description: "Track job applications and automate follow-up emails"
- Remote code: NO
- Permissions justification:
  • storage: Save application data locally
  • activeTab: Read job listing details from the current page
  • scripting: Inject content script to extract job data
  • tabs: Open the full app and mail links

### Step 5 — Submit for review
- Review takes 1-3 business days for new extensions
- You'll get an email when approved or if changes are needed

---

## 4. PRICING STRATEGY

### Recommended: Freemium Model

FREE tier (no account needed):
- Unlimited application tracking
- Auto-detect from job sites
- Email templates (non-AI)
- Visa tracker
- Kanban board

PRO tier (SGD 4.90/month or SGD 39/year):
- AI Resume Builder (generate + tailor)
- AI-personalised follow-up emails
- URL job extraction with AI
- Priority support

### Why this works:
- Low barrier to try (free = installs + word of mouth)
- AI features are the clear upgrade reason
- SGD 4.90 ≈ less than one coffee — easy sell
- Annual plan = 33% discount, better for your cash flow

---

## 5. LAUNCH CHECKLIST

Before submitting:
□ Extension tested on Chrome (fresh install)
□ Popup buttons all working
□ Full app opens and syncs with popup
□ Auto-detect tested on LinkedIn
□ Email templates working
□ No console errors on any page

Store listing:
□ Description written (use copy above)
□ 5 screenshots prepared (1280x800)
□ Icon 128x128 uploaded
□ Privacy policy URL added (use the privacy policy in this package)
□ Permissions justified

After approval:
□ Share install link on LinkedIn
□ Post in r/singapore, r/cscareerquestions, r/SEA_jobs
□ Share in Singapore expat Facebook groups
□ Post on Twitter/X with #Singapore #JobSearch #ExpatLife

---

## 6. PRIVACY POLICY URL

You need to host a privacy policy. Easiest free option:
1. Create a GitHub repository called "jobtrackr-privacy"
2. Add a README.md with the privacy policy text (see privacy-policy.md in this package)
3. Enable GitHub Pages
4. Your URL will be: https://[yourusername].github.io/jobtrackr-privacy

Or use https://app.termly.io to generate one for free.
