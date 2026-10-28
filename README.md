# TaskHub 🚀

> **Fast, privacy-focused, zero-token personal task & reminder application for Windows, macOS & Android.**

TaskHub lets you quickly dump your thoughts in natural conversational Persian (e.g. `فردا ساعت ۱۰ جلسه با تیم`, `۲ ساعت دیگه تماس با دکتر`) and automatically schedules reminders with zero AI token overhead.

---

## 📥 دانلود نسخه‌های آماده (Official Downloads - v1.5.1)

| پلتفرم | لینک دانلود مستقیم | فرمت | توضیحات |
| :--- | :--- | :--- | :--- |
| 🖥️ **سرور مرکزی (Server)** | [**دانلود TaskHub-Server.exe**](https://github.com/Moein-Hosseinzade/taskhub-app/releases/download/v1.5.0/TaskHub-Server.exe) | `.exe` (18 MB) | سرور پرتابل مستقل (بدون نیاز به پایتون)، مدیریت دیتابیس و وب‌سوکت |
| 💻 **کلاینت ویندوز (Windows)** | [**دانلود TaskHub-Windows.exe**](https://github.com/Moein-Hosseinzade/taskhub-app/releases/download/v1.5.1/TaskHub-Windows.exe) | `.exe` (24 MB) | نسخه جدید v1.5.1، صف آفلاین Outbox، تب‌های فیلتر، رفع باگ رول‌اور و سیستم ترِی |
| ⚡ **کلاینت نیتیو مک (macOS Swift)** | [**دانلود TaskHubSwift-v1.5.0.dmg**](https://github.com/Moein-Hosseinzade/taskhub-app/releases/download/v1.5.1/TaskHubSwift-v1.5.0.dmg) | `.dmg` (1.2 MB) | نسخه بومی فوق‌سبک Swift/SwiftUI مک همراه با Outbox و تست تاخیر پینگ |
| 🍎 **کلاینت مک (macOS - DMG)** | [**دانلود TaskHub-v1.5.0.dmg**](https://github.com/Moein-Hosseinzade/taskhub-app/releases/download/v1.5.1/TaskHub-v1.5.0.dmg) | `.dmg` (19 MB) | پکیج رسمی نصبی macOS، صف آفلاین Outbox، یکپارچه با Menu Bar |
| 🍏 **کلاینت مک (macOS - ZIP)** | [**دانلود TaskHub-v1.5.0-macos.zip**](https://github.com/Moein-Hosseinzade/taskhub-app/releases/download/v1.5.1/TaskHub-v1.5.0-macos.zip) | `.zip` (19 MB) | آرشیو پرتابل `TaskHub.app` جهت اجرای مستقیم بدون نصب |
| 📱 **اپ اندروید (Android)** | [**دانلود TaskHub-Android.apk**](https://github.com/Moein-Hosseinzade/taskhub-app/releases/download/v1.5.1/TaskHub-Android.apk) | `.apk` (18 MB) | نسخه جدید v1.5.1، صف Outbox با WorkManager، ایمن‌سازی اتصال، آلارم قطعی و رفع باگ رول‌اور |

> همچنین می‌توانید فایل‌ها را از پوشه [releases/](releases/) یا بخش [Releases گیت‌هاب](https://github.com/Moein-Hosseinzade/taskhub-app/releases) نیز مستقیماً دریافت کنید.

---

## ✨ امکانات و قابلیت‌ها (Features)

### 1. 🧠 پردازش زبان طبیعی فارسی (Zero-AI / ۱۰۰٪ محلی)
- درک اصطلاحات محاوره‌ای فارسی بدون نیاز به هوش مصنوعی و اینترنت:
  - `فردا ساعت ۱۰ جلسه با علی`
  - `پس‌فردا ساعت ۵ عصر خرید نان`
  - `۲ ساعت دیگه تماس فوری`
  - `شنبه ساعت ۹ صبح دکتر`
- تشخیص خودکار ساعت‌های تقریبی (`صبح`, `ظهر`, `عصر`, `غروب`, `شب`).
- برچسب‌گذاری هوشمند تاریخ‌های نسبی شمسی.

### 2. 💻 نسخه دسکتاپ ویندوز (Windows Client)
- رابط کاربری مدرن با پشتیبانی کامل از چینش راست‌به‌چپ (RTL) و فونت فارسی وزیرمتن.
- **تنظیم دستی آدرس سرور مرکزی (Server URL) و API Key اختیاری** از طریق آیکون چرخ‌دنده (⚙️).
- ذخیره پایدار آدرس سرور در `%APPDATA%/PersonalTaskHub/config.json`.
- قرارگیری در بخش System Tray و اجرای مداوم در پس‌زمینه.
- نوتیفیکیشن‌های بومی ویندوز برای سررسید تسک‌ها.
- **انتخاب چندتایی و حذف گروهی تسک‌ها** با کلیدهای میانبر (Ctrl/Shift Click) و نوار ابزار هوشمند.

### 3. 🍎 نسخه دسکتاپ مکینتاش (macOS Client)
- پورت اختصاصی برای سیستم‌عامل **macOS** با آیکون منوبار بومی (`NSStatusBar` و `NSMenu`).
- ارسال نوتیفیکیشن‌های سیستم از طریق Notification Center مک با AppleScript.
- پشتیبانی کامل از چینش راست‌به‌چپ فارسی، تنظیمات سرور و حذف چندتایی تسک‌ها.
- ذخیره‌سازی استاندارد پیکربندی در `~/Library/Application Support/PersonalTaskHub/config.json`.

### 4. 📱 نسخه موبایل اندروید (Android Native App)
- طراحی منطبق بر **Material 3** با انیمیشن‌های روان.
- **هسته آلارم قطعی (`AlarmManager.setExactAndAllowWhileIdle`):** هشدارها حتی در حالت خواب عمیق گوشی (Doze Mode) دقیقاً سر موعد زنگ می‌خورند.
- **تایل دسترسی سریع (Quick Settings Tile):** ثبت سریع تسک از کنترل‌سنتر بالای گوشی بدون نیاز به باز کردن برنامه.
- **حالت انتخاب چندتایی (Contextual Action Bar):** انتخاب با نگه داشتن انگشت روی تسک و حذف دسته‌جمعی با تاییدیه امنیتی.
- ذخیره‌سازی آفلاین با پایگاه داده محلی Room.
- تنظیم آدرس سرور دلخواه و اتصال مستقیم در شبکه وای‌فای یا اینترنت.

### 5. ⚡ سینک آنی دوطرفه (Real-time Live Sync)
- همگام‌سازی لحظه‌ای بر بستر وب‌سوکت؛ هر تغییری در ویندوز یا مک در کمتر از ۳۰ میلی‌ثانیه روی گوشی اعمال می‌شود و بالعکس.

---

## 🚀 راهنمای راه‌اندازی و تست ۳ مرحله‌ای

1. **اجرای سرور مرکزی:** فایل `TaskHub-Server.exe` را اجرا کنید (پنجره سرور باز شده و دیتابیس و وب‌سوکت روی پورت ۸۰۰۰ آماده به کار می‌شوند).
2. **اجرای کلاینت ویندوز یا مک:** فایل `TaskHub-Windows.exe` یا `TaskHub-macOS.dmg` را باز کرده؛ در صورت نیاز با کلیک روی آیکون ⚙️ آدرس سرور را تعیین نمایید (پیش‌فرض: `http://127.0.0.1:8000`).
3. **اتصال اپلیکیشن اندروید:** فایل `TaskHub-Android.apk` را روی گوشی نصب کنید؛ در تنظیمات (⚙️) آدرس IP کامپیوتر خود در شبکه وای‌فای را وارد نمایید (مثال: `http://192.168.1.50:8000`). نشانگر به `سینک آنی فعال 🟢` تغییر کرده و تمام اطلاعات هماهنگ می‌شوند.

---

## 🔒 حریم خصوصی
تمام اطلاعات شما در پایگاه‌داده محلی خودتان ذخیره می‌شود و هیچ داده‌ای به هیچ سرور متفرقه‌ای ارسال نمی‌گردد.
