خطوات التشغيل (مجانية - خطة Firebase Spark)

1) console.firebase.google.com: أنشئ مشروعا، ثم أضف تطبيق Web.
2) الصق إعدادات التطبيق في public/index.html (ابحث عن YOUR_API_KEY).
3) Authentication > Sign-in method: فعّل Google.
   Authentication > Settings > Authorized domains: أضف نطاق موقعك.
4) Firestore Database: أنشئ قاعدة بيانات (production mode).
5) في الطرفية داخل هذا المجلد:
   npm i -g firebase-tools
   firebase login
   firebase use --add
   firebase deploy

يُنشر الموقع على HTTPS تلقائيا، وتُنشر قواعد الحماية (firestore.rules) معه.
