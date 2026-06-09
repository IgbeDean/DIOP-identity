# DIOP Identity Engine

DIOP Identity is a robust, enterprise-ready backend authentication and identity management system built with **Django 6** and backed by a relational **PostgreSQL** database. It seamlessly bridges secure manual credentials management with seamless third-party social authentication.

## 🚀 Key Features

* **Custom User Architecture:** Extended Django user models paired with signals to automate profile generation upon registration.
* **Dual Authentication Pipeline:** Supported by unified manual login and native Google OAuth (via `django-allauth`).
* **Brute-Force & Security Protection:** Armed with `django-axes` to track failed access attempts by IP and username, generating real-time lockout countdown warnings.
* **Unified Visual Feedback:** Customized background signal listeners to harmonize flash messages ("Welcome back!") perfectly across both standard and OAuth sessions.
* **Enterprise Database Foundation:** Migrated seamlessly from SQLite to robust PostgreSQL tables.

---

## 🛠️ Tech Stack

* **Backend Framework:** Django (v6.0+)
* **Database:** PostgreSQL
* **Identity & OAuth:** django-allauth
* **Security & Gatekeeping:** django-axes
* **Environment Management:** Python `venv` & `python-dotenv`

---

## ⚙️ Local Installation & Setup

Since the repository already contains the structural codebase, follow these steps to spin it up locally:

### 1. Clone the Repository
```bash
git clone [https://github.com/IgbeDean/DIOP-identity.git](https://github.com/IgbeDean/DIOP-identity.git)
cd DIOP-identity