# BorsTerminal

**ایستگاه معاملاتی و پژوهشی دسکتاپ برای بازار سرمایه ایران**

BorsTerminal با هدف یکپارچه‌کردن پایش بازار، تحلیل تکنیکال و بنیادی، غربالگری مبتنی بر FTS و پژوهش استراتژی‌های معاملاتی در یک نرم‌افزار دسکتاپ در حال توسعه است.

این مخزن فقط ویترین عمومی پروژه است. **کد منبع، فایل نصب، نسخه اجرایی، مدل‌های آموزش‌دیده و داده‌های اختصاصی در اینجا منتشر نمی‌شوند.**

## حوزه‌های محصول

- **Market & Board:** مشاهده بازار، تابلوی نمادها، جریان معاملات و وضعیت صنایع
- **Technical Analysis:** نمودارها، ساختار قیمت، اندیکاتورها و تحلیل چندتایم‌فریمی
- **FTS Screening:** غربالگری بر پایه قواعد روش FTS و نمایش دلایل تصمیم
- **Fundamental Analysis:** بررسی بنیادی شرکت‌ها
- **Opportunity Lab:** ساخت فرضیه، آزمایش و اعتبارسنجی استراتژی‌ها
- **Strategy Library:** نگهداری نسخه‌های بررسی‌شده و تأییدشده استراتژی‌ها
- **Portfolio:** ابزارهای مدیریت و پایش پرتفوی
- **Local ML Engine:** مدل‌های تخصصی برای ارزیابی الگوها، رژیم بازار، ریسک و مسیرهای احتمالی قیمت

## جهت فناوری

نسل فعلی پروژه با این جهت معماری توسعه می‌یابد:

- **Desktop:** Tauri 2
- **Frontend:** React + TypeScript
- **Product Runtime:** Go
- **Data:** پایگاه‌های داده محلی با قراردادهای مشخص
- **Research & Training:** محیط تحقیق و آموزش جدا از Runtime کاربران

هدف، محصولی local-first با وابستگی حداقلی به سرویس‌های ابری پولی است.

## اصول محصول

1. قواعد قطعی و canonical روش FTS مستقل و قابل‌ردیابی باقی می‌مانند؛ ML جایگزین آن‌ها نیست.
2. خروجی مدل‌ها باید همراه شواهد، عدم‌قطعیت و محدودیت‌ها ارائه شود.
3. مدل‌ها و استراتژی‌ها پیش از انتشار نسخه‌بندی و اعتبارسنجی می‌شوند.
4. استراتژی‌های معتبر مشترک در کنار امکان شخصی‌سازی کاربران قرار می‌گیرند.
5. داده‌ها و ترجیحات اختصاصی کاربران تا جای ممکن روی دستگاه خودشان نگهداری می‌شود.

## مسیر توسعه

پروژه در حال گذار به نسل Go و Tauri است. مسیر کلی شامل تثبیت داده و موتورهای تحلیلی قطعی، تکمیل تکنیکال و FTS، توسعه Opportunity Lab و سپس گسترش مدل‌های تخصصی ML است.

جزئیات عمومی مسیر در [ROADMAP.md](ROADMAP.md) آمده است. این نقشه راه، جهت کلی را نشان می‌دهد و تعهدی برای تاریخ انتشار قابلیت‌ها نیست.

## درباره این مخزن

این مخزن برای معرفی محصول، انتشار توضیحات عمومی و نمایش پیشرفت توسعه است؛ **مخزن سورس‌کد یا دانلود نرم‌افزار نیست**. هیچ فایل اجرایی، نصاب، دیتابیس، مدل یا محتوای داخلی پروژه در این مخزن ارائه نمی‌شود.

## مالکیت فکری

BorsTerminal یک محصول اختصاصی است. مشاهده این مخزن به‌تنهایی مجوز کپی، تغییر، توزیع یا بهره‌برداری تجاری از نرم‌افزار یا محتوای اختصاصی آن ایجاد نمی‌کند. توضیحات در [LICENSE](LICENSE) آمده است.

---

## English

**BorsTerminal is a desktop trading and market-research workstation focused on Iran's capital market.**

The project aims to bring market monitoring, technical and fundamental analysis, deterministic FTS screening, strategy research, portfolio tools, and evidence-based machine learning into one local-first application.

### Product areas

- Market monitoring and order-flow views
- Technical charts and multi-timeframe analysis
- Canonical FTS screening and decision traceability
- Fundamental company analysis
- Opportunity Lab for hypothesis-driven strategy research
- A versioned library of reviewed strategies
- Portfolio monitoring
- Specialized local ML models for pattern quality, market regimes, volatility, risk, and probabilistic price paths

### Technology direction

The current development direction is a **Tauri 2 desktop application**, a **React + TypeScript** interface, and a **Go** product runtime. Research and model training are kept separate from the end-user runtime.

### Development status

BorsTerminal is under active development, transitioning toward the Go/Tauri architecture. Engineering priorities include reliable local data, deterministic technical and FTS engines, strategy research, and a staged technical-first ML roadmap. See [ROADMAP.md](ROADMAP.md).

### Intellectual property

This is a public showcase repository, not a source-code or software-download repository. All rights are reserved as described in [LICENSE](LICENSE). No right to copy, modify, redistribute, or commercially exploit BorsTerminal is granted by viewing this repository.
