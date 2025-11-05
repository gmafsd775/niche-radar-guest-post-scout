NicheRadar Protocol: Guest Post Scout
Modular AI-powered workflow to scout guest post websites by niche, shortlist beginner-friendly leads, and guide outreach strategy.

**Find, filter, and outreach to the best websites in any niche — powered by AI and built in n8n.**

---

## What It Does

- Accepts niche input via webhook
- Uses AI to list high-traffic websites
- Parses and normalizes data
- Shortlists beginner-friendly sites
- Suggests outreach strategy
- We can also Exports leads to Google Sheets or Airtable

---

Visit the frontend here:  
🔗 [https://gmafsd775.github.io/niche-radar-guest-post-scout/](https://gmafsd775.github.io/niche-radar-guest-post-scout/)

## 📦 GitHub Repository

Explore the source code and workflow:  
🔗 [[https://github.com/gmafsd775/niche-radar-guest-post-scout](https://github.com/gmafsd775/niche-radar-guest-post-scout)](https://github.com/gmfaid7575/niche-radar-guest-post-scout)

##  Workflow Structure

```plaintext
Webhook → Set Niche → AI Agent (List Sites)
Extract top 10 SEO based sites with Gemini Model
And with Code node+ Set Node shortlist the Wensites with DA,DR,Traffic etc
Finally Give result at frontend.
