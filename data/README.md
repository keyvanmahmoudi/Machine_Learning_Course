<div dir="rtl">

# داده‌های دوره

| فایل | توضیح | جلسه | منبع |
|---|---|:---:|---|
| `titanic.csv` | ۸۹۱ مسافر تایتانیک و زنده ماندن یا نماندن آن‌ها | ۲، ۸ | [Kaggle: Titanic](https://www.kaggle.com/c/titanic) |
| `housing.csv` | ۲۰۶۴۰ ناحیهٔ مسکونی کالیفرنیا از سرشماری ۱۹۹۰ و میانهٔ قیمت خانه | ۳، ۴، ۶، ۷، ۸، ۹، ۱۴ | Pace & Barry (1997)، StatLib؛ نسخهٔ کتاب Géron با ستون `ocean_proximity` |
| `Churn_Modelling.csv` | ۱۰۰۰۰ مشتری بانک و ترک کردن یا نکردن بانک | ۱۰، ۱۳ | Kaggle: Bank Customer Churn |
| `Restaurant_Reviews.tsv` | ۱۰۰۰ نظر کوتاه انگلیسی دربارهٔ رستوران با برچسب مثبت/منفی | ۶ | Kotzias et al. (2015)، UCI Sentiment Labelled Sentences |
| `Mall_Customers.csv` | ۲۰۰ مشتری مرکز خرید با سن، درآمد و امتیاز خرج کردن | ۱۱ | Kaggle: Mall Customer Segmentation |
| `Market_Basket_Optimisation.csv` | ۷۵۰۱ تراکنش یک فروشگاه، هر سطر یک سبد خرید | ۱۳ | Kaggle: Market Basket Optimisation |
| `bank_marketing.csv` | ۴۱۱۸۸ تماس تلفنی کمپین بازاریابی یک بانک پرتغالی | ۱۴ | Moro et al. (2014)، [UCI Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)، مجوز CC BY 4.0 |

## داده‌های داخلی scikit-learn

بعضی جلسه‌ها از داده‌هایی استفاده می‌کنند که همراه scikit-learn نصب می‌شوند و فایل جداگانه ندارند: `load_iris`، `load_wine`، `load_breast_cancer`، `load_digits`، `load_diabetes` و `load_sample_image`.

## نکته‌ها

- در `bank_marketing.csv` (نسخهٔ `bank-additional-full`) نقطه در نام ستون‌ها با زیرخط جایگزین شده است (مثلاً `emp.var.rate` به `emp_var_rate`)؛ بقیهٔ داده دست‌نخورده است.
- ستون `duration` در دادهٔ بانک فقط بعد از تماس معلوم است و در جلسهٔ ۱۴ به‌عنوان نمونه‌ای از نشت هدف حذف می‌شود.
- نوت‌بوک‌ها داده‌ها را مستقیم از نشانی خام همین مخزن می‌خوانند، پس برای اجرا در Colab نیازی به آپلود فایل نیست.

</div>
