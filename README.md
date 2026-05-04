# استضافة الموقع على GitHub Pages

هذا المشروع يحتوي على صفحة HTML واحدة `index.html`، ويمكن نشرها مجانًا باستخدام GitHub Pages.

## الخطوات الأساسية

1. أنشئ مستودعًا جديدًا على GitHub.
   - اذهب إلى https://github.com/new
   - اختر اسمًا للمستودع مثل `oxygen-site` أو أي اسم تريده.
   - اترك الخيار "Initialize this repository with a README" غير محدد إذا كنت تريد رفع الملفات من جهازك.

2. اربط المجلد المحلي بالمستودع على GitHub:

```bash
cd "c:\Users\pc\Desktop\New folder (2)"
git init
git add index.html README.md
git commit -m "Initial commit"
git branch -M main
# غيّر الرابط التالي برابط المستودع الخاص بك
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

3. فعّل GitHub Pages:
   - افتح المستودع في GitHub.
   - انتقل إلى `Settings` > `Pages`.
   - تحت "Build and deployment" اختر الفرع `main` والمجلد `/ (root)`.
   - اضغط `Save`.

4. بعد دقائق قليلة، سيكون موقعك متاحًا عبر:

```
https://<your-username>.github.io/<repo-name>/
```

## إذا أردت نشرًا أسرع بدون GitHub
يمكنك استخدام خدمات مجانية مثل:
- Netlify: https://app.netlify.com/drop
- Vercel: https://vercel.com/new

كل ما تحتاجه هو سحب وإفلات مجلد المشروع أو وصل المستودع من GitHub.

## ملاحظة
إذا أردت، يمكنني أيضًا مساعدتك في إعداد `git` محليًا هنا وإعداد المستودع لرفع الملفات أولًا.
