# EcoReguard website

Static English landing page prepared for Netlify.

## Integrations

**Active as of June 2026:**
- **Typeform** - Embedded compliance check form on `/check.html` 
- **Voiceflow** - EmpCo Guru AI chat integrated into the main landing page
- **Google Fonts, Tailwind CSS, Material Symbols** - Loaded via CDN

### Configuration

**Voiceflow Project ID:** Set via environment variable `VOICEFLOW_PROJECT_ID`
- In Netlify: Site settings → Build & deploy → Environment
- Locally: Create `.env` file or set in terminal before serving

## Local preview

Open `index.html` directly or serve the folder with any static web server.

## Deployment

Connect this repository to Netlify. No build command is required and the
publish directory is the repository root.

## Site structure

- `index.html` - Main landing page with Voiceflow AI chat
- `check.html` - EmpCo compliance check page with embedded Typeform
- `imprint.html` - Legal impressum (FLUSTIX GmbH)
- `privacy.html` - GDPR-compliant privacy policy (updated June 8, 2026)
- `assets/` - Images and brand assets
- `netlify.toml` - Netlify routing configuration

## Pre-launch checklist

- ✅ Privacy policy updated for Typeform & Voiceflow (June 8, 2026)
- ⚠️ Consider locally hosting Google Fonts before production
- ⚠️ Review EmpCo legal claims with legal counsel before launch
- ⚠️ Verify Typeform data processing agreement (DPA) is signed
- ⚠️ Verify Voiceflow data processing agreement (DPA) is signed
- ⚠️ Connect production domain and test all redirects
- ⚠️ Test compliance form and AI chat functionality in production
