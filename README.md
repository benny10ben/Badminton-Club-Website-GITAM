# 🏸 Badminton Club Website (GITAM)

A dynamic web platform designed for the **GITAM Badminton Club**. This website serves as the central hub for club announcements, event registrations, team showcases, and gallery highlights.

## 🌟 Features

- **Event Management**: Admins can create and update upcoming tournaments and practice sessions.
- **Team Showcase**: Dedicated section to display club coordinators and players.
- **Gallery**: Dynamic image grid for event photos.
- **Announcements**: Real-time updates for club members.
- **Responsive Design**: Optimized for both mobile and desktop views.

## 🛠️ Tech Stack

- **Backend**: Django 5.x (Python)
- **Frontend**: HTML5, CSS3, JavaScript
- **Database**: SQLite (Development) / PostgreSQL (Production recommended)
- **Deployment**: Vercel (Configured via `vercel.json`)

---

## 🚀 Getting Started

Follow these instructions to set up the project locally on your machine.

### Prerequisites

- Python 3.10 or higher
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/benny10ben/Badminton-Club-Website-GITAM.git
cd Badminton-Club-Website-GITAM
```

### 2. Create Virtual Environment

It is recommended to use a virtual environment to manage dependencies.

```bash
# Create the environment
python -m venv myenv

# Activate it
# On Windows:
myenv\Scripts\activate
# On macOS/Linux:
source myenv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Database Setup

Initialize the database with default tables.

```bash
python manage.py migrate
```

### 5. Create Admin User

Create a superuser to access the admin panel.

```bash
python manage.py createsuperuser
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000` in your browser.

---

## 📂 Project Structure

```text
Badminton-Club-Website-GITAM/
├── Badminton__Club/      # Project settings (settings.py, urls.py)
├── club/                 # Main application logic (views, models, migrations)
├── media/                # User-uploaded content (images, videos)
├── static/               # CSS, JS, and site assets
├── templates/            # HTML Templates
├── build_files.sh        # Vercel build script
├── db.sqlite3            # Local database
├── manage.py             # Django command-line utility
└── vercel.json           # Vercel configuration
```

---