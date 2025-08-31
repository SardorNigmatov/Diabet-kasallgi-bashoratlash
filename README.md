# Diabet Kasalligini Bashoratlash (Pima Indian Dataset)

## ℹ Maqsad
Pima Indian Diabetes Dataset asosida (faqat 21 yoshdan katta ayollar) diagnostik o‘lchovlardan foydalangan holda bemorda diabet bor-yo‘qligini bashorat qilish.

---

##  Dataset haqida
- Manba: NIDDK (Milliy Qandli Diabet va Buеrak Kasalliklari Instituti) :contentReference[oaicite:5]{index=5}.
- Bemorlar: Kamida 21 yoshli Pima Indian ayollar.
- Sifatlar (features): 
  - Homilasizlik soni (Pregnancies)
  - Qon shakar (Glucose)
  - Qon bosimi (BloodPressure)
  - Terining qalinligi (SkinThickness)
  - Insulin darajasi (Insulin)
  - BMI (Body Mass Index)
  - Diabetning nasldan-o‘tish koeffitsienti (DiabetesPedigreeFunction)
  - Yoshi (Age)
- Maqsad (Outcome): Diabet bor yoki yo‘qligi (1 yoki 0) :contentReference[oaicite:6]{index=6}.

---

##  Loyihaning tarkibi
- `data/` – `diabetes.csv` (dataset)
- `notebook.ipynb` – tahlil, vizualizatsiya va model sinovi
- `train.py` – modelni o‘rgatish
- `predict.py` – yangi ma’lumotlar asosida bashorat qilish
- `requirements.txt` – kerakli kutubxonalar

---

##  Ishga tushirish (Quick Start)
```bash
git clone https://github.com/SardorNigmatov/Diabet-kasallgi-bashoratlash.git
cd Diabet-kasallgi-bashoratlash
pip install -r requirements.txt
