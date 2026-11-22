# B_K ONLINE SHOPPING — Real website starter

Yeh **deployable backend + frontend starter project** hai, magar abhi public internet par hosted nahi. Is mein:
- Customer registration/login
- Seller application (owner approval ke baghair seller active nahi hota)
- Seller product submission
- Owner-only seller/product approval
- Customer order request
- Owner order status management
- PKR aur USD price fields
- SQLite database

## Zaroori baat
Abhi payment gateway, courier/shipping API, automated tax, refunds, live AI assistant, Alibaba/Amazon/TikTok API sync aur production-grade cloud database connected nahi. Website order request save karti hai; online payment process nahi karti. In integrations ke liye provider approval, merchant account, API keys aur legal/business requirements poori karni hoti hain. Minor user ko payment/business accounts ke liye parent/guardian ki madad aur provider ki age rules follow karni hongi.

## Run karne ka tareeqa
1. Computer par Node.js 20+ install karein.
2. Is ZIP ko extract karein.
3. Terminal mein project folder open karein.
4. `npm install` chalayein.
5. `.env.example` ki copy bana kar `.env` naam dein.
6. `.env` mein OWNER_EMAIL aur OWNER_PASSWORD change karein. SESSION_SECRET ko lambi random value dein. `.env` kisi ko share na karein.
7. `npm start` chalayein.
8. Browser mein `http://localhost:3000` kholein.

## Live internet par publish karne se pehle
- HTTPS-enabled hosting aur managed database use karein.
- Default/development secrets replace karein.
- Persistent secure session store lagayein (default Express MemoryStore production ke liye nahi).
- Rate limiting, CSRF protection, email verification, password reset, audit logs, backups, privacy policy, terms, refund/return policy aur seller agreement add karein.
- Payment gateway (Pakistan mein supported provider) ko merchant approval aur official API docs ke mutabiq integrate karein. Card data khud store na karein.
- Courier API/contract aur shipping rates configure karein.
- Security review aur real-device testing karein.

## Android note
Android par ZIP download/extract aur code dekh sakte hain, lekin is Node.js server ko aasani se run/deploy karne ke liye computer ya supported cloud development environment behtar hai. Hosting account aur domain setup alag step hai.
