<div align="center">

# 💚 Kick Chat Viewer

**A clean, real-time Kick chat viewer with a modern glass UI.**

[![English](https://img.shields.io/badge/Language-English-53fc18?style=for-the-badge)](#-english)
[![Persian](https://img.shields.io/badge/Language-Persian-53fc18?style=for-the-badge)](#-persian)

</div>

---

## 🇬🇧 English

### ✨ What is this?

A lightweight, single-file web app that lets you watch **any Kick streamer's chat** in a clean, modern interface — no login, no ads, no bloat. Just type a username and you're in.

Built with vanilla JavaScript + jQuery, styled with a glassmorphic dark theme, and powered by Kick's public API + Pusher WebSocket for real-time messages.

### 🚀 Features

- 💬 **Real-time chat** — messages arrive instantly via WebSocket
- 🎨 **Modern glass UI** — translucent surfaces, animated gradient orbs, smooth transitions
- 😀 **Emote support** — native Kick emotes **and** 7TV emotes
- 🏅 **Badges** — broadcaster, moderator, VIP, subscriber (with month tiers), OG, founder, verified, bot
- 📌 **Pinned messages** — displayed in a dedicated card
- 🗑️ **Moderation view** — deleted / banned messages shown with strikethrough
- ↩️ **Replies** — threaded reply previews
- 📊 **Live viewer count** — auto-refreshes every minute
- 🌐 **Offline detection** — shows a separator when stream goes offline
- 📱 **Fully responsive** — works on desktop and mobile
- 🚪 **Home button** — quick navigation back to the start
- 💚 **Made with love** — by [DouMeem](https://donofa.com/doumeem)

### 🖥️ How to use

1. Open the page.
2. Type a Kick username in the input field.
3. Press **Open Chat**.
4. Watch the chat stream in real-time.

You can also deep-link directly to a streamer's chat:
https://doumeem.github.io/chat/?streamer=USERNAME


### 🔗 URL Parameters

| Parameter   | Purpose                                  |
| ----------- | ---------------------------------------- |
| `?streamer` | Opens the chat for the given Kick user   |
| `?unknown`  | Shows the "User Not Found" error screen  |
| `?connection` | Shows the "Connection Failed" screen   |

### ⚠️ Notes

- The app uses **Kick's public API** — if Kick changes endpoints, things may break.
- If you're in **Iran**, you'll likely need a VPN to reach Kick's servers.
- All chat content belongs to Kick and its users. This is just a viewer.

### 💚 Support

If you enjoy this, consider supporting the developer:

👉 **[donofa.com/doumeem](https://donofa.com/doumeem)**

---

## 🇮🇷 Persian

<div dir="rtl">

### ✨ این چیه؟

یک اپلیکیشن سبک و تک‌فایلی که بهت اجازه می‌ده **چت هر استریمری در کیک** رو با یک رابط کاربری تمیز و مدرن تماشا کنی — بدون لاگین، بدون تبلیغ، بدون دردسر. فقط یوزرنیم رو وارد کن و تمام.

با JavaScript خالص و jQuery ساخته شده، با یک تم شیشه‌ای تیره (glassmorphic) استایل خورده، و از API عمومی کیک + وب‌سوکت Pusher برای پیام‌های لحظه‌ای استفاده می‌کنه.

### 🚀 امکانات

- 💬 **چت لحظه‌ای** — پیام‌ها آنی از طریق WebSocket می‌رسن
- 🎨 **رابط کاربری مدرن شیشه‌ای** — سطوح نیمه‌شفاف، اورب‌های گرادیانتی متحرک، ترنزیشن‌های نرم
- 😀 **پشتیبانی از ایموت** — ایموت‌های خود کیک **و** ایموت‌های 7TV
- 🏅 **بج‌ها** — استریمر، مدیر، VIP، سابسکرایبر (با سطح ماهانه)، OG، فاندر، وریفای، ربات
- 📌 **پیام‌های پین‌شده** — در یک کارت اختصاصی نمایش داده می‌شن
- 🗑️ **نمایش مدیریت** — پیام‌های حذف‌شده / بن‌شده با خط‌خورده نشون داده می‌شن
- ↩️ **پاسخ‌ها** — پیش‌نمایش پاسخ‌های تردی
- 📊 **شمارش زنده بیننده** — هر دقیقه آپدیت می‌شه
- 🌐 **تشخیص آفلاین** — وقتی استریم آفلاین می‌شه یک جداکننده نشون می‌ده
- 📱 **کاملاً ریسپانسیو** — روی دسکتاپ و موبایل کار می‌کنه
- 🚪 **دکمه خانه** — دسترسی سریع به صفحه اصلی
- 💚 **ساخته‌شده با عشق** — توسط [DouMeem](https://donofa.com/doumeem)

### 🖥️ نحوه استفاده

1. صفحه رو باز کن.
2. یوزرنیم کیک رو در فیلد ورودی وارد کن.
3. روی **Open Chat** بزن.
4. چت رو به صورت زنده تماشا کن.

همچنین می‌تونی مستقیم به چت یک استریمر بری:
https://doumeem.github.io/chat/?streamer=USERNAME


### 🔗 پارامترهای URL

| پارامتر      | کاربرد                                    |
| ------------ | ----------------------------------------- |
| `?streamer`  | چت یوزر مورد نظر رو در کیک باز می‌کنه     |
| `?unknown`   | صفحه‌ی خطای «کاربر پیدا نشد» رو نشون می‌ده |
| `?connection`| صفحه‌ی «اتصال ناموفق» رو نشون می‌ده        |

### ⚠️ نکات

- این اپ از **API عمومی کیک** استفاده می‌کنه — اگه کیک اندپوینت‌ها رو تغییر بده، ممکنه خراب بشه.
- اگه در **ایران** هستی، احتمالاً به VPN نیاز داری تا به سرورهای کیک وصل بشی.
- تمام محتوای چت متعلق به کیک و کاربرانشه. این فقط یک ویوئره.

### 💚 حمایت

اگه از این لذت می‌بری، می‌تونی از دولوپر حمایت کنی:

👉 **[donofa.com/doumeem](https://donofa.com/doumeem)**

</div>

---

<div align="center">

Made with 💚 by [DouMeem](https://donofa.com/doumeem)

</div>
