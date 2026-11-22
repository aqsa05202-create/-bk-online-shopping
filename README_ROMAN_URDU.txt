B_K ONLINE SHOPPING - Android APK project

Yeh pehla APK wrapper hai: app aapki maujooda website ko Android app ke andar kholta hai.
Yeh abhi native shopping app nahi hai. Website ke features aur Supabase backend website par hi chalenge.

APK banane ka asaan tareeqa:
1. Is ZIP ko extract karein.
2. Apne GitHub repository https://github.com/aqsa05202-create/-bk-online-shopping par jaayein.
3. Android project ki files repository ke root mein upload karein. Website ki index.html, style.css, app.js waghera delete/replace na karein.
4. .github/workflows/build-apk.yml bhi upload hona chahiye. GitHub mobile par hidden .github folder banana mushkil ho sakta hai; agar upload mein na aaye to pehle Android Studio ya desktop GitHub se upload karna hoga.
5. Commit ke baad GitHub repository mein Actions tab kholein.
6. "Build Android APK" workflow successful hone par run kholein.
7. Artifacts mein "BK-Online-Shopping-APK" download karein, ZIP extract karein, phir app-debug.apk install karein.

Note:
- APK banane ke liye internet aur GitHub Actions chahiye.
- Website ka published URL code mein set hai.
- Website mein login/database features tabhi kaam karenge jab website aur Supabase configuration sahi ho.
- Yeh debug APK hai, Play Store release ke liye signed release build aur privacy/security checks alag chahiye.
