# BlogWeb

BlogWeb is a Django-based web application that allows users to create, edit, and manage blog posts. Users can register, log in, and interact with posts in a structured manner.

## Features
- User authentication (registration, login, logout)
- Create, update, and delete blog posts
- User profile management
- Bootstrap-based responsive UI
- Django Crispy Forms for enhanced form styling

## Technologies Used
- **Django**: Backend framework
- **HTML/CSS**: Frontend structure and styling
- **Bootstrap**: UI components
- **Django Crispy Forms**: Enhanced form rendering

## Installation
### Prerequisites:
- Python installed (>=3.8)
- Virtual environment setup (recommended)

### Steps:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd blogweb
   ```
2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run migrations:
   ```bash
   python manage.py migrate
   ```
5. Start the development server:
   ```bash
   python manage.py runserver
   ```
6. Open `http://127.0.0.1:8000/` in your browser.

## Project Structure
```
blogweb/
│-- blog/              # Blog app
│-- users/             # User authentication and profiles
│-- templates/         # HTML templates
│-- static/            # CSS and JavaScript files
│-- db.sqlite3         # SQLite database (default)
│-- manage.py          # Django project manager
│-- requirements.txt   # Dependencies
```

## Usage
1. Register an account.
2. Log in to create and manage blog posts.
3. Edit or delete your own posts.
4. Update your user profile.

## Future Enhancements
- Add comments and likes on posts
- Enable image uploads for posts
  
## Feel free to suggest further improvements!


