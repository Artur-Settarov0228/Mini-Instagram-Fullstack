# 📸 Mini-Instagram-Fullstack
### Mini Instagram – Fullstack (API + Templates)

Mini Instagram — bu **Instagram’ga o‘xshash to‘liq backend + frontend (Django Templates)** loyihasi.  
Loyiha **portfolio**, **intervyu** va **real backend tajriba** uchun mo‘ljallangan.

---

## 🚀 Features

### 👤 Authentication & Profile
- User registration & login  
- JWT authentication (access & refresh)  
- User profile (avatar, bio)  
- Public / Private profile  
- Follow request (private account)  

---

### ➕ Follow System
- Follow / Unfollow user  
- Followers & Following list  
- Follow request (accept / reject)  

---

### 🖼 Posts
- Create post with image  
- Update & delete own post  
- Feed (follow qilingan userlar postlari)  
- Post detail view  

---

### ❤️ Like System
- Like / Unlike post  
- One user → one like per post  
- Like count  

---

### 💬 Comment System
- Add comment  
- View comments  
- Comment owner permission  

---

### ⏳ Stories
- Upload stories (image/video)  
- Auto-expire after 24 hours  
- View stories of followed users  

---

### 🔔 Notifications
- Follow notification  
- Like notification  
- Comment notification  
- Read / unread status  

---

### 💬 Chat (Basic DM)
- Send message  
- Conversation list  
- Message history  

---

### 🔍 Search
- Search users by username  
- Search posts by caption  

---

### 📊 Statistics
- Likes count  
- Comments count  
- Followers / following count  

---

## 🧱 Full Project Structure (API + Templates)

```text
mini_instagram/
├── manage.py
├── core/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── apps/
│   ├── users/              # User, Profile, Follow
│   ├── posts/              # Posts & Stories
│   ├── interactions/       # Like, Comment
│   ├── notifications/      # Notifications
│   └── chat/               # Direct Messages
│
├── templates/
│   ├── base.html
│   ├── auth/
│   ├── profile/
│   ├── posts/
│   ├── stories/
│   ├── chat/
│   └── notifications/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── media/
├── requirements.txt
└── README.md
## 🛠 Tech Stack

- **Python**
- **Django**
- **Django REST Framework**
- **JWT Authentication**
- **PostgreSQL**
- **Django Templates**
- **HTML / CSS / JavaScript**
- **Pillow** (image upload)

---

## 🔐 Permissions & Security

- JWT protected endpoints  
- Owner-based permissions  
- Private profile access control  
- Secure follow system  

---

## 📌 API Endpoints (Example)

```http
POST   /api/auth/register/
POST   /api/auth/login/

GET    /api/profile/me/
GET    /api/profile/{id}/

POST   /api/posts/
GET    /api/posts/
POST   /api/posts/{id}/like/
POST   /api/posts/{id}/comment/

POST   /api/users/{id}/follow/
POST   /api/users/{id}/unfollow/
## ⚙️ Installation

```bash
git clone https://github.com/yourusername/mini-instagram.git
cd mini-instagram

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
🎯 Project Goal

Real-world Instagram clone logic

Clean backend architecture

Fullstack (API + Templates)

Interview-ready portfolio project

👨‍💻 Author

Artur
Python Backend Developer
Django | DRF | PostgreSQL

🏆 Interview Pitch

“Mini Instagram’ni Django REST API + Django Templates bilan qildim.
Auth, follow system, post, like, comment, stories, notification va chat mavjud.”

🚀 Next Steps

✅ Project setup

✅ CustomUser + JWT

✅ Base template (base.html) + Login / Register

✅ Post upload

✅ Like / Follow system


---

### ✅ Natija
Bu bo‘lim:
- GitHub’da **toza va professional** ko‘rinadi  
- Intervyuda **tayyor gap** sifatida ishlatiladi  
- Portfolio’ni **kuchli qiladi**

Agar xohlasang, keyingi qadamda:
- `requirements.txt` ni to‘liq yozib beraman  
- yoki **1-bosqich: project setup** ni real kod bilan boshlaymiz  

👉 shunchaki **“mini instagram”** deb yoz 💪🔥
