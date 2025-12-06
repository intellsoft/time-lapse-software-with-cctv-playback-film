# 📽️ نرم‌افزار ساخت تایم‌لیپس از دوربین‌های مداربسته (CCTV Timelapse)

<div dir="rtl">

## 🚀 معرفی
نرم‌افزار **Timelapse Playback Pro** یک ابزار حرفه‌ای برای ساخت ویدیوهای تایم‌لیپس از فیلم‌های ضبط شده دوربین‌های مداربسته هایک‌ویژن و داهوا است. این نرم‌افزار با استفاده از قابلیت Playback دوربین‌ها، تصاویر را در بازه‌های زمانی مشخص استخراج کرده و به صورت خودکار تایم‌لیپس تولید می‌کند.

🔗 **صفحه محصول:** [https://intellsoft.ir/product/time-lapse-software-with-cctv-playback-film/](https://intellsoft.ir/product/time-lapse-software-with-cctv-playback-film/)

## ✨ ویژگی‌های اصلی
- ✅ **پشتیبانی از دوربین‌های هایک‌ویژن و داهوا** - سازگار با مدل‌های مختلف
- ✅ **پردازش موازی کانال‌ها** - استخراج همزمان از چندین کانال
- ✅ **رابط کاربری مدرن و فارسی** - طراحی زیبا و کاربرپسند با CustomTkinter
- ✅ **سیستم مدیریت لایسنس** - محافظت از نرم‌افزار با احراز هویت سخت‌افزاری
- ✅ **پردازش هوشمند** - شناسایی خودکار فرمت‌های RTSP مختلف
- ✅ **گزارش‌گیری کامل** - نمایش آمار و لاگ‌های عملیاتی
- ✅ **ذخیره خودکار تنظیمات** - با رمزنگاری پیشرفته
- ✅ **پشتیبانی از ۶۴ کانال** - انتخاب چند کاناله با امکان انتخاب انعطاف‌پذیر

## 🛠️ فناوری‌های استفاده شده
- **Python 3** + **Tkinter**/**CustomTkinter** برای رابط کاربری
- **FFmpeg** برای استخراج فریم‌ها از streams RTSP
- **Cryptography** برای سیستم لایسنس و رمزنگاری
- **Threading** + **Concurrent Futures** برای پردازش موازی
- **JSON** + **Fernet Encryption** برای ذخیره امن تنظیمات

## 🎯 نحوه استفاده
1. **تنظیمات دوربین**: وارد کردن IP، کاربری، رمز عبور و پورت
2. **انتخاب کانال‌ها**: انتخاب یک یا چند کانال از بین ۶۴ کانال
3. **تنظیم بازه زمانی**: انتخاب تاریخ و ساعت شروع و پایان
4. **تعیین فاصله**: تنظیم فاصله زمانی بین تصاویر (ثانیه، دقیقه، ساعت)
5. **شروع فرآیند**: کلیک روی دکمه شروع و مشاهده پیشرفت

## 🔒 سیستم لایسنس
نرم‌افزار از سیستم لایسنس سخت‌افزار محور استفاده می‌کند که بر اساس:
- شناسه پردازنده (CPU ID)
- شماره سریال مادربرد
ایجاد می‌شود. فایل لایسنس (`lic.enc`) باید در کنار فایل اجرایی قرار گیرد.

## 📊 خروجی
تصاویر استخراج شده در پوشه‌هایی با ساختار زیر ذخیره می‌شوند:
```
مسیر_ذخیره‌سازی/
├── IP_دوربین/
│   └── timelapse/
│       ├── Channel_1/
│       ├── Channel_2/
│       └── ...
```

## 🤝 مشارکت
برای گزارش باگ یا پیشنهاد ویژگی‌های جدید، لطفاً از طریق صفحه محصول با ما در ارتباط باشید.

## 📞 پشتیبانی
- 🌐 وبسایت: [intellsoft.ir](https://intellsoft.ir)
- 📧 ایمیل: از طریق فرم تماس در وبسایت

## 📄 مجوز
این نرم‌افزار دارای مجوز اختصاصی است. هرگونه کپی، توزیع یا تغییر بدون مجوز ممنوع است.

---
**توسعه‌دهنده:** علی عباس‌پور  
**تبدیل دوربین‌های مداربسته به ابزارهای خلاقانه**

</div>

---

# 📽️ CCTV Timelapse Playback Software

## 🚀 Introduction
**Timelapse Playback Pro** is a professional software for creating timelapse videos from recorded footage of Hikvision and Dahua CCTV cameras. The software extracts images at specified intervals using the camera's playback feature and automatically generates timelapse videos.

🔗 **Product Page:** [https://intellsoft.ir/product/time-lapse-software-with-cctv-playback-film/](https://intellsoft.ir/product/time-lapse-software-with-cctv-playback-film/)

## ✨ Key Features
- ✅ **Hikvision & Dahua Camera Support** - Compatible with various models
- ✅ **Parallel Channel Processing** - Simultaneous extraction from multiple channels
- ✅ **Modern Persian/English UI** - Beautiful design with CustomTkinter
- ✅ **License Management System** - Hardware-based authentication protection
- ✅ **Smart Processing** - Automatic detection of different RTSP formats
- ✅ **Complete Reporting** - Statistics and operational logs display
- ✅ **Auto-save Settings** - With advanced encryption
- ✅ **64-Channel Support** - Multi-channel selection with flexible options

## 🛠️ Technologies Used
- **Python 3** + **Tkinter**/**CustomTkinter** for GUI
- **FFmpeg** for frame extraction from RTSP streams
- **Cryptography** for license system and encryption
- **Threading** + **Concurrent Futures** for parallel processing
- **JSON** + **Fernet Encryption** for secure settings storage

## 🎯 How to Use
1. **Camera Settings**: Enter IP, username, password, and port
2. **Channel Selection**: Select one or multiple channels from 64 available
3. **Time Range**: Choose start and end date/time
4. **Interval Setting**: Set time interval between images (seconds, minutes, hours)
5. **Start Process**: Click start button and monitor progress

## 🔒 License System
The software uses hardware-based licensing system based on:
- Processor ID (CPU ID)
- Motherboard Serial Number
License file (`lic.enc`) must be placed alongside the executable.

## 📊 Output
Extracted images are saved in the following structure:
```
Save_Path/
├── Camera_IP/
│   └── timelapse/
│       ├── Channel_1/
│       ├── Channel_2/
│       └── ...
```

## 🤝 Contribution
For bug reports or feature suggestions, please contact us through the product page.

## 📞 Support
- 🌐 Website: [intellsoft.ir](https://intellsoft.ir)
- 📧 Email: Via contact form on website

## 📄 License
This software is proprietary. Any copying, distribution, or modification without permission is prohibited.

---
**Developer:** Ali Abbaspour  
**Converting CCTV Cameras into Creative Tools**