# 📚 Library Management System

The **Library Management System** is a database-driven application developed as part of our DBMS course. It was collaboratively built by **Muhammad Usman**, **Asma Channa**, and **Soyam Kapoor**, under the supervision of **Ma'am Zainab Umair**.

The system uses **MySQL** for the backend and a **Python Tkinter GUI** with `ttkbootstrap` for a modern interface. It supports two roles:

- **Admin**: Full access to manage books, members, transactions, and generate reports.  
- **User**: Can search/view books and track issued items.

---

## 🔑 Key Features

- **Secure Login & Role-Based Access**
- **Book & Member Management**
- **Issue/Return Transactions**
- **Overdue Book Reporting & CSV Export**
- **Modern GUI with Searchable Tables**

---

## 💻 Tech Stack

- **Frontend**: Python, Tkinter, ttkbootstrap  
- **Backend**: MySQL  
- **Libraries**: `mysql-connector-python`, `bcrypt`, `pandas`  

---

## ⚙️ System Requirements

- **Python**: 3.8 or above  
- **MySQL**: 8.0+  
- **RAM**: Minimum 4 GB  
- **OS**: Windows/Linux/macOS  
- **Tools**: VS Code, MySQL Workbench, Git

---

## 🚀 Getting Started

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/[your-username]/library-management-system.git
   cd library-management-system
   ```

2. **Set Up Database**  
   - Import SQL schema from `docs/`
   - Use default login: `admin / admin123`

3. **Install Dependencies**  
   ```bash
   pip install ttkbootstrap mysql-connector-python bcrypt pandas
   ```

4. **Configure Database**  
   - Edit `database/db_config.py` with your credentials.

5. **Run the App**  
   ```bash
   python login_window.py
   ```

---

## 🤝 Contribution

We welcome contributions! Fork, make changes in a new branch, and submit a pull request.

---

## 📬 Contact

**Soyam Kapoor**  
📧 soyamkapoor.becsef22@iba-suk.edu.pk  
🔗 [LinkedIn](https://www.linkedin.com/in/soyamkapoor/)

**Muhammad Usman**  
📧 muhammadusman.becsef22@iba-suk.edu.pk  
🔗 [LinkedIn](https://www.linkedin.com/in/muhammad-usman-018535253)

**Asma Channa**  
📧 asmachanna.becsef22@iba-suk.edu.pk  
🔗 [LinkedIn](https://www.linkedin.com/in/iasmachanna/)
