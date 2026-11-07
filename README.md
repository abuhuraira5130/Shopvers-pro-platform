<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B35,50:FF8F5E,100:14B8A6&height=270&section=header&text=ShopVers%20Pro&fontSize=74&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Premium%20Full-Stack%20E-Commerce%20Platform&descSize=22&descAlignY=60" width="100%" alt="ShopVers Pro banner" />

<a href="https://shopvers.me">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&pause=1100&color=FF6B35&center=true&vCenter=true&width=820&height=50&lines=Build+trust+with+a+storefront+that+feels+premium+%E2%9C%A8;React+%2B+Vite+frontend%2C+Django+REST+backend+%E2%9A%A1;Secure+login%2C+search+%26+pagination+%F0%9F%9B%8D%EF%B8%8F;Live+on+shopvers.me+%F0%9F%9A%80" alt="Typing animation" />
</a>

<br/><br/>

[![Live Site](https://img.shields.io/badge/%F0%9F%8C%90_LIVE_SITE-shopvers.me-FF6B35?style=for-the-badge)](https://shopvers.me)
[![Status](https://img.shields.io/badge/Status-In_Active_Development-14B8A6?style=for-the-badge)](#-roadmap)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-0F172A?style=for-the-badge)](#-contributing)

![React](https://img.shields.io/badge/React-0F172A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-0F172A?style=flat-square&logo=vite&logoColor=646CFF)
![Django](https://img.shields.io/badge/Django-0F172A?style=flat-square&logo=django&logoColor=44B78B)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0F172A?style=flat-square&logo=postgresql&logoColor=4169E1)
![Vercel](https://img.shields.io/badge/Vercel-0F172A?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-0F172A?style=flat-square&logo=render&logoColor=white)

<br/>

<a href="https://shopvers.me"><b>🌐 Live Site</b></a>
&nbsp;•&nbsp;
<a href="#-features"><b>✨ Features</b></a>
&nbsp;•&nbsp;
<a href="#-getting-started"><b>🚀 Get Started</b></a>
&nbsp;•&nbsp;
<a href="#-roadmap"><b>🗺️ Roadmap</b></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF6B35,100:14B8A6&height=3&section=header" width="100%" alt="divider" />

## 📑 Table of Contents

- [🌟 About](#-about)
- [✨ Features](#-features)
- [📸 Screenshots](#-screenshots)
- [🛠️ Tech Stack](#️-tech-stack)
- [🏗️ Architecture](#️-architecture)
- [📂 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
- [🔐 Environment Variables](#-environment-variables)
- [☁️ Deployment](#️-deployment)
- [🗺️ Roadmap](#️-roadmap)
- [🤝 Contributing](#-contributing)
- [👨‍💻 Author](#-author)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF6B35,100:14B8A6&height=3&section=header" width="100%" alt="divider" />

## 🌟 About

**ShopVers Pro** is a full-stack e-commerce web application with a premium, responsive storefront powered by a **Django REST API**. It is designed to give shoppers a fast, clean, and secure experience, and to give store owners a solid foundation to sell online.

> 🌐 **Live website:** [https://shopvers.me](https://shopvers.me)

<div align="center">

| 🛒 **For Shoppers** | 🏪 **For Store Owners** | 👨‍💻 **For Developers** |
|:---:|:---:|:---:|
| Clean, responsive storefront | Backend-driven product data | Modular React + Django codebase |
| Product search & pagination | Scalable API architecture | One-command local setup |
| Secure account & login | Cloud-ready deployment | Vercel + Render ready |

</div>

> 🚧 **Project status:** ShopVers Pro is under active development. The backend is largely complete and the frontend covers the storefront home, product search and pagination, and authentication. See the [Roadmap](#️-roadmap) for what's next.

---

## ✨ Features

| | Feature | Status |
|:---:|---|:---:|
| 🎨 | **Premium responsive UI** with modern gradients and clean interactions | ✅ Live |
| 🔎 | **Product search** by title or description | ✅ Live |
| 📄 | **Pagination** for product listings | ✅ Live |
| 🔐 | **Authentication** (Login / Join Now) | ✅ Live |
| ⚙️ | **Django REST API** powering product data | ✅ Built |
| ☁️ | **Cloud deployment** (Vercel + Render + Neon PostgreSQL) | ✅ Live |
| 🛒 | **Shopping cart** | 🚧 In progress |
| 💳 | **Checkout & online payments** | 🔜 Planned |
| 📦 | **Orders & order tracking** | 🔜 Planned |
| 🧑‍💼 | **Admin dashboard** | 🔜 Planned |
| ⭐ | **Reviews & ratings** | 🔜 Planned |

---

## 📸 Screenshots

<div align="center">

| 🏠 Home | 🔐 Login |
|:---:|:---:|
| <img src="docs/screenshots/home.png" width="440" alt="ShopVers Pro home page" /> | <img src="docs/screenshots/login.png" width="440" alt="ShopVers Pro login page" /> |

</div>

---

## 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=react,vite,js,html,css,py,django,postgres,vercel,git,github" alt="Tech stack icons" />

</div>

| Layer | Technologies |
|:---:|---|
| 🎨 **Frontend** | React, Vite, JavaScript (JSX), CSS |
| ⚙️ **Backend** | Python, Django (REST API) |
| 🗄️ **Database** | PostgreSQL (Neon) |
| ☁️ **Hosting** | Vercel (frontend), Render (backend) |
| 🌐 **Domain** | [shopvers.me](https://shopvers.me) |

---

## 🏗️ Architecture

```mermaid
flowchart LR
    A[👤 Shopper] --> B[🎨 React + Vite Frontend<br/>Vercel]
    B -->|REST API| C[⚙️ Django Backend<br/>Render]
    C --> D[(🗄️ Neon PostgreSQL)]
    B -->|Login / Join| C
    C -.->|Planned| E[💳 Payment Gateway]

    classDef orange fill:#FF6B35,stroke:#c2410c,color:#ffffff;
    classDef teal fill:#14B8A6,stroke:#0f766e,color:#ffffff;
    class B,C orange;
    class D teal;
```

---

## 📂 Project Structure

```text
ecommerce-fullstack-design/
├── Backend/                  # Django REST API
├── Frontend/                 # React + Vite storefront
│   ├── src/
│   │   ├── components/       # Reusable UI components
│   │   ├── hooks/            # Custom React hooks
│   │   ├── layouts/          # Page layouts
│   │   ├── pages/            # Route pages
│   │   ├── services/         # API calls to the backend
│   │   ├── styles/           # Stylesheets
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   ├── package.json
│   ├── vite.config.js
│   └── vercel.json           # Vercel deployment config
├── render.yaml               # Render deployment config (backend)
├── production ready plan.md
└── README.md
```

---

## 🚀 Getting Started

Want a quick look? 👉 **[Open the live site](https://shopvers.me)**. To run ShopVers Pro locally:

### Prerequisites

- **Node.js** 18+
- **Python** 3.10+
- **Git**
- A PostgreSQL database (a free [Neon](https://neon.tech) database works well)

### 1️⃣ Clone the repository

```bash
git clone https://github.com/abuhuraira5130/ecommerce-fullstack-design.git
cd ecommerce-fullstack-design
```

### 2️⃣ Start the backend (Django)

```bash
cd Backend

# Create and activate a virtual environment
python -m venv venv
.\venv\Scripts\activate      # Windows
source venv/bin/activate     # Mac / Linux

# Install dependencies
pip install -r requirements.txt

# Apply database migrations and run the server
python manage.py migrate
python manage.py runserver 8000
```

### 3️⃣ Start the frontend (React + Vite)

```bash
cd Frontend
npm install
npm run dev
```

Open the local URL printed in your terminal.

---

## 🔐 Environment Variables

Example values. Adjust the names to match your project.

**Backend: `Backend/.env`**

```env
SECRET_KEY=your_django_secret_key
DEBUG=True
DATABASE_URL=your_neon_postgresql_connection_string
ALLOWED_HOSTS=localhost,127.0.0.1
CORS_ALLOWED_ORIGINS=http://localhost:5173
```

**Frontend: `Frontend/.env`**

```env
VITE_API_URL=http://localhost:8000
```

> ⚠️ **Never commit `.env` files or secret keys to GitHub.**

---

## ☁️ Deployment

| Part | Platform | Config |
|---|---|---|
| 🎨 **Frontend** | Vercel | `Frontend/vercel.json` |
| ⚙️ **Backend** | Render | `render.yaml` |
| 🗄️ **Database** | Neon PostgreSQL | Connection via `DATABASE_URL` |
| 🌐 **Domain** | shopvers.me | Custom domain |

For production, set `DEBUG=False`, add `https://shopvers.me` to `CORS_ALLOWED_ORIGINS`, and point the frontend API URL to your deployed backend.

---

## 🗺️ Roadmap

- [x] Django REST API (core)
- [x] React + Vite storefront
- [x] Product search & pagination
- [x] Authentication (login)
- [x] Live deployment on [shopvers.me](https://shopvers.me)
- [ ] Shopping cart (in progress)
- [ ] Product detail pages
- [ ] Checkout & payment integration
- [ ] Orders & order tracking
- [ ] Admin dashboard
- [ ] Reviews & ratings
- [ ] Performance & SEO improvements

---

## 🤝 Contributing

Contributions, ideas, and feedback are welcome!

1. Fork the repository
2. Create a branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m "Add amazing feature"`
4. Push: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

## 👨‍💻 Author

<div align="center">

### **Abu Huraira**
*BSAI Student · Full-Stack & AI Developer*

[![GitHub](https://img.shields.io/badge/GitHub-abuhuraira5130-0F172A?style=for-the-badge&logo=github)](https://github.com/abuhuraira5130)
[![Live Site](https://img.shields.io/badge/ShopVers_Pro-shopvers.me-FF6B35?style=for-the-badge)](https://shopvers.me)

<br/>

⭐ **If you like ShopVers Pro, give it a star!** ⭐

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B35,50:FF8F5E,100:14B8A6&height=150&section=footer" width="100%" alt="footer" />

</div>
