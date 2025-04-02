# 🍋 LittleLemon Project - Django  

Welcome to **LittleLemon Project**, the final project I developed during my journey in the **"Django Web Framework"** course by **Meta** on **Coursera**. This project applies key **Django** concepts, showcasing a fully functional web application with authentication, data management, and a REST API.  

## 🚀 Project Description  
**LittleLemon** is a **restaurant management system** where users can explore the menu, make reservations, and manage restaurant operations. Through this project, I implemented:  

- **Django Models** for data management  
- **Views and Templates** for the user interface  
- **Django REST Framework (DRF)** for API development  
- **User authentication and authorization**  
- **CRUD operations** for menu and reservation management  

## 🛠️ Technologies Used  
- **Python 3**  
- **Django & Django REST Framework**  
- **SQLite**  

## 📌 Features  
✅ **User registration and login**  
✅ **Menu management** (create, update, and delete dishes)  
✅ **Reservation system** for customers  
✅ **RESTful APIs** to interact with data  
✅ **Admin panel** for data management  

## 📂 Project Structure  
```
LittleLemon-Project/
│── littlelemon/          # Main project folder
│── restaurant/           # Main app (menu & reservations)
  │── static/               # Static files (CSS, JS, images)
│── menu_images/          # Main images of the app
│── templates/            # HTML templates for the frontend  
│── db.sqlite3            # SQLite database
│── manage.py             # Django management script
```

## 🚀 Installation & Setup  
1️⃣ **Clone the repository**  
```bash
git clone https://github.com/stobio19/LittleLemon-Project---Django.git
cd LittleLemon-Project
```
2️⃣ **Create and activate a virtual environment**  
```bash
python -m venv venv  
source venv/bin/activate   # On macOS/Linux  
venv\Scripts\activate      # On Windows  

3️⃣ **Run database migrations**  
```bash
python manage.py migrate  
```
4️⃣ **Create a superuser for the admin panel**  
```bash
python manage.py createsuperuser  
```
5️⃣ **Start the development server**  
```bash
python manage.py runserver  
```
Now, open your browser and go to `http://127.0.0.1:8000/` 🎉  

## 📜 License  
This project is licensed under Apache 2.0 License – feel free to modify and use it as needed.  

## 🤝 Contributing  
If you'd like to improve this project, feel free to fork it and submit a pull request!  

## ✨ Author  
Developed by **[Samuel Tobio]** – Connect with me on [GitHub](https://github.com/stobio19) 🚀  
