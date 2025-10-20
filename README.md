# 🇦🇫 Smart School Management System (Afghanistan Edition)
### Modern, Offline-Capable, and Built for Real Schools

A practical, professional, and multilingual school management system designed for Afghanistan — where many students don’t own smartphones, internet is limited, and most schools still rely on paper.  
This system bridges traditional management with modern tools using **offline support**, **local hosting**, and **SMS-based communication**.

---

## 🧑‍💼 User Accounts & Access

### Account Creation
- Admins, Teachers, Accountants, Parents, and Students can register using **phone number**, **email**, or **school code**.
- Accounts can be created manually by admin or imported from Excel.

### Role-Based Permissions
- Each user role has unique access:
  - **Admin**: full control (manage all modules)
  - **Teacher**: attendance, grades, announcements
  - **Accountant**: fee, payment, finance
  - **Parent**: view-only dashboard
  - **Student**: personal performance access

### Authentication & Security
- Login via phone or email.
- OTP verification through **SMS or email**.
- Secure JWT authentication for all APIs.

### Password Reset
- Reset or recover password using SMS code or email link.

### Multi-School / Branch Management
- One central admin can manage multiple branches.
- Branches have their own teachers, classes, and students, but share main control.

---

## 📊 Dashboards & Navigation

### Admin Dashboard
- Displays real-time stats: total students, active teachers, fee collections, attendance rate.
- Quick access to reports and alerts.

### Teacher Dashboard
- Daily class schedule and attendance summary.
- Pending grading tasks and announcements.

### Parent Dashboard
- View child’s attendance, marks, and fee status.
- Receive school announcements directly.

### Student Dashboard
- Students can view grades, attendance, and upcoming exams or homework.

---

## 🧑‍🎓 Student & Class Management

### Student Registry
- Add and edit student profiles (photo, date of birth, guardian info, contact, etc.).
- Assign each student to class, section, and subjects.

### Class & Section Control
- Create and organize classes (Grade 1–12) and sections (A, B, C...).
- Assign class teachers and subjects easily.

### Subject–Teacher Assignment
- Connect teachers with their subjects and sections.
- Supports multiple teachers per subject if needed.

### Bulk Import
- Upload student data using **Excel or CSV**.
- Perfect for schools moving from paper to digital.

### ID Card & Photos
- Capture photo directly or upload scanned image.
- Print ID cards with QR codes and school branding.

---

## 🕓 Attendance Management

### Mark Attendance
- Teachers can mark daily attendance by list, roll number, or QR code scan.
- Works in both online and offline modes.

### Attendance Correction
- Mistakes can be edited by admin or teacher.
- Every change is recorded in an **audit log**.

### Reports & History
- Generate attendance summaries for class or student.
- Export data to PDF or Excel for record keeping.

### Offline Mode
- Attendance is stored locally when no internet is available.
- Data syncs automatically once connection restores.

### Absence Notifications
- Sends SMS alerts to parents when students are absent for more than a set number of days.

---

## 🧾 Grades & Performance

### Digital Gradebook
- Teachers can enter grades for exams, assignments, and tests.
- Supports weighted marks and averages.

### Automatic Calculations
- Define weightage for exams, homework, and tests.
- System calculates total and final marks automatically.

### Analytics & Reports
- View charts for class averages, performance trends, and weak subjects.
- Identify top-performing students.

### At-Risk Alerts
- Flags students with attendance under 75% or grades below 40%.
- Helps early intervention.

### Printable Report Cards
- Auto-generate PDF report cards with student info, grades, and teacher comments.

---

## 💰 Fee & Finance Management

### Fee Structure
- Define tuition, lab, transport, or other fee categories.
- Set schedules, due dates, and discounts.

### Invoice Generation
- Create fee invoices automatically for each student.
- Include due dates and payment details.

### Payment Tracking
- Record full or partial payments.
- Track outstanding balances and defaulters.

### Receipt Printing
- Generate professional receipts (PDF/PNG).
- Each payment logged with date, method, and amount.

### Fee Defaulter Reports
- View list of unpaid students.
- Send reminders through SMS or print collection reports.

---

## 📢 Communication & Announcements

### Announcements
- Admin or teachers can broadcast messages to all users or specific classes.
- Used for holidays, exam reminders, or events.

### SMS & Email Alerts
- For important announcements when internet is poor.
- Compatible with Afghan mobile networks (Roshan, Etisalat, AWCC, MTN).

### Parent–Teacher Messaging
- Direct or limited two-way messaging for updates and student progress.

---

## 📁 Document & Record Management

### Document Upload
- Upload student files like Tazkira, certificates, or photos.
- Stored securely in the database or local folder.

### Searchable Records
- Find any document by student name, class, or upload date.

### Export & Printing
- Export student lists, attendance reports, or grade sheets to Excel or PDF.

