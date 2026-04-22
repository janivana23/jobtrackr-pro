# Privacy Policy — JobTrackr Pro

**Last updated: April 2026**

## Overview

JobTrackr Pro ("the Extension") is committed to protecting your privacy. This policy explains what data we collect, how we use it, and your rights.

## Data We Collect

### Data stored locally on your device
JobTrackr Pro stores the following data **locally in your browser** using Chrome's `chrome.storage.local` API:

- Job application details (company name, role, status, dates, notes)
- Your preferences (name, nationality, job preferences, salary range)
- Visa and work pass information you enter
- Your Anthropic API key (if you choose to use AI features)

**This data never leaves your device** unless you explicitly use AI features (see below).

### Data sent to third parties

**Anthropic API (only when using AI features):**
- When you use the AI Resume Builder or AI email generation, the text you enter is sent to Anthropic's API at api.anthropic.com
- This requires your own Anthropic API key
- Anthropic's privacy policy applies: https://www.anthropic.com/privacy
- We do not store or log any data sent to Anthropic

**Job listing websites:**
- When you visit job listing sites (LinkedIn, Indeed, etc.), our content script reads publicly visible job data (role, company, location) from the page
- This data is only used to auto-fill the application form in the extension
- We do not transmit this data anywhere

## Data We Do NOT Collect

- We do not have any servers or databases
- We do not collect analytics or usage data
- We do not collect personal identification information
- We do not use cookies
- We do not sell, rent, or share your data with anyone
- We do not have access to your data at all — it stays on your device

## Permissions Explained

| Permission | Why we need it |
|-----------|----------------|
| `storage` | Save your application data locally in your browser |
| `activeTab` | Read job listing details from the page you're currently viewing |
| `scripting` | Run a script to extract job data from job listing pages |
| `tabs` | Open the full app view and email links in new tabs |

## Data Security

All your data is stored locally using Chrome's built-in secure storage. Your Anthropic API key is stored locally and only transmitted directly to Anthropic when you use AI features.

## Your Rights

You can delete all your data at any time by:
1. Going to `chrome://extensions`
2. Clicking "Details" on JobTrackr Pro
3. Clicking "Clear data"

Or by uninstalling the extension, which removes all locally stored data.

## Changes to This Policy

We will update this policy if our data practices change. The "Last updated" date at the top of this page will reflect any changes.

## Contact

If you have questions about this privacy policy, please open an issue at:
https://github.com/janivana23/jobtrackr-pro

---

*JobTrackr Pro is an independent product not affiliated with Google, LinkedIn, Indeed, or any job platform.*
