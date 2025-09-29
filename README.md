# ویکی لایسنس (WikiLicense)

[![Website](https://img.shields.io/badge/Website-wikilicense.ir-blue)](https://wikilicense.ir/)
[![License](https://img.shields.io/badge/License-GPL--3.0-green.svg)](LICENSE)
[![Language](https://img.shields.io/badge/Language-Persian-red.svg)](https://github.com/MahdiMajidzadeh/wikilicense)

دیکشنری جامع لایسنس‌های نرم‌افزاری و محتوا به زبان فارسی همراه با توضیحات کامل و قابل فهم.

## 📖 درباره پروژه

ویکی لایسنس یک پروژه منبع باز است که هدف آن ارائه اطلاعات جامع و قابل فهم درباره لایسنس‌های نرم‌افزاری و محتوا به زبان فارسی است. این پروژه به عنوان یک دیکشنری کامل عمل می‌کند و به توسعه‌دهندگان، طراحان، نویسندگان و کاربران فارسی‌زبان کمک می‌کند تا بتوانند لایسنس‌های مختلف را بهتر درک کنند و انتخاب مناسبی برای پروژه‌های خود داشته باشند.

### ویژگی‌های کلیدی

- **جامعیت**: پوشش کامل لایسنس‌های مهم نرم‌افزاری و محتوا
- **دسته‌بندی**: تقسیم‌بندی لایسنس‌ها بر اساس نوع و شدت محدودیت‌ها
- **توضیحات فارسی**: ترجمه و توضیح کامل هر لایسنس به زبان فارسی
- **مقایسه**: امکان مقایسه ویژگی‌ها و محدودیت‌های مختلف لایسنس‌ها
- **به‌روزرسانی**: نگهداری و به‌روزرسانی مداوم محتوا

## 🌐 وب‌سایت

پروژه در آدرس [wikilicense.ir](https://wikilicense.ir/) در دسترس است.

## 📋 لایسنس‌های موجود

### لایسنس‌های نرم‌افزاری

#### لایسنس‌های Copyleft (قوی)
- **GNU General Public License v2.0** - لایسنس copyleft کلاسیک
- **GNU General Public License v3.0** - لایسنس copyleft با حمایت از حق ثبت اختراع
- **GNU Affero General Public License v3.0** - لایسنس copyleft برای سرویس‌های آنلاین
- **GNU Lesser General Public License v2.1** - لایسنس copyleft کلاسیک برای کتابخانه‌ها
- **GNU Lesser General Public License v3.0** - لایسنس copyleft برای کتابخانه‌ها
- **Mozilla Public License 2.0** - لایسنس copyleft متعادل
- **Eclipse Public License 2.0** - لایسنس copyleft متوسط
- **Artistic License 2.0** - لایسنس copyleft برای پروژه‌های Perl
- **CeCILL License 2.1** - لایسنس copyleft فرانسوی

#### لایسنس‌های Permissive (آزاد)
- **MIT License** - لایسنس ساده و کوتاه با حداقل محدودیت‌ها
- **Apache License 2.0** - لایسنس انعطاف‌پذیر با حمایت از ثبت تغییرات
- **BSD 0-Clause** - لایسنس بدون محدودیت
- **BSD 2-Clause** - لایسنس ساده با دو شرط
- **BSD 3-Clause** - لایسنس با محدودیت تبلیغاتی
- **ISC License** - لایسنس ساده و کوتاه
- **Boost Software License 1.0** - لایسنس برای کتابخانه‌های C++
- **Zlib License** - لایسنس ساده برای کتابخانه‌های کوچک
- **PostgreSQL License** - لایسنس برای پروژه PostgreSQL

#### لایسنس‌های عمومی
- **The Unlicense** - لایسنس عمومی ساده
- **WTFPL** - لایسنس طنزآمیز بدون محدودیت

### لایسنس‌های محتوا

#### Creative Commons
- **Creative Commons Zero 1.0** - لایسنس عمومی برای محتوا
- **Creative Commons Attribution 4.0** - لایسنس با ذکر منبع
- **Creative Commons Attribution-ShareAlike 4.0** - لایسنس copyleft برای محتوا
- **Creative Commons Attribution-NonCommercial 4.0** - لایسنس با ذکر منبع و ممنوعیت تجاری
- **Creative Commons Attribution-NonCommercial-ShareAlike 4.0** - لایسنس copyleft غیرتجاری برای محتوا

## 🛠️ تکنولوژی‌های استفاده شده

- **MkDocs** - تولید مستندات استاتیک
- **Material Theme** - پوسته مدرن و زیبا
- **RTL Support** - پشتیبانی کامل از راست به چپ
- **Search Functionality** - قابلیت جستجو در محتوا
- **Responsive Design** - طراحی واکنش‌گرا

## 🚀 راه‌اندازی محلی

### پیش‌نیازها

- Python 3.6+
- pip

### نصب و راه‌اندازی

1. کلون کردن مخزن:
```bash
git clone https://github.com/MahdiMajidzadeh/wikilicense.git
cd wikilicense
```

2. نصب MkDocs:
```bash
pip install mkdocs mkdocs-material
```

3. اجرای سرور توسعه:
```bash
mkdocs serve
```

4. باز کردن مرورگر و رفتن به `http://127.0.0.1:8000`

### ساخت سایت

```bash
mkdocs build
```

فایل‌های تولید شده در پوشه `docs/` قرار خواهند گرفت.

## 📁 ساختار پروژه

```
wikilicense/
├── docs/                 # فایل‌های تولید شده سایت
├── pages/               # فایل‌های منبع Markdown
│   ├── licenses/        # فایل‌های لایسنس‌ها
│   └── index.md         # صفحه اصلی
├── mkdocs.yml           # تنظیمات MkDocs
├── LICENSE              # لایسنس پروژه (GPL-3.0)
└── README.md            # این فایل
```

## 🤝 مشارکت

ویکی لایسنس یک پروژه منبع باز است و از مشارکت‌های شما استقبال می‌کند:

### راه‌های مشارکت

1. **افزودن لایسنس جدید**: اگر لایسنس مهمی وجود دارد که در پروژه نیست
2. **بهبود توضیحات**: تکمیل یا بهبود توضیحات موجود
3. **گزارش باگ**: اگر مشکلی مشاهده کردید
4. **پیشنهاد بهبود**: ایده‌های جدید برای بهتر شدن پروژه

### نحوه مشارکت

1. Fork کردن پروژه
2. ایجاد شاخه جدید (`git checkout -b feature/amazing-feature`)
3. Commit تغییرات (`git commit -m 'Add some amazing feature'`)
4. Push به شاخه (`git push origin feature/amazing-feature`)
5. ایجاد Pull Request

## 📝 گزارش مشکلات

اگر مشکلی مشاهده کردید، لطفاً از طریق [Issues](https://github.com/MahdiMajidzadeh/wikilicense/issues) گزارش دهید.

## 📄 لایسنس

این پروژه تحت لایسنس [GNU General Public License v3.0](LICENSE) منتشر شده است.

## 👨‍💻 توسعه‌دهنده

**Mahdi Majidzadeh**
- GitHub: [@MahdiMajidzadeh](https://github.com/MahdiMajidzadeh)
- Website: [wikilicense.ir](https://wikilicense.ir/)

## 🙏 تشکر

از تمام کسانی که در توسعه و بهبود این پروژه مشارکت کرده‌اند، تشکر می‌کنیم.

---

⭐ اگر این پروژه برای شما مفید بود، لطفاً آن را ستاره کنید!
