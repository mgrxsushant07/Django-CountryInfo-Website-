# CountryInfo 🌍

A Django-based web application that provides information about different countries using Django models and templates. This project demonstrates how to structure a Django app, utilize models for data storage, and render dynamic content with templates.

## Features 🚀
- 🌎 Display detailed country information
- 🏗️ Django models for structured data storage
- 🎨 Clean and responsive UI with Django templates
- 🔧 Easily customizable and extendable

## Tech Stack 🛠
- **Django (Python)** 🐍
- **HTML, CSS** (Django Templates) 🎨
- **SQLite/PostgreSQL** (Database) 🗄️

## Installation & Setup ⚙️

### Prerequisites
Make sure you have Python and Django installed:
```sh
python3 --version
pip install django
```

### Clone the Repository
```sh
git clone https://github.com/yourusername/countryinfo.git
cd countryinfo
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

### Apply Migrations
```sh
python manage.py migrate
```

### Run the Server
```sh
python manage.py runserver
```
Visit `http://127.0.0.1:8000/` in your browser.

## Project Structure 📂
```
countryinfo/
│-- countryinfo/        # Project settings and configuration
│-- info/               # Main app for country information
│   ├── models.py       # Database models
│   ├── views.py        # Business logic
│   ├── templates/      # HTML templates
│-- static/             # CSS, JS, Images
│-- db.sqlite3          # Database file (if using SQLite)
│-- manage.py           # Django CLI
```

## Contributing 🤝
Pull requests are welcome! Feel free to contribute by forking the repo and submitting a PR.

## License 📜
This project is licensed under the MIT License.

---
⭐ **Don't forget to star this repository if you find it useful!** ⭐
