# 🦅 Griffin-ATR Validator

**Griffin-ATR Validator** is a precision tool in **Pine Script** for **TradingView**, developed from the heart of market volatility.
This indicator helps you focus only on candles that truly have **power** and **certainty**, not just random market noise.

---

## 📖 About The Project

In the busy world of financial markets, not all price movements are of equal value. Many candles only show uncertainty or random fluctuations. **Griffin-ATR Validator** is built to filter out these worthless movements.
---

## ⚙️ How It Works

Each candle is validated based on two main rules, and only if both rules are met will a signal be displayed:

### 1️⃣ Law of Power

The body of the candle must be **greater than or equal to the ATR**.

```
Body Size >= ATR
```

### 2️⃣ Law of Conviction

The adverse shadow of the candle must be **less than or equal to ATR**.

* Bullish candle → upper shadow
* Bearish candle → lower shadow

```
Adverse Shadow <= ATR
```

---

## ✨ Features

✅ **High certainty signals** – only candles with real strength and close are displayed.
✅ **Dynamic volatility filter** – use ATR according to any timeframe and market conditions.
✅ **Simple visual alerts** – display an "OK" triangle on valid candles.
✅ **Live information table** – display ATR, body size and shadow in the corner of the chart with status color.
✅ **Full customization** – ability to change the ATR period to suit your trading style.

---

## 🚀 How to Use

1. Log in to [TradingView](https://www.tradingview.com/).
2. Open **Pine Editor** from the bottom of the page.
3. Copy the full code in the `.pine` file.
4. Paste it into Pine Editor.
5. Click **"Add to Chart"**.

---

## 📜 License

This project is released to help the trading community and is licensed under the **GNU General Public License v3.0**.

More details are available in the `LICENSE.txt` file.



# 🦅 Griffin-ATR Validator

**Griffin-ATR Validator** یک ابزار دقیق در **Pine Script** برای **TradingView** است که از دل نوسانات بازار شکل گرفته.
این اندیکاتور به شما کمک می‌کند تنها روی کندل‌هایی تمرکز کنید که واقعاً **قدرت** و **قطعیت** دارند، نه صرفاً نویزهای بی‌هدف بازار.

---

## 📖 About The Project

در دنیای شلوغ بازارهای مالی، همه‌ی حرکات قیمت ارزش یکسانی ندارند. بسیاری از کندل‌ها فقط تردید یا نوسان‌های تصادفی را نشان می‌دهند. **Griffin-ATR Validator** برای فیلتر کردن همین حرکات بی‌ارزش ساخته شده است.
---

## ⚙️ How It Works

هر کندل بر اساس دو قانون اصلی اعتبارسنجی می‌شود و تنها در صورت رعایت هر دو قانون، سیگنال نمایش داده خواهد شد:

### 1️⃣ قانون قدرت (Law of Power)

بدنه‌ی کندل باید **بزرگ‌تر یا مساوی ATR** باشد.

```
Body Size >= ATR
```

### 2️⃣ قانون قطعیت (Law of Conviction)

سایه‌ی مخالف کندل باید **کمتر یا مساوی ATR** باشد.

* کندل صعودی → سایه‌ی بالا
* کندل نزولی → سایه‌ی پایین

```
Adverse Shadow <= ATR
```

---

## ✨ Features

✅ **سیگنال‌های با قطعیت بالا** – فقط کندل‌هایی با قدرت و بسته‌شدن واقعی نمایش داده می‌شوند.
✅ **فیلتر داینامیک نوسان** – استفاده از ATR متناسب با هر تایم‌فریم و شرایط بازار.
✅ **هشدارهای تصویری ساده** – نمایش مثلث "OK" روی کندل‌های معتبر.
✅ **جدول اطلاعات زنده** – نمایش ATR، اندازه بدنه و سایه در گوشه نمودار با رنگ‌بندی وضعیت.
✅ **شخصی‌سازی کامل** – قابلیت تغییر دوره‌ی ATR مطابق با سبک معاملاتی شما.

---

## 🚀 How to Use

1. وارد [TradingView](https://www.tradingview.com/) شوید.
2. از پایین صفحه، **Pine Editor** را باز کنید.
3. کد کامل موجود در فایل `.pine` را کپی کنید.
4. آن را در Pine Editor قرار دهید.
5. روی **"Add to Chart"** کلیک کنید.

---

## 📜 License

این پروژه برای کمک به جامعه‌ی تریدرها منتشر شده و تحت **GNU General Public License v3.0** قرار دارد.

جزئیات بیشتر در فایل `LICENSE.txt` موجود است.

