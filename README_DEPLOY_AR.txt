طريقة النشر على Vercel:
1) فك ضغط الحزمة أولاً. لا ترفع ZIP كملف داخل المشروع.
2) ارفع محتويات المجلد إلى مستودع GitHub، ثم اختر Add New Project في Vercel واستورد المستودع.
3) اترك Root Directory على جذر المشروع؛ سيشغل Vercel npm run build وينشر مجلد dist.

بديل CLI: افتح الطرفية داخل هذا المجلد ثم شغّل vercel --prod.
