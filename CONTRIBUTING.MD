# CONTRIBUTING.MD
> This is a template from [abjad.wiki](https://abjad.wiki)

[اقرأ بالعربي](#arabic) | [Read English ↓](#english)

---

<a name="arabic"></a>
# 🤝 كيف تساهم في أبجد ويكي

شكراً إنك عايز تساهم! أبجد ويكي مشروع مجتمعي مفتوح، وكل إضافة بتفرق.

## القواعد الأساسية

- **الدقة أهم من السرعة.** لو مش متأكد من معلومة، اكتب "يُرجى التحقق" أو اسأل في الـ issues.
- **اكتب بالعامية المصرية** عشان المحتوى يوصل لأكبر عدد من الناس.
- **المحتوى محايد.** مش المفروض تروج لمنتج أو خدمة معينة.
- **حدّث التاريخ.** كل صفحة لازم تكون فيها جملة "آخر تحديث" في الآخر.
- **مفيش معلومات قانونية أو طبية** من غير إشارة واضحة إنها مش استشارة متخصصة.

---

## الـ Formatter

كل صفحة لازم تبدأ بـ frontmatter بالشكل ده:

```yaml
---
title:
  en: "Page Title in English"
  ar: "عنوان الصفحة بالعربي"
description:
  en: "Short description in English"
  ar: "وصف قصير بالعربي"
order: 1
category_order: 1
category_icon: "💸"
category_title:
  en: "Category Name"
  ar: "اسم الكاتيجوري"
category_description:
  en: "Category description in English"
  ar: "وصف الكاتيجوري بالعربي"
hidden: false
---
```

### الكاتيجوريز والترتيب

| category_order | العربي | English |
|---|---|---|
| 1 | أساسيات الفلوس | Basics |
| 2 | البنوك | Banks |
| 3 | المحافظ والتطبيقات | Wallets & Apps |
| 4 | استلام دولار من مصر | Money Abroad |
| 5 | استثمار | Investment |
| 6 | الكريبتو شرعياً | Crypto |
| 7 | الأزمات والطوارئ | Crises & Emergencies |
| 8 | النصب والاحتيال | Fraud & Scams |

---

## خطوات المساهمة

1. **Fork** الريبو
2. اعمل **branch** جديد باسم واضح، مثلاً: `add/vodafone-cash` أو `fix/paypal-limits`
3. اكتب المحتوى واتبع الـ formatter
4. افتح **Pull Request** مع وصف قصير لإيه اللي أضفته أو عدلته
5. هيتعمل review وهيتضاف لو كل حاجة تمام

---

## للمزيد

- 📖 [Styling Guide](./STYLING.MD) -إزاي تكتب وتنسق الصفحات
- 💬 [Issues](https://github.com/abjaad/pfeg/issues) - اقترح صفحة جديدة أو بلغ عن معلومة غلط

---

<a name="english"></a>
# 🤝 How to Contribute to Abjad Wiki

Thanks for wanting to contribute! Abjad Wiki is an open community project, and every addition makes a difference.

## Basic Rules

- **Accuracy over speed.** If you're unsure about something, write "needs verification" or open an issue.
- **Write in Egyptian Arabic** so content is accessible to as many people as possible.
- **Stay neutral.** Don't promote specific products or services.
- **Update the date.** Every page should end with a "Last updated" note.
- **No legal or medical information** without a clear disclaimer that it's not professional advice.

---

## The Formatter

Every page must start with frontmatter in this format:

```yaml
---
title:
  en: "Page Title in English"
  ar: "عنوان الصفحة بالعربي"
description:
  en: "Short description in English"
  ar: "وصف قصير بالعربي"
order: 1
category_order: 1
category_icon: "💸"
category_title:
  en: "Category Name"
  ar: "اسم الكاتيجوري"
category_description:
  en: "Category description in English"
  ar: "وصف الكاتيجوري بالعربي"
hidden: false
---
```

### Categories & Order

| category_order | Arabic | English |
|---|---|---|
| 1 | أساسيات الفلوس | Basics |
| 2 | البنوك | Banks |
| 3 | المحافظ والتطبيقات | Wallets & Apps |
| 4 | استلام دولار من مصر | Money Abroad |
| 5 | استثمار | Investment |
| 6 | الكريبتو شرعياً | Crypto |
| 7 | الأزمات والطوارئ | Crises & Emergencies |
| 8 | النصب والاحتيال | Fraud & Scams |

---

## Contribution Steps

1. **Fork** the repo
2. Create a new **branch** with a clear name, e.g. `add/vodafone-cash` or `fix/paypal-limits`
3. Write your content following the formatter above
4. Open a **Pull Request** with a short description of what you added or changed
5. It will be reviewed and merged if everything looks good

---

## More Resources

- 📖 [Styling Guide](./STYLING.MD) - How to write and format pages
- 💬 [Issues](https://github.com/abjaad/pfeg/issues) - Suggest a new page or report incorrect info
