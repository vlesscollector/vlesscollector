<div align="center">

#⚡️ Vless Collector

### 🛰️ **Automatic VLESS Config Scanner & Updater**
#### جمع‌آوری، تست، و به‌روزرسانی خودکار کانفیگ‌های رایگان VLESS

[![Telegram](https://img.shields.io/badge/Telegram%20Bot-Join%20Now-blue?logo=telegram&style=for-the-badge)](https://t.me/vlessconfigcollectorbot)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/vlesscollector/vlesscollector?style=for-the-badge)](https://github.com/vlesscollector/vlesscollector/stargazers)

</div>

---

## 📖 توضیحات پروژه

پروژه **Vless Collector** یک ابزار هوشمند و خودکار است که کانفیگ‌های **VLESS**  
(پروتکل پروکسی مبتنی بر V2Ray/V2Fly) را از سراسر اینترنت جمع‌آوری، تست و فیلتر می‌کند.  

✅ **هدف:** شناسایی و اشتراک‌گذاری فقط کانفیگ‌های سالم و فعال از منابع عمومی.

---

## 📦 خروجی‌های پروژه

- 🧾 **فایل TXT:**  
  لیست کامل کانفیگ‌های VLESS (base64-encoded) برای استفاده مستقیم.

- 🔗 **لینک Subscription:**  
  مناسب برای کلاینت‌های V2Ray مثل **V2RayN**, **Qv2ray**, یا **Nekobox**.  

   ```
https://raw.githubusercontent.com/vlesscollector/vlesscollector/refs/heads/main/vless_configs.txt
   ```

- 🤖 **ربات Telegram:**  
دسترسی آسان به لیست کانفیگ‌ها از طریق ربات تلگرام 👇  
[🔹 Telegram Bot – VLESS Config Collector](https://t.me/vlessconfigcollectorbot)

---

## 🧠 ویژگی‌ها

- 🌐 جمع‌آوری از منابع عمومی (فروم‌ها، گیت‌هاب‌ها، وب‌سایت‌ها)
-⚙️ تست خودکار برای اطمینان از فعال بودن کانفیگ‌ها (ping / latency)
- 🧩 خروجی به فرمت‌های استاندارد V2Ray
- 🔁 به‌روزرسانی خودکار با **GitHub Actions** یا **local scripts**
- 💡 طراحی ماژولار و قابل گسترش

---

## 🚀 نحوه استفاده

1. لینک subscription بالا را در کلاینت V2Ray خود وارد کنید.  
2. هر بار به‌صورت خودکار کانفیگ‌های سالم جدید دریافت خواهید کرد.  
3. از بخش **Logs** کلاینت می‌توانید اتصال‌ها را مانیتور کنید.

> ⚙️ **مثال:**  
> در V2RayN، وارد تب Subscription شوید → روی Add کلیک کنید → لینک بالا را Paste کنید.

---

## ⚠️ هشدارهای امنیتی

> ⚠️ **مهم:** تمام کانفیگ‌ها از منابع عمومی اینترنت استخراج می‌شوند. ما مالک هیچ‌کدام نیستیم!

🔒 **ریسک‌های احتمالی:**
- سرورهای مخرب یا جاسوسی  
- نقض حریم خصوصی  
- حملات MITM یا سرقت داده  

🚫 **توصیه:**  
از این ابزار فقط برای اهداف آموزشی یا تست استفاده کنید.  
برای استفاده واقعی، از سرویس‌های معتبر و امن VPN استفاده نمایید.

---

## 🤝 کمک و مشارکت

- 🐞 اگر باگی مشاهده کردید، لطفاً [Issue](https://github.com/vlesscollector/vlesscollector/issues) باز کنید.  
- 🧩 برای افزودن قابلیت جدید، **Pull Request** ارسال کنید.  
- 💬 سؤالات خود را در بخش **Discussions** مطرح کنید.

---

## ⚖️ مجوز

این پروژه تحت مجوز **MIT** منتشر شده است.  
📄 برای جزئیات بیشتر، فایل `LICENSE` را ببینید.

---

<div align="center">

✨ ساخته‌شده با ❤️ توسط [ما](https://github.com/vlesscollector) ✨  
📡 قدرت‌گرفته از **GitHub Actions** + **V2Ray**

</div>
