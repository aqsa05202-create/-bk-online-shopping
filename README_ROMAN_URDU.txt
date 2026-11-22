B_K ONLINE SHOPPING - SETUP GUIDE (Roman Urdu)

ZIP KE ANDAR:
1. index.html - website homepage, login/signup, shop, cart, dashboards
2. style.css - design
3. app.js - website functions
4. supabase-config.js - tumhare Supabase project ki public/publishable settings
5. schema.sql - database tables aur security policies
6. README_ROMAN_URDU.txt - ye guide

STEP 1 - DATABASE:
1. Supabase dashboard kholo aur BK-ONLINE-SHOPPING project select karo.
2. SQL Editor kholo.
3. New query par tap karo.
4. schema.sql file ka poora code copy karke SQL Editor mein paste karo.
5. Run dabao. Agar error aaye to screenshot bhejo.

STEP 2 - GITHUB:
1. Apni existing repository kholo: aqsa05202-create/-bk-online-shopping
2. Add file > Upload files kholo.
3. ZIP ko pehle extract karo. ZIP file ko directly upload NAHI karna.
4. Andar ki 5 website/setup files upload karo: index.html, style.css, app.js, supabase-config.js, schema.sql.
5. Agar same naam ki file pehle se hai to usay replace/overwrite karo.
6. Commit message: Replace website with full marketplace system
7. Commit changes dabao.

STEP 3 - FIRST ADMIN:
1. Website par apna account create karo.
2. Supabase > SQL Editor mein ye query apne email ke saath run karo:
   update public.profiles p set role='admin'
   from auth.users u where p.id=u.id and u.email='YOUR_EMAIL_HERE';
3. YOUR_EMAIL_HERE ko apne registered email se replace karo.
4. Website refresh karke sign in karo. Admin dashboard nazar aana chahiye.
5. Admin dashboard mein seller ki role ko seller kar ke seller access approve kar sakte ho.

IMPORTANT:
- Website abhi product listing, customer auth, cart, orders, seller/admin screens ka starter system hai. Har feature ko live data ke saath test karna zaroori hai.
- Payment gateway, shipping/courier integrations, refunds, tax, inventory reservation, product image upload/storage, seller payouts, messaging, AI assistant aur international checkout abhi configured nahi hain.
- Checkout order record banata hai; ye card/JazzCash/Easypaisa payment collect nahi karta. Customer ko payment lene ka jhoota confirmation nahi deta.
- PKR/USD yahan currency display aur per-product currency selection ke liye hai; exchange rate conversion nahi hoti.
- GitHub Pages static hosting hai. Secure backend Supabase par chalta hai.
- Supabase publishable key browser mein use ho sakti hai with RLS policies. service_role/secret key kabhi bhi website mein mat dalna.
- Admin role sirf Supabase SQL se pehli dafa set karo. Apna admin password kisi ke saath share na karo.
- Agar GitHub HTTP 400 de, pehle page refresh karke files ko 1-2 at a time upload karo. Error screenshot save kar ke bhejo.
