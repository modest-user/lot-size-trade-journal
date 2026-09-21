LOT SIZE CALCULATOR + JOURNAL — PWA PACKAGE
=============================================

Isme 5 files hain: index.html, manifest.json, service-worker.js,
icon-192.png, icon-512.png, icon-maskable-512.png.
In sabko EK saath, isi naam se, ek hi folder me rakhna hai jab bhi
host karo — naam ya structure mat badalna.

STEP 1 — Free hosting (HTTPS zaroori hai, PWA install isके bina nahi hota)
  Sabse aasan free options (koi bhi ek):
   - GitHub Pages  (github.com pe free account, "New repository" →
     ye files upload karo → Settings → Pages → Enable)
   - Netlify Drop  (app.netlify.com/drop pe seedha ye folder drag-drop
     karo, turant ek https link mil jata hai)
  Dono free hain, credit card nahi chahiye.

STEP 2 — Test as an app
  Us https link ko Android phone pe Chrome mein kholo.
  Chrome apne aap "Add to Home Screen" / "Install app" ka option
  dikhayega — install karke check karo icon aur app jaisa feel aa
  raha hai ya nahi (ab ye offline bhi chalega).

STEP 3 — Play Store ke liye Android package banao
  Website: pwabuilder.com (Microsoft ka free tool)
   - Apna hosted https link daalo
   - "Android" package select karo → it generates a signed .aab file
   - Ye .aab hi Play Store pe upload hota hai

STEP 4 — Google Play Developer account
   - play.google.com/console pe account banao (one-time $25 fee,
     ID verification lagti hai — ye sirf Google khud kar sakta hai,
     iske bina koi app store pe list nahi ho sakta)
   - Ek simple Privacy Policy page chahiye hoga (chunki app photos
     use karti hai) — likh sakta hoon agar chahiye, sirf ek line
     mein bata dena: "sab data sirf device par local rehta hai,
     kahin bheja nahi jata."

STEP 5 — Store listing bana ke submit karo
   - App name, screenshots (apne phone se le lena after install),
     description, category "Finance" ya "Productivity"
   - Data safety form mein bata dena: "no data collected/shared"
     (sab kuch local storage mein hai)
   - Submit → Google ka review 1-3 din leta hai, phir live ho jayega

Iske baad koi bhi user Play Store se search karke install kar
payega.
