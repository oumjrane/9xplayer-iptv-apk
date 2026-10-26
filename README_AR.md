# مشروع تطبيق 9XPlayer IPTV (للهاتف و Android TV Box)

يحتوي هذا الأرشيف على:
1. `www/index.html`: التطبيق الكامل مع دعم شاشات الهواتف وأزرار ريموت Android TV Box.
2. `android_config/AndroidManifest.xml`: ملف إعدادات أندرويد يدعم الهواتف (`LAUNCHER`) وأجهزة التلفاز (`LEANBACK_LAUNCHER`) وتشغيل روابط البث غير المشفرة (`usesCleartextTraffic="true"`).
3. `.github/workflows/build-apk.yml`: ملف بناء تلقائي لاستخراج ملف `.apk` مجاناً عبر GitHub Actions أو عبر تطبيقات تحويل HTML إلى APK مثل WebIntoApp أو Website 2 APK Builder.
