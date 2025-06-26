# Underworld Crusaders Internal Portal

Welcome to the private internal portal of **Underworld Crusaders**, created and maintained by [Kraziman](https://github.com/Kraziman).  
This project powers a self-hosted system connected to my personal home database and tools.

---

## ⚔️ Purpose

This portal serves as a secure interface for managing my private systems, services, and data. It is **not open to the public** and access is restricted via **GitHub OAuth login**.

---

## 🛠️ Tech Stack

- **Frontend**: React + HTML/CSS + Bootstrap
- **Backend**: Spring Boot (Java)
- **Database**: MySQL
- **Deployment**: Docker + Docker Compose
- **Auth**: GitHub OAuth2 (Spring Security)

---

## 🔐 Security

- Only authorized GitHub accounts (mine) can log in.
- All access is protected using OAuth2 login and role-based authorization.
- HTTPS enforced via reverse proxy (e.g., Nginx or Caddy).
- External access is secured with firewalls, fail2ban, and optional VPN.

---

## ⚙️ Features (in progress)

- 🔒 Secure GitHub login
- 🗃️ Dashboard for tools, stats, and logs
- 📁 File/media manager
- 📊 Grafana monitoring (via subdomain)
- 🧠 Knowledge base or private wiki
- 🧾 Vault (password manager integration)
- 🔧 Admin panel with role management

---

## 🧪 Future Plans

- Role-based access for selected friends or admins
- Public-facing site or blog (optional)
- Crusade Quests RPG system integration
- Custom announcements and reminders
- API access to home database (read-only/limited)

---

## 🚫 License

This project is **private and for personal/internal use only**.  
Unauthorized distribution, reproduction, or modification is prohibited.

All rights reserved © 2025 Kraziman / Underworld Crusaders.

---

## 📁 Structure Overview

```
project-root/
├── backend/ # Spring Boot API server
│ └── ...
├── frontend/ # React app with Bootstrap
│ └── ...
├── docker-compose.yml
└── README.md
```

---

## 🧙 Author

Built with 🔥 by **Kraziman**, founder of Underworld Crusaders.  
Follow the crusade: [github.com/Kraziman](https://github.com/Kraziman)
