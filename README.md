# 🏥 Hospital Management System (Front-End)

A simple and interactive **Hospital Management System Front-End** built using **HTML, CSS, PHP, and MySQL**.  
This project provides a web interface for managing hospital-related data such as **doctors, nurses, patients, treatments, and insurance**.

---

## 🚀 Features

- 🏠 **Homepage:** Clean landing page with navigation across modules.  
- 👨‍⚕️ **Doctor Management:** View and add doctor details.  
- 👩‍⚕️ **Nurse Management:** Manage nurse details (day/night shift and ward info).  
- 🧠 **Departments:** Separate pages for Cardiology, Neurology, Orthopedics, etc.  
- 🧾 **Treatment Details:** Display treatment information for patients.  
- 💳 **Insurance Module:** Manage and insert insurance policy details.  
- 🔐 **Login & Registration:** Basic user authentication pages.  
- 🗄️ **Database Integration:** MySQL database (`HMS.sql`) to store all data.

---

## 🧩 Project Structure

```
Front-end-of-Hospital-Management-System/
│
├── Homepage.html                # Main entry point
├── Login.html                   # User login page
├── Registration.html             # Registration form
│
├── doctordata.html              # Doctor details page
├── insert_doctor.PHP            # PHP script to add doctor data
│
├── NurseData.html               # Nurse details
├── NurseDataNight.html
├── NurseWard.html
│
├── Insurance Policy.html        # Insurance info
├── insert_Insurance Policy.PHP  # PHP script for insurance
│
├── Treatment Details.html       # Patient treatment data
│
├── HMS.sql                      # MySQL database script
│
├── about.css, NurseData.css, Treatment Details.css, Insurance Policy.css  # Styling files
│
└── assets/                      # Images and other media
```

---

## ⚙️ How to Run the Project

### 1️⃣ Prerequisites
- Install [XAMPP](https://www.apachefriends.org/) or [WAMP](https://www.wampserver.com/).  
- Make sure **Apache** and **MySQL** are running.

### 2️⃣ Setup Steps
1. Download or clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Front-end-of-Hospital-Management-System.git
   ```

2. Move the project folder to:
   ```
   C:\xampp\htdocs\
   ```

3. Import the SQL file:
   - Open **phpMyAdmin** → Create a new database (e.g. `hospital_db`).
   - Import the file `HMS.sql`.

4. Open your browser and run:
   ```
   http://localhost/Front-end-of-Hospital-Management-System/Homepage.html
   ```

---

## 🧠 Technologies Used

| Component | Technology |
|------------|-------------|
| Front-End  | HTML5, CSS3 |
| Backend (Basic) | PHP |
| Database | MySQL |
| Styling | Custom CSS |
| Server | XAMPP / WAMP |

---

## 📸 Screenshots

| Module | Preview |
|---------|----------|
| Homepage | 🏠 Shows navigation and intro |
| Doctor Page | 👨‍⚕️ Displays doctor list and specialization |
| Nurse Page | 👩‍⚕️ Shows nurse data for day/night shifts |
| Insurance | 💳 Add and view insurance policy info |
| Login | 🔐 Simple authentication form |

*(Add screenshots later by uploading images and linking them here.)*

---

## 📚 Database Information

- The database file: **`HMS.sql`**
- Contains tables for:
  - Doctors
  - Nurses
  - Treatments
  - Insurance
  - Patients
  - User Login/Registration

---

## 🧑‍💻 Contributors

- **Aniketh Reddy** – Developer & Designer  

If you’d like to contribute, feel free to fork this repository and submit a pull request! 💡

---

## 📝 License

This project is open-source and available under the **MIT License**.

---

## 💬 Feedback

If you have any suggestions or improvements,  
please open an issue or reach out via email or GitHub discussions.

**⭐ Don’t forget to star this repo if you found it helpful!**
