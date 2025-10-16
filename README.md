# 🧾 SmartBiz Manager
A full-stack **Business Management System** built with **Laravel 10**, designed to streamline daily business operations such as customer management, invoicing, inventory, and reporting — all in one place.

---

## 🚀 Overview
**SmartBiz Manager** is a web-based system that demonstrates end-to-end web and online system development using modern technologies.  
It includes both **front-end** and **back-end** functionalities, RESTful API integration, CMS connectivity (WordPress), and deployment on a **Linux-based server** environment.

---

## 🎯 Core Features
- 🔐 **Role-based Authentication** (Admin, Staff, Client)
- 👥 **Customer Management** – Add, edit, and view customers
- 📦 **Product & Inventory Control** – Manage stock levels, categories, and alerts
- 🧾 **Invoicing & Payments** – Generate and send invoices (PDF export)
- 💹 **Analytics Dashboard** – Visualize business KPIs using Chart.js
- 🌐 **REST API** – Internal and external API endpoints with Laravel Sanctum
- 📰 **WordPress Blog Integration** via REST API
- 🕒 **Automated Reports** – Email reports using Laravel Scheduler
- ☁️ **Deployed on Ubuntu** using Nginx, Git, and SSL (Certbot)

---

## 🧰 Tech Stack

| Category | Technology |
|-----------|-------------|
| **Backend** | Laravel 10 (PHP 8.2+) |
| **Frontend** | Bootstrap 5, Vue.js (optional) |
| **Database** | MySQL 8 |
| **Server** | Ubuntu 22.04 LTS, Nginx |
| **Version Control** | Git, GitHub |
| **CMS** | WordPress (REST API integration) |
| **APIs** | Laravel Sanctum, Mailgun (Email), Currency API |
| **Other Tools** | Composer, Node.js (Vite), Laravel Excel, DomPDF |

---

## ⚙️ Installation Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Shadam98/smartbiz.git
cd smartbiz

2️⃣ Install Dependencies
composer install
npm install && npm run dev

3️⃣ Setup Environment

Copy .env.example to .env and update:

cp .env.example .env
php artisan key:generate
