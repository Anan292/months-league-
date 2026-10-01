# دوري الأشهر — Android APK Builder

هذا المشروع يحول نسخة الويب الحالية من دوري الأشهر إلى تطبيق Android APK.

## من الهاتف فقط

1. أنشئ مستودع GitHub جديدًا باسم `month-league`.
2. ارفع **كل محتويات هذا المجلد** إلى المستودع (وليس ملف ZIP نفسه).
3. اجعل الفرع `main`.
4. افتح تبويب **Actions**.
5. اختر **Build Android APK** ثم **Run workflow**.
6. انتظر حتى يكتمل البناء.
7. افتح نتيجة التشغيل ثم قسم **Artifacts**.
8. حمّل `month-league-apk`.
9. فك ضغط الـartifact وستجد `app-debug.apk`.
10. ثبّته على الهاتف.

لا تحتاج إلى Android Studio على هاتفك.

> ملاحظة: APK الناتج Debug ومناسب للتجربة والتثبيت الشخصي. للنشر على Google Play لاحقًا نحتاج توقيع Release/Android App Bundle.
