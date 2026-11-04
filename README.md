# موقع المهندس نجيب علوان الفراصي

موقع عربي ثابت مع لوحة إدارة Decap CMS.

## لوحة الإدارة

بعد نشر الموقع وإعداد مصادقة GitHub في Netlify، افتح:

`https://engnajeeb.netlify.app/admin/`

## المحتوى

يُدار المحتوى من `content/site.json`. تُرفع صور الأعمال من لوحة الإدارة إلى `images/uploads/`.

## إعداد Netlify

- Publish directory: `.`
- Build command: اتركه فارغاً (الموقع HTML/CSS/JS ثابت ولا يحتاج خطوة بناء).
- اربط مشروع Netlify الحالي بالمستودع `engnajeebalwan-oss/Eng-najeeb-alwan-alfurasy` وعلى الفرع `main`.
- أكمل إعداد موفر مصادقة GitHub الذي تتطلبه Decap CMS في إعدادات Netlify قبل استخدام صفحة الإدارة.

لا تضع Client Secret أو رموز وصول أو كلمات مرور في ملفات المستودع.