---

## 📈 Reports & Insights

### School Summary Reports
- Monthly or term-wise reports with attendance rate, grades, and fee summaries.

### Teacher Performance
- Compare teacher classes based on average grades and attendance.

### Parent Engagement
- See how many parents have logged in, read messages, or paid fees.

---

## 🌍 Localization & Accessibility

### Multi-Language Interface
- Full support for **Dari**, **Pashto**, and **English**.
- User can switch language anytime.

### Responsive Design
- Optimized for desktops (admins), tablets, and Android phones (teachers & parents).

### Low-Bandwidth Optimization
- Fast-loading interface, minimal graphics, and local caching for slow networks.

---

## 🔒 Security & Hosting

### Data Encryption
- All data encrypted both in storage and during transmission (HTTPS).

### Local Hosting Option
- Schools without reliable internet can install system locally (on LAN).
- Data syncs to cloud when available.

### Role-Based Logs
- Every edit or deletion tracked with user, time, and reason.

### Backup & Restore
- One-click backup of all data to ZIP or JSON.
- Auto daily backup option for safety.

---

## 🧠 Future Enhancements (Phase 2+)

### Parent Mobile App / PWA
- Mobile app for parents with push notifications and live updates.

### AI Performance Analytics
- Smart insights predicting drop-out risk or academic decline.

### Integration with Ministry Systems
- Export reports compatible with Afghanistan’s EMIS or regional education systems.

### Homework & Assignment Module
- Teachers assign homework online; students submit when internet available.

### Library & Asset Management
- Manage books, lab tools, and equipment borrowing.

### Student Transport Module
- Manage school bus routes, pickup/drop logs, and SMS alerts for parents.

### Alumni Management
- Keep track of graduates, achievements, and future donations.

---

## 🧰 Deployment Options

### Local Server Mode (Offline Schools)
- Fully runs on school computer or LAN network.
- Syncs manually with cloud when connection is available.

### Cloud Mode (Online Schools)
- Hosted on VPS for 24/7 access.
- Ideal for city-based schools with reliable internet.

### Hybrid Mode
- Combines both: school uses local version daily and syncs to cloud weekly.

---

## ❤️ Built for Afghanistan
- Works even without smartphones.
- Functions perfectly in poor internet zones.
- Uses SMS for communication, not just mobile apps.
- Easy to use for teachers and admins with basic computer skills.

---

© 2025 CodeArya — Empowering Afghan Education with Technology 🇦🇫

---

# 🇦🇫 سیستم مدیریت مکتب (نسخه افغانستان)
### مدرن، آفلاین، و مناسب مکاتب واقعی

یک سیستم مدیریت مکتب عملی، حرفه‌ای و چندزبانه طراحی شده برای افغانستان — جایی که بیشتر شاگردان موبایل ندارند، اینترنت محدود است و بیشتر مکاتب هنوز به کاغذ وابسته‌اند.  
این سیستم مدیریت سنتی را با ابزارهای مدرن ترکیب می‌کند با پشتیبانی از **حالت آفلاین**، **میزبانی محلی** و **اطلاعیه‌های SMS**.

---

## 🧑‍💼 حساب‌ها و دسترسی کاربران

### ایجاد حساب
- مدیر، استاد، حسابدار، والدین و شاگردان می‌توانند با **شماره تلفن**، **ایمیل** یا **کود مکتب** ثبت‌نام کنند.
- حساب‌ها می‌توانند توسط مدیر ایجاد یا از فایل Excel وارد شوند.

### دسترسی بر اساس نقش
- هر نقش دسترسی منحصر به فرد دارد:
  - **مدیر:** دسترسی کامل به تمام ماژول‌ها
  - **استاد:** حضور، نمرات، اعلان‌ها
  - **حسابدار:** فیس، پرداخت و امور مالی
  - **والدین:** داشبورد فقط برای مشاهده
  - **شاگرد:** دسترسی به نمرات و عملکرد شخصی

### احراز هویت و امنیت
- ورود با شماره تلفن یا ایمیل.
- تایید از طریق **کد SMS یا ایمیل**.
- احراز هویت امن با JWT برای تمام API‌ها.

### بازیابی رمز عبور
- بازنشانی یا بازیابی رمز عبور با کد SMS یا لینک ایمیل.

### مدیریت چند مکتب / شعبه
- یک مدیر مرکزی می‌تواند چند شعبه را مدیریت کند.
- هر شعبه معلمان، کلاس‌ها و شاگردان خود را دارد اما کنترل اصلی مشترک است.

---

## 📊 داشبوردها و ناوبری

### داشبورد مدیر
- نمایش آمار به‌صورت لحظه‌ای: تعداد شاگردان، معلمان فعال، جمع‌آوری فیس، درصد حضور.
- دسترسی سریع به گزارش‌ها و اعلان‌ها.

