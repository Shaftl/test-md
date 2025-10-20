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
