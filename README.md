# 📚 Attendance System

A smart **AI-powered attendance management website** designed for online classes.  
This system ensures that students are present and attentive throughout the class by using **face detection** and **randomized attendance checks**.  

---

## ✨ Features
- ✅ **Face Detection with AI** – Students must capture their face during attendance prompts.  
- 🎥 **Random Attendance Pop-ups** – Three randomized checks per class ensure continuous participation.  
- 🔑 **Secure Student Accounts** – Students register via admin and set up their own password & reference photo.  
- 🖼️ **Reference Photo Verification** – Attendance photos are matched with the reference photo for authenticity.  
- 🔒 **Privacy Friendly** – Students are not required to keep their camera on for the entire class.  
- ⏰ **Automated Scheduling** – Uses **PgAgent** to handle class start and end times.  

---

## 🛠️ Tech Stack

### 🔹 Languages & Frameworks
- **Golang** – Backend  
- **JavaScript** – Frontend logic & random pop-ups  
- **HTML / CSS** – Frontend UI  

### 🔹 Database & Tools
- **PostgreSQL (pgsql)** – Database  
- **PgAgent** – Schedule maintainer for classes  

---

## 📂 How It Works
1. **Admin registers student accounts.**  
2. On first login, students set a password and capture a **reference photo**.  
3. During class, the system generates **3 random attendance pop-ups**.  
4. Students must capture valid attendance photos for **all 3 checks** to be marked present.  
5. The teacher can compare attendance photos with the reference photo for verification.  

---

## 🎥 Demo
Watch the full project demo here:  
▶️ [Attendance System Demo](https://youtube.com/playlist?list=PLCk1Y31wvMhUsFFMXJ8afSK5ZLtYU2Yb6)  

---

## 🚀 Getting Started

### Prerequisites
- **Golang** installed  
- **PostgreSQL** with **PgAgent**  
- Web browser (for frontend)  

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/aadityaprabu/attendance-system.git
   cd attendance-system
   ```

2. Set up the PostgreSQL database and configure **PgAgent** for scheduling.  

3. Run the Golang backend server.  

4. Open the frontend in a browser and log in as a student or admin.  

---

## 📜 License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

---

## 👨‍💻 Author
**Aaditya Prabu**  
- GitHub: [@aadityaprabu](https://github.com/aadityaprabu)
