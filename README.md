# Tourism
# Explorer Tours — Tourism Platform

> Central overview repository for the project.  
> Contains links to **Frontend (Angular + Material)** and **Backend (ASP.NET Modular Monolith)**.

[➡️ Frontend repository](https://github.com/MilanUD/psw-fe-tourism)  
[➡️ Backend repository](https://github.com/MilanUD/psw-be-tourism)

---

## 🎯 About the Project
Explorer Tours is a tourism platform with three user roles:

- **Tourist** – search and book tours, attend tours, access blogs  
- **Guide** – create and sell tours, view statistics about their tours  
- **Admin** – manage users, block/unblock accounts
- **Blogs** – available to all users for reading and writing

---

## ✨ Key Features
- Tour search with ability to search by street, city or by radius based on your location
- Tour details and purchasing  
- Tour creation and editing (guides)  
- Guide dashboard with sales/attendance statistics  
- Admin panel for user management  
- Blog section (list, detail view, creation)

---

## 🧱 Technologies
- **Frontend:** Angular, Angular Material  
- **Backend:** ASP.NET Core (modular monolith), EF Core, REST API, Swagger  
- **Database:** PostgreSQL  
- **Development process:** Scrum (ClickUp), GitHub PR reviews, Clean Code principles

---

## 🧭 Architecture
- Backend structured as a **modular monolith** (modules: `Blog`, `Tours`, `Encounters`, `Payments`, `Stakeholders`)  
- Frontend communicates via REST API  
