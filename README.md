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
- We can Exports leads to Google Sheets or Airtable

---

##  Workflow Structure

```plaintext
Webhook → Set Niche → AI Agent (List Sites)
Extract top 10 SEO based sites with Gemini Model
And with Code node+ Set Node shortlist the Wensites with DA,DR,Traffic etc
Finally Give result at frontend.
