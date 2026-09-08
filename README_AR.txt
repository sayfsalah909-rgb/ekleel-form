Ekleel Group — نسخة iPhone/Web النهائية

هذه النسخة تصلح للرفع على GitHub Pages أو أي استضافة HTTPS ثابتة.

مهم جدًا:
- لا تفتح index.html من تطبيق "الملفات" على iPhone إذا أردت تشغيل JavaScript بالكامل.
- ارفع الملفات إلى استضافة HTTPS ثم افتح الرابط في Safari.
- في GitHub Pages: ارفع الملفات إلى المستودع، ثم Settings > Pages > Deploy from a branch > main > / (root).
- بعد ظهور الرابط افتحه في Safari على iPhone ثم Share > Add to Home Screen.

الإصلاح في هذه النسخة:
تم إصلاح خطأ HTML/JavaScript داخل وظيفة الطباعة كان يجعل متصفح iPhone يوقف قراءة جزء كبير من JavaScript عند وجود <script> داخل قالب الطباعة. لذلك كانت الأزرار تبدو وكأنها لا تستجيب.

الملفات:
index.html
manifest.webmanifest
sw.js
icon-192.png
icon-512.png
.nojekyll
