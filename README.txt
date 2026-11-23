B_K ONLINE SHOPPING — LIVE LOGIN UPDATE

Included: Supabase email/password sign-up, login, logout, session restore and password reset.

INSTALL
1. Extract this ZIP.
2. Upload index.html and README.txt to the ROOT of your existing GitHub Pages repository (replace the old index.html).
3. Wait for GitHub Pages deployment, then open your website and test Sign Up / Login.

SUPABASE CHECKS
- Supabase Dashboard → Authentication → Providers → Email: enable Email provider.
- For email verification, configure the Supabase email templates and SMTP as desired.
- Authentication → URL Configuration: add your GitHub Pages site URL to Site URL / Redirect URLs. Example: https://aqsa05202-create.github.io/-bk-online-shopping/
- Password reset uses the current site URL.

SECURITY
The browser contains only the Supabase publishable key, which is designed for public client use. Never put a service_role or secret key in this file.
This update connects customer authentication only; it does not yet make orders/products persist in database tables.
