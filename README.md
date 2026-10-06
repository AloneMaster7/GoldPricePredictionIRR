# 🪙 18K Gold Price Prediction with AI

> 🤖 **AI-based technical analysis and price forecasting for 18K gold using PyTorch & Bidirectional GRU**

مدلی برای **تحلیل تکنیکال و پیش‌بینی قیمت هر گرم طلای ۱۸ عیار** با استفاده از یادگیری عمیق و پردازش سری‌های زمانی.

💰 **واحد قیمت:** ریال ایران (IRR)

---

## ✨ Features

* 📈 تحلیل سری زمانی قیمت طلا
* 🧠 شبکه عصبی **Bidirectional GRU**
* 🔮 پیش‌بینی هم‌زمان قیمت **۳ روز آینده**
* 📊 استخراج ویژگی‌های تکنیکال
* ⚙️ استفاده از PyTorch و Scikit-learn
* 📉 ارزیابی مدل با MAPE و MAE
* 🎯 محاسبه Directional Accuracy

---

## 📊 Technical Features

مدل از ترکیبی از داده‌های قیمت و اندیکاتورهای تکنیکال استفاده می‌کند:

`Open` · `High` · `Low` · `Close` · `Returns` · `Moving Averages` · `RSI` · `Volatility` · `Price Range`

---

## 🗂️ Dataset

از آنجا که دیتاست آماده و مناسب برای این پروژه در دسترس نبود، داده‌های تاریخی قیمت به‌صورت دستی از بخش **History** یک منبع آنلاین قیمت طلا در ایران جمع‌آوری و در قالب CSV آماده شده‌اند.

📅 **آخرین داده موجود: ۱۴ مهر ۱۴۰۵**

💰 تمام قیمت‌های دیتاست بر حسب **ریال ایران (IRR)** هستند.

---

## 🧠 Model

مدل با استفاده از **۲۰ روز گذشته**، قیمت **۳ روز آینده** را به‌صورت Multi-Output پیش‌بینی می‌کند:

```text
📊 Historical Data
       │
       ▼
⚙️ Feature Engineering
       │
       ▼
🧠 Bidirectional GRU
       │
       ▼
🔮 Multi-Output Prediction
       │
       ├── Day +1
       ├── Day +2
       └── Day +3
```

---

## 🛠️ Technologies

| Technology      | Usage               |
| --------------- | ------------------- |
| 🐍 Python       | Core                |
| 🔥 PyTorch      | Deep Learning       |
| 🐼 Pandas       | Data Processing     |
| 🔢 NumPy        | Numerical Computing |
| 📐 Scikit-learn | Data Scaling        |

---

## ⚠️ Disclaimer

این پروژه با هدف **آموزشی و پژوهشی** توسعه داده شده است.

پیش‌بینی قیمت بازار دارای عدم قطعیت است و خروجی مدل **توصیه مالی یا تضمین قیمت آینده** محسوب نمی‌شود.

---

## 📄 License

This project is licensed under the **MIT License**.

---

⭐ اگر این پروژه برایتان جالب بود، خوشحال می‌شوم به آن Star بدهید.
