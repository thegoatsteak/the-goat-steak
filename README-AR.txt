طريقة تشغيل لوحة التحكم لمنيو THE GOAT STEAK

1) أنشئ حساب GitHub من https://github.com إذا ما عندك حساب.
2) أنشئ Repository جديداً باسم the-goat-steak-menu واجعله Public أو Private.
3) ارفع جميع محتويات هذا المجلد إلى جذر المستودع (بما فيها .pages.yml ومجلد data وmedia وindex.html).
   ملاحظة: لإظهار الملف المخفي .pages.yml عند الرفع تأكد أنك ترفع كل الملفات.
4) في Netlify اختر Add new site ثم Import an existing project، واربط GitHub واختر المستودع.
   Publish directory: .   (ولا تحتاج Build command)
5) بعد نشر Netlify، افتح https://app.pagescms.org وسجّل الدخول باستخدام GitHub.
6) اسمح لتطبيق Pages CMS بالوصول إلى مستودع the-goat-steak-menu فقط.
7) افتح المستودع داخل Pages CMS. ستظهر لك صفحة "إعدادات المنيو والأصناف".
8) عدّل الأسعار والوصف ورقم التواصل، وارفع الصور من حقل "صورة الصنف"، ثم احفظ.
   Pages CMS يحفظ التغييرات في GitHub، وNetlify يعيد نشر الموقع تلقائياً.
9) رابط المنيو العام يبقى نفسه ما دمت لا تغيّر اسم الموقع أو النطاق.

مهم:
- لوحة Pages CMS منفصلة عن رابط المنيو، ولا تشارك دخول GitHub أو Pages CMS مع العملاء.
- لا تضع كلمات المرور أو مفاتيح API داخل ملفات الموقع.
- جرّب التعديل بعد النشر وتأكد من ظهور التحديث في رابط المنيو.
