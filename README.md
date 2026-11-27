# PartSouq App

- `pwa/` : تطبيق ويب (PWA) يُنشر على أي استضافة HTTPS (GitHub Pages, Netlify...) ويُثبَّت من Chrome.
- `android/` : مشروع أندرويد (WebView) يفتح https://partsouq.com/en/ ويُنتج ملف APK.
- `.github/workflows/build-apk.yml` : يبني APK تلقائيا على GitHub (Actions → Build APK → Artifacts).

بناء محلي: افتح مجلد `android` في Android Studio ثم Build → Build APK.
