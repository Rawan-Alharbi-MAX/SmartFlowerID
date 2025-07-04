# SmartFlowerID
 A simple AI project that uses a Keras-based model to classify two types of Japanese flowers: the Higanbana (red spider lily) and the yellow spider lily, based on image input.
# 🌸 AI Flower Classification Project - تصنيف الأزهار بالذكاء الاصطناعي

مشروع بسيط يستخدم نموذج مدرّب مسبقًا باستخدام Keras لتصنيف الصور بين نوعين من الزهور اليابانية:

1. زهرة الموت (Higanbana)
2. زهرة الليلك العنكبوتي الأصفر

## 🔧 المتطلبات

- Python 3.7+
- TensorFlow 2.12.1
- Pillow
- NumPy
- Google Colab أو Jupyter Notebook (مفضل لتشغيل الكود مباشرة)

## 📁 الملفات

- `Task1AIprojectCode.ipynb` : كود المشروع الأساسي.
- `keras_model.h5` : النموذج المدرّب.
- `labels.txt` : ملف الفئات/التصنيفات.
- `output.png` : صورة مستخدمة للاختبار.

## 🧠 طريقة العمل

1. تحميل النموذج والملفات.
2. تحميل الصورة (مقاس 224x224).
3. تطبيع الصورة وتحويلها إلى مصفوفة.
4. تمرير الصورة للنموذج للتنبؤ.
5. طباعة اسم الزهرة ونسبة الثقة.

## 📸 مثال على المخرجات
Class: زهرة الليلك العنكبوتي الأصفر
Confidence Score: 0.99999094

<img width="957" alt="output" src="https://github.com/user-attachments/assets/b8f70218-477e-4dbb-a488-ebeeedcd993d" />

## ✅ طريقة التشغيل

1. افتح `Task1AIprojectCode.ipynb` باستخدام Google Colab.
2. تأكد من رفع الملفات التالية:
   - `keras_model.h5`
   - `labels.txt`
   - صورة الاختبار
3. شغّل جميع الخلايا.

## 📝 ملاحظات

- تأكد من أن الصورة بصيغة JPG أو PNG.
- حجم الصورة يُعدّل تلقائيًا إلى 224x224 قبل التنبؤ.

## 🧠 النموذج

تم إنشاء النموذج باستخدام Teachable Machine من Google، ثم تم تصديره بصيغة `Keras` لتضمينه في هذا المشروع.

---

## 👤 المبرمج

- الاسم: *(روان الحربي)*
- التاريخ: يوليو 2025
