# 🧩 Online Quiz Web Application (JSP | Servlet | JDBC | MySQL)

An interactive **Online Quiz Application** built using **Java (JSP + Servlet)**, **JDBC**, and **MySQL**.  
It allows users to take quizzes based on various categories and difficulty levels, while administrators can manage questions, categories, and users from a secure admin panel.

---

## 🚀 Features

### 👨‍🎓 User Side
- Register and login with authentication
- Choose quiz **categories** and **difficulty levels**
- Dynamic question loading from the database
- Auto-calculated quiz result and score display
- View quiz history and performance

### 🛠️ Admin Side
- Secure Admin Login
- Add / Update / Delete quiz questions
- Manage quiz categories dynamically (fetched from DB)
- View and manage registered users
- Monitor quiz results and user attempts

---

## 🧱 Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Frontend** | HTML, CSS, JSP |
| **Backend** | Java Servlet, JSP |
| **Database** | MySQL (via JDBC) |
| **Server** | Apache Tomcat |
| **IDE** | Eclipse IDE for Enterprise Java Developers |

---

## 🗂️ Project Structure
⚙️ Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/rajp6508/QuizeApp-java-WebApp.git

2️⃣ Import the Project

Open Eclipse IDE

Go to File → Import → Existing Projects into Workspace

Browse and select the project folder

3️⃣ Configure the Database

Create a new database in MySQL (e.g., quizapp)

Import the provided SQL file:

SOURCE path_to_project/database/quizapp.sql;


Update your JDBC connection credentials in the Java code (inside src/main/java/...)

4️⃣ Run the Project

Right-click on the project → Run on Server

Select Apache Tomcat

Open the browser and visit:
👉 http://localhost:8080/QuizApp/

	
🧑‍💻 Author

👋 Raj Puri
📧 Email: rajp66228@gmail.com

⭐ Contribute / Support

If you found this project useful, please give it a ⭐ on GitHub to support my work!

🏁 License

This project is open source and available under the MIT License.
