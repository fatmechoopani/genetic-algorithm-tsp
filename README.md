# 🧬 Genetic Algorithm for the Traveling Salesman Problem (TSP)

این پروژه یک پیاده‌سازی ساده از الگوریتم ژنتیک برای حل مسئله‌ی فروشنده دوره‌گرد (TSP) با استفاده از زبان Python است.

## 📌 مسئله فروشنده دوره‌گرد (TSP) چیه؟

فروشنده‌ای باید تعدادی شهر را فقط یک‌بار بازدید کرده و در نهایت به نقطه شروع برگردد، طوری که مسیر طی‌شده کمترین فاصله ممکن را داشته باشد. این مسئله یکی از مشهورترین مسائل بهینه‌سازی است.

## 🧠 روش حل

در این پروژه از الگوریتم ژنتیک استفاده شده که یک الگوریتم الهام‌گرفته از تکامل طبیعی است. مراحل کلی شامل:
- تولید جمعیت اولیه تصادفی
- محاسبه فاصله مسیرها (Fitness)
- انتخاب والدین
- عملیات ترکیب (Crossover)
- جهش (Mutation)
- تکرار تا رسیدن به جواب بهتر

## 📂 فایل‌ها

- `tsp_ga.py`: کد اصلی پروژه که الگوریتم ژنتیک را پیاده‌سازی می‌کند.
- `README.md`: توضیحات پروژه (همین فایل).

## 🚀 نحوه اجرا

برای اجرای پروژه نیاز به نصب Python دارید. بعد از نصب، دستور زیر را در ترمینال بزنید:

```bash
python tsp_ga.py
