# 📸 Instagram Clone (Django)

A simplified Instagram clone built with **Django**.  
The project reproduces basic Instagram functionality: user accounts, posts, stories, likes, comments, subscriptions, and search.

---

## ✨ Features
- User registration and authentication  
- Edit profile and change password  
- Create and publish posts 
- Like and comment on posts  
- View comments under posts  
- Follow and unfollow other users  
- Built-in search to find users  

---

## 🛠️ Tech Stack
- **Backend:** Django, Python 
- **Database:** SQLite (default Django DB)  
- **Frontend:** Django templates, Bootstrap  
- **Other:** Django ORM, Django auth system  

---

## 🚀 Installation & Run (via venv)

### 1. Clone the repository and go to the project folder
```bash
git clone https://github.com/Fort-Rage/Instagram-Clone.git
cd instagram
```

### 2. Create and activate a virtual environment

**On Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**On Linux/Mac:**
```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r reqs.txt
```

### 4. Apply database migrations
```bash
python manage.py migrate
```

### 5. Load fixtures (initial demo data)
```bash
python manage.py loaddata fixtures/auth_dump.json
python manage.py loaddata fixtures/dump.json
```

### 6. Start the development server
```bash
python manage.py runserver
```

---

## 👤 Demo Account
You can log in with the demo account to avoid creating a new user and following others manually:
```
Username: guest
Password: guest
```
