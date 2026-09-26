# SCORPIUS Studio

موقع SCORPIUS لاستوديو رقمي وفريق متكامل في تطوير المنتجات، تصميم الواجهات، والهوية البصرية.

## التشغيل المحلي

```bash
pnpm install
pnpm run dev
```

## بناء نسخة الإنتاج

```bash
pnpm run build
```

## إعداد Vercel

- Framework Preset: `Vite`
- Root Directory: `.`
- Install Command: `pnpm install`
- Build Command: `pnpm run build`
- Output Directory: `dist/public`

## الملفات الأساسية

- `client/src/pages/Home.tsx` — محتوى الصفحة والتفاعلات.
- `client/src/index.css` — نظام التصميم والتجاوب.
- `client/index.html` — إعداد اللغة والبيانات الوصفية.
- `client/public/scorpius-hero-abstract.jpg` — خلفية الـ Hero.

## التخصيص السريع

- رقم واتساب: متغير `whatsappNumber` في `client/src/pages/Home.tsx`.
- أعضاء الفريق: مصفوفة `team` في نفس الملف.
- الخدمات: مصفوفة `services`.
- الأسئلة الشائعة: مصفوفة `faqs`.