### داشبورد معلم
- برنامه روزانه کلاس‌ها و خلاصه حضور و غیاب.
- وظایف نمره‌دهی مانده و اعلان‌ها.

### داشبورد والدین
- مشاهده حضور، نمرات و وضعیت فیس فرزند.
- دریافت مستقیم اعلان‌های مکتب.

### داشبورد شاگرد
- شاگردان می‌توانند نمرات، حضور و امتحانات یا وظایف آینده را مشاهده کنند.

---

## 🧑‍🎓 مدیریت شاگرد و صنف

### ثبت شاگرد
- اضافه و ویرایش پروفایل شاگردان (عکس، تاریخ تولد، معلومات والدین، تماس و غیره).
- تخصیص هر شاگرد به کلاس، بخش و مضامین.

### مدیریت کلاس و بخش
- ایجاد و سازماندهی کلاس‌ها (صنف ۱–۱۲) و بخش‌ها (A, B, C...).
- تعیین معلم کلاس و مضامین به‌سادگی.

### تخصیص معلم–مضمون
- اتصال معلم‌ها به مضامین و بخش‌های خود.
- پشتیبانی از چند معلم برای یک مضمون در صورت نیاز.

### وارد کردن گروهی
- وارد کردن معلومات شاگردان با **Excel یا CSV**.
- مناسب برای مکاتبی که از کاغذ به دیجیتال منتقل می‌شوند.

### کارت شناسایی و عکس‌ها
- گرفتن عکس مستقیم یا آپلود تصویر اسکن شده.
- چاپ کارت با QR Code و برند مکتب.

---

## 🕓 مدیریت حضور و غیاب

### نشانه‌گذاری حضور
- معلمان می‌توانند حضور روزانه را با لیست، شماره رول یا QR Code علامت‌گذاری کنند.
- کارکرد در حالت آنلاین و آفلاین.

### اصلاح حضور
- اشتباهات توسط مدیر یا معلم قابل ویرایش است.
- هر تغییر در **لاگ حسابرسی** ثبت می‌شود.

### گزارش‌ها و تاریخچه
- تولید خلاصه حضور برای کلاس یا شاگرد.
- خروجی PDF یا Excel برای ثبت و نگهداری.

### حالت آفلاین
- حضور زمانی که اینترنت نیست محلی ذخیره می‌شود.
- داده‌ها پس از اتصال به‌طور خودکار هم‌زمان می‌شوند.

### اطلاعیه غیبت
- ارسال SMS به والدین در صورت غیبت شاگرد بیش از تعداد مشخص روز.

---

## 🧾 نمرات و عملکرد

### دفتر نمرات دیجیتال
- وارد کردن نمرات امتحان، وظایف و تست‌ها توسط معلم.
- پشتیبانی از نمرات وزنی و میانگین.

### محاسبات خودکار
- تعریف وزن امتحان، وظیفه و تست.
- سیستم نمره کل و نهایی را به‌طور خودکار محاسبه می‌کند.

### تحلیل و گزارش‌ها
- مشاهده نمودارهای میانگین کلاس، روند عملکرد و مضامین ضعیف.
- شناسایی شاگردان برتر.

### هشدار شاگردان در خطر
- شاگردانی با حضور کمتر از ۷۵٪ یا نمره کمتر از ۴۰٪ علامت‌گذاری می‌شوند.
- کمک به مداخله زودهنگام.

### چاپ کارنامه
- تولید خودکار PDF کارنامه با اطلاعات شاگرد، نمرات و توضیحات معلم.

---

## 💰 مدیریت فیس و امور مالی

### ساختار فیس
- تعریف فیس درسی، لابراتوار، ترانسپورت و غیره.
- تعیین زمان پرداخت، تاریخ‌ها و تخفیف‌ها.

### صدور بل فیس
- ایجاد خودکار بل فیس برای هر شاگرد.
- شامل تاریخ پرداخت و جزئیات.

### پیگیری پرداخت‌ها
- ثبت پرداخت کامل یا جزئی.
- پیگیری بدهی‌ها و شاگردان پرداخت نکرده.

### چاپ رسید
- تولید رسید حرفه‌ای (PDF/PNG).
- هر پرداخت با تاریخ، روش و مبلغ ثبت می‌شود.

### گزارش بدهکاران
- مشاهده لیست شاگردان پرداخت نکرده.
- ارسال یادآوری با SMS یا چاپ گزارش.

---

## 📢 اعلان‌ها و ارتباطات

### اعلان‌ها
- مدیر یا معلم می‌تواند پیام به همه کاربران یا کلاس‌های خاص ارسال کند.
- برای تعطیلی، یادآوری امتحان یا رویدادها.

