# Akasia — Interactive Website Package

## تشغيل النسخة على أي جهاز
1. نزّل ملف ZIP وفك الضغط أولًا.
2. افتح `index.html` بمتصفح حديث مثل Chrome أو Edge أو Safari.
3. كل الصور والخطوط وفيديو اللوجو والكود مدمجة داخل الملف. لا تحتاج إنترنت أو تثبيت برامج أو تشغيل localhost.

التجربة تتضمن اللوجو، الماب وتفاعل الدول، Home، About، وFMCG & Retail. تعمل النقاط بالماوس أو اللمس، وTab/Enter لاختيار دولة وEscape لفك التثبيت. أول scroll من الماب يفتح الهوم بفيد. الانتقال التلقائي بعد 15 ثانية خمول؛ الإعداد في الموقع مستقل عن مدة فيديو العرض المختصر. بعض الأنيميشن يتوقف عند تفعيل Reduce Motion بالجهاز.

## الرفع إلى GitHub Pages
1. أنشئ Repository على GitHub أو افتح المستودع المطلوب.
2. ارفع **محتويات هذا المجلد** إلى جذر المستودع على فرع `main` — لا ترفع ملف ZIP نفسه. لازم `index.html` يكون ظاهر مباشرة في الجذر وليس داخل مجلد إضافي.
3. ارفع `.nojekyll` أيضًا لتعطيل معالجة Jekyll. هذا ملف مخفي؛ على Mac أظهر الملفات المخفية بـ Command + Shift + نقطة، أو أنشئه على GitHub باسم `.nojekyll`.
4. افتح Settings → Pages.
5. Source: Deploy from a branch.
6. Branch: main، Folder: /(root)، ثم Save.
7. بعد اكتمال النشر سيظهر رابط الموقع داخل نفس صفحة الإعدادات. تحديث `index.html` بعد ذلك يحدّث الموقع تلقائيًا.

الموقع static بالكامل: لا يحتاج Node أو npm أو database أو GitHub Actions مخصص. المسارات الداخلية تستخدم # وتعمل على GitHub Pages داخل اسم المستودع.

GitHub Pages عادةً ينشر الموقع للعامة؛ للمراجعة الخاصة مع الفريق شارك ZIP مباشرة. إتاحة Pages للمستودعات الخاصة تعتمد على خطة الحساب، وخصوصية المستودع لا تعني تلقائيًا خصوصية الموقع المنشور.

مرجع GitHub الرسمي:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## English quick start
Unzip, then open index.html in a modern desktop browser. All assets are embedded; no internet, server or installation is required.
To host: upload the package contents to a GitHub repository root, including index.html and .nojekyll. Enable Settings → Pages → Deploy from a branch → main → /(root). Use the URL shown by GitHub after deployment.

This package contains the current interactive website, not the edited presentation video. No hosting credentials, repository metadata or account tokens are included.
