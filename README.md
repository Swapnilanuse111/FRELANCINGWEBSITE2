# 🌐 Advanced Java Web Application

### *Servlet | JSP | JDBC | MySQL*

A fully functional web application built using **Advanced Java technologies** such as Servlets, JSP, and JDBC.
This project demonstrates how to build a dynamic website capable of storing and managing data using **MySQL**.

---

## 📖 Overview

This project is designed as a **beginner-friendly full-stack Java web application**.
It follows the **MVC architecture** and includes modules for user input, backend processing, and database interaction.

It is ideal for:

* Students learning Advanced Java
* Java developers practicing Servlets/JSP
* Mini-project submission
* Portfolio or GitHub showcase

---

## 🚀 Key Features

* Clean and responsive JSP pages
* Servlets for handling business logic
* JDBC for secure database connectivity
* CRUD operations (Create, Read, Update, Delete)
* MVC project structure
* MySQL backend integration
* Form validation and proper error responses

---

## 🛠️ Technologies Used

* **Java (JDK 8 or above)**
* **Servlets & JSP**
* **JDBC**
* **MySQL 8.x**
* **Apache Tomcat Server**
* **Eclipse IDE**
* **HTML, CSS (optional Bootstrap)**

---

## 🧱 Project Architecture (MVC)

```
Model   → Java classes + JDBC code  
View    → JSP pages (frontend)  
Controller → Servlets (request handling)
```

---

## 📂 Folder Structure

```
ProjectName/
│── src/
│   ├── controller/        # Servlets
│   ├── dao/               # JDBC Database access
│   ├── model/             # Java model classes
│── WebContent/
│   ├── JSP Pages
│   ├── CSS / Images
│   ├── WEB-INF/
│       ├── web.xml
│── lib/                   # MySQL Connector JAR
```

---

## 🗄️ Database Configuration

**Database:** `YOUTUBE`
**Table:** `USER`
**Driver Used:** `mysql-connector-j`

Example connection URL:

```
jdbc:mysql://localhost:3306/your_database_name
```

---

## 📦 How to Run the Project

1. Clone the repository
2. Open **Eclipse → File → Import → Existing Projects into Workspace**
3. Add **Tomcat Server**
4. Add **mysql-connector.jar** inside `WEB-INF/lib` (if not added)
5. Update DB credentials in your DAO/JDBC file
6. Right-click project → **Run As → Run on Server**

---

## 📡 API / Servlet Endpoints

| Endpoint    | Method   | Description         |
| ----------- | -------- | ------------------- |
| `/register` | POST     | Insert data into DB |
| `/display`  | GET      | Show stored data    |
| `/update`   | POST     | Update record       |
| `/delete`   | GET/POST | Delete record       |

---

## 🖼️ Screenshots (Optional)


<img width="1919" height="1079" alt="Screenshot 2025-11-26 165554" src="https://github.com/user-attachments/assets/713f33e2-06b1-4a9a-a921-d394ab8a703e" />
<img width="1918" height="1079" alt="Screenshot 2025-11-26 165256" src="https://github.com/user-attachments/assets/6610b08c-e6b6-4b74-af55-d27ce9e259f1" />
<img width="1919" height="1079" alt="Screenshot 2025-11-26 165444" src="https://github.com/user-attachments/assets/b2d8d952-2cee-4e58-9eef-33ad5a72bef0" />
<img width="943" height="348" alt="Screenshot 2025-11-26 165520" src="https://github.com/user-attachments/assets/3e527fc7-15b8-4af6-8690-9709d3ab3183" />





## 🙋 Author

**Swapnil Anuse**
Java Developer | Learning Advanced Java, Web Development & Databases

---

## ⭐ Support

If you found this helpful, please ⭐ the repository to support my work!

---

## 📜 License

This project is released under the **MIT License**.