### SMS و ایمیل هشدار
- برای اعلان‌های مهم در صورت اینترنت ضعیف.
- سازگار با شبکه‌های موبایل افغانستان (روشن، اتصالات، AWCC، MTN).

### پیام والدین و معلم
- پیام مستقیم یا محدود دوطرفه برای بروزرسانی و پیشرفت شاگرد.

---

## 📁 مدیریت مدارک و سوابق

### آپلود مدارک
- آپلود فایل‌های شاگرد مانند تذکره، گواهی یا عکس.
- ذخیره امن در پایگاه داده یا پوشه محلی.

### جستجوی مدارک
- پیدا کردن هر مدرک بر اساس نام شاگرد، کلاس یا تاریخ آپلود.

### خروجی و چاپ
- خروجی گرفتن از لیست شاگردان، گزارش حضور یا دفتر نمرات به Excel یا PDF.

---

## 📈 گزارش‌ها و تحلیل‌ها

### گزارش عمومی مکتب
- گزارش ماهانه یا فصلی با درصد حضور، نمرات و جمع فیس.

### عملکرد معلم
- مقایسه کلاس‌های معلمان بر اساس میانگین نمرات و حضور.

### تعامل والدین
- مشاهده تعداد والدینی که وارد سیستم شده‌اند، پیام‌ها را خوانده یا فیس پرداخت کرده‌اند.

---

## 🌍 زبان و دسترسی

### رابط چندزبانه
- پشتیبانی کامل از **دری، پشتو و انگلیسی**.
- کاربر می‌تواند هر زمان زبان را تغییر دهد.

### طراحی واکنش‌گرا
- بهینه برای دسکتاپ (مدیر)، تبلت و گوشی اندروید (معلم و والدین).

### بهینه‌سازی اینترنت ضعیف
- رابط سریع، گرافیک کم و حافظه کش محلی برای شبکه‌های کند.

---

## 🔒 امنیت و میزبانی

### رمزگذاری داده‌ها
- تمام داده‌ها در ذخیره و انتقال رمزگذاری شده (HTTPS).

### گزینه میزبانی محلی
- مکاتب بدون اینترنت قابل اعتماد می‌توانند سیستم را محلی نصب کنند (LAN).
- داده‌ها با کلود هم‌زمان می‌شوند وقتی اینترنت موجود است.

### لاگ‌های دسترسی نقش‌ها
- هر ویرایش یا حذف با نام کاربر، زمان و دلیل ثبت می‌شود.

### پشتیبان‌گیری و بازیابی
- یک کلیک برای پشتیبان‌گیری همه داده‌ها به ZIP یا JSON.
- گزینه پشتیبان‌گیری روزانه خودکار برای امنیت.

---

## 🧠 امکانات آینده (مرحله دوم+)

### اپلیکیشن والدین / PWA
- اپلیکیشن موبایل برای والدین با نوتیفیکیشن و بروزرسانی زنده.

### تحلیل عملکرد با AI
- تحلیل هوشمند برای پیش‌بینی افت تحصیلی یا خطر ترک مکتب.

### ادغام با سیستم‌های وزارت
- خروجی گزارش‌ها سازگار با EMIS افغانستان یا سیستم‌های محلی.

### ماژول وظیفه و تکلیف
- معلم وظایف را آنلاین ارسال و شاگردان در دسترس بودن اینترنت ارسال می‌کنند.

### مدیریت کتابخانه و وسایل
- مدیریت کتاب‌ها، ابزارهای لابراتوار و قرض دادن/برگشت تجهیزات.

### ماژول ترانسپورت شاگردان
- مدیریت مسیر بس، ثبت رسید و خروج، و اطلاع‌رسانی SMS برای والدین.

### مدیریت فارغ‌التحصیلان
- پیگیری فارغین، دستاوردها و کمک‌های آینده.

---

## 🧰 گزینه‌های استقرار

### حالت سرور محلی (مکاتب آفلاین)
- اجرا کامل روی کامپیوتر مکتب یا شبکه LAN.
- هم‌زمان‌سازی دستی با کلود در صورت اتصال.

### حالت کلود (مکاتب آنلاین)
- میزبانی روی VPS برای دسترسی ۲۴/۷.
- مناسب مکاتب شهری با اینترنت مطمئن.

### حالت ترکیبی
- ترکیبی: استفاده روزانه از نسخه محلی و هم‌زمان‌سازی هفتگی با کلود.

---

## ❤️ ساخته شده برای افغانستان
- کارکرد حتی بدون موبایل.
- عملکرد عالی در مناطق با اینترنت ضعیف.
- استفاده از SMS برای ارتباط، نه فقط اپلیکیشن موبایل.
- آسان برای استفاده معلم و مدیر با مهارت‌های پایه کامپیوتر.

---

© 2025 CodeArya — توانمندسازی آموزش افغانستان با فناوری 🇦🇫
