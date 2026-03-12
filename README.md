# CIA Dashboard (SQLite Backend)

## تشغيل السيرفر محليًا

1. ثبّت الحزم:
   - `npm install`
2. شغّل السيرفر:
   - `npm start`
3. افتح المتصفح على:
   - `http://localhost:3000/index.html`

## ملاحظات

- قاعدة البيانات ستكون في `server/database.sqlite`.
- أول تشغيل سيقوم بإنشاء حسابات جاهزة:
  - Owner: `Director` / `director-001`
  - Admin: `Control` / `admin-001`
- الإعدادات العامة (الألوان، الخطوط، الصور، HUD) محفوظة في الجدول `site_config`.
