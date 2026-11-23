B_K ONLINE SHOPPING — FINAL WEBSITE PACKAGE

This package is based on the latest B_K login update. It preserves the existing Supabase email/password sign-up, login, logout, session restore and password-reset flow, plus TikTok video links, wishlist, coupons, reviews, customer cart/checkout preview and order tracking.

NEW IN THIS FINAL UPDATE
- Two professional animated promotional poster panels.
- Refined motion, hover and mobile responsive styling; respects reduced-motion accessibility settings.
- Store Preferences panel for display currency, language preference, appearance preference and public support email.
- PWA manifest, B_K SVG app icon, robots.txt and .nojekyll for GitHub Pages.

PUBLISH TO THE EXISTING PUBLIC SITE
1. Extract this ZIP.
2. Open your existing GitHub repository and upload the CONTENTS of this folder to the repository root.
3. Replace the existing index.html with this index.html. Upload manifest.webmanifest, robots.txt, .nojekyll and the assets folder too.
4. Keep existing GitHub Pages settings (main branch / root) unchanged.
5. Wait for the Pages deployment workflow to finish, then open:
   https://aqsa05202-create.github.io/-bk-online-shopping/

SUPABASE AUTH
- Existing Supabase project URL and browser publishable key are retained from the latest login package.
- Supabase Dashboard → Authentication → URL Configuration: ensure the public site URL is in the allowed Redirect URLs.
- Email provider must be enabled. Configure email confirmation/SMTP as required.
- Never add a service_role key or other secret to this public website.

IMPORTANT LIMITS
- This is still a static GitHub Pages front end. Authentication uses Supabase, but products, seller applications, cart, order previews, reviews, coupons, TikTok links and settings that are marked as browser preview are stored in localStorage and are not shared across devices.
- The public customer page does not expose an owner/admin dashboard. Do not add owner controls to the public navigation.
- Live payment processing, shared product/order database, real courier tracking, AI API responses and automatic TikTok/Amazon/Alibaba catalogue sync are not enabled. Those require secure backend/database policies, business/provider accounts and approved integrations.
- Do not enter payment card details or private customer data in demo-only fields.

CHROME
Open the HTTPS site in Chrome. On Android, use Chrome menu → Add to Home screen (or Install app when offered).
