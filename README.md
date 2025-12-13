# Full-Stack Web Application

- This is a full-stack web application.
- The project is structured using **Git submodules** to keep frontend and backend concerns cleanly separated while still presenting the project under a single parent repository.

---

## 🧱 Project Structure

- **Frontend** and **Backend** are maintained as independent repositories.
- The parent repository tracks stable versions of each via Git submodules.

This approach preserves **full commit history and ownership** for both parts of the application.

---

## 🚀 Tech Stack

### Frontend
- React
- Deployed on **Vercel**

### Backend
- Node.js
- Express.js
- Deployed on **Render**

---

## 🔗 Repositories

- **Frontend Repository**: [(Git submodule)](https://github.com/Tharindu-Gimhana/computer-shop-management-system-front-end)
- **Backend Repository**: [(Git submodule)](https://github.com/Tharindu-Gimhana/computer-shop-management-system)

Each submodule contains its own complete commit history, reflecting the development process of the project.

---

## 🛠️ Local Setup

```bash
git clone (https://github.com/Tharindu-Gimhana/-ROOT-computer-shop-management-system-)
cd project-root → enter the folder
git submodule update --init --recursive    → download the submodules (frontend & backend)

