# موقع مشكاة الثقافة | التراث الذكي

موقع من صفحة واحدة (HTML + ملفات). لا يحتاج أي خادم أو أدوات بناء.

## النشر على GitHub Pages (مجاني)
1. أنشئ مستودعاً عاماً جديداً على GitHub (مثال: smart-heritage).
2. ارفع **محتويات هذا المجلد** (index.html ومجلد assets) إلى المستودع.
3. من Settings ← Pages اختر Branch: main و Folder: / (root) ثم Save.
4. بعد دقيقة يظهر الرابط: https://اسم-المستخدم.github.io/smart-heritage/

## تفعيل حفظ التقييمات
في index.html ابحث عن السطر:
    const CFG={endpoint:'',extra:{}};
- Formspree: أنشئ نموذجاً مجانياً وضع رابطه: endpoint:'https://formspree.io/f/XXXX'
- Web3Forms: endpoint:'https://api.web3forms.com/submit', extra:{access_key:'مفتاحك'}
قبل التفعيل يبقى زر الإرسال معطلاً وتظهر رسالة صريحة، ولا تظهر رسالة نجاح وهمية.

## رمز QR
افتح الرابط النهائي في أي مولّد QR مجاني، أو أرسل الرابط ليُنشأ لك رمز بصيغة PNG.

## ملاحظة أمان
لا ترفع كود ESP32 إلى GitHub لأنه يحتوي أسماء شبكات Wi-Fi وكلمات مرورها.
