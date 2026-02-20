## Moiteek Digital Tech Academy - LMS 🎓

A robust, secure, and responsive Learning Management System designed for digital skill acquisition. This project features a custom-built PHP backend and a modern Tailwind CSS frontend.

## 🚀 Features

### **For Students**
* **Course Catalog:** Dynamic filtering by category (Web Dev, Digital Skills, etc.).
* **Enrollment System:** Secure registration tied to specific course IDs.
* **Learning Portal:** Dedicated interface for video lessons and curriculum tracking.
* **Progress Tracking:** Interactive "Mark as Complete" functionality.

### **For Administrators**
* **Unified Dashboard:** Real-time stats on student enrollment and revenue.
* **Student Management:** Approve/Deactivate accounts with one click.
* **Automatic Credentials:** System generates secure random passwords upon student approval.
* **Content Management:** Fully dynamic course and lesson management.

## 🛠️ Technical Highlights
* **Architecture:** Model-View-Controller (MVC) inspired patterns with a singleton-style `Database` class.
* **Security:** * Password hashing using `bcrypt`.
  * Protection against SQL Injection via PDO Prepared Statements.
  * CSRF protection and input sanitization.
* **UI/UX:** Fully responsive design built with **Tailwind CSS**.
* **Database:** Relational MySQL schema with foreign key constraints for data integrity.

## 📦 Installation (Localhost)
1. Clone the repository into your `htdocs` folder.
2. Import the `sql/master_setup.sql` file into your MySQL database (via phpMyAdmin).
3. Configure your database credentials in `config/db.php`.
4. Open `http://localhost/moiteek_academy` in your browser.

## 📄 License
MIT License - feel free to use this for your own educational projects!
