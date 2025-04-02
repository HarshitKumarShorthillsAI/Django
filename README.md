# Tweet App

This is a simple Tweet application built using the Django framework. The application allows users to create, edit, and view tweets.

## Features
- User authentication (Login & Logout)
- Create, edit, and delete tweets
- View a list of all tweets
- Responsive UI using Bootstrap

## Installation

### 1. Clone the repository
```sh
git clone https://github.com/HarshitKumarShorthillsAI/Django.git
cd django-tweet-app
```

### 2. Create and activate a virtual environment
```sh
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install dependencies
```sh
pip install -r requirements.txt
```

### 4. Run migrations
```sh
python manage.py migrate
```

### 5. Create a superuser
```sh
python manage.py createsuperuser
```
Follow the instructions to create an admin account.

### 6. Run the server
```sh
python manage.py runserver
```
Access the app at `http://127.0.0.1:8000/`

## Project Structure
```
├── djangoharshit/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   ├── asgi.py
├── tweets/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   ├── urls.py
│   ├── templates/
│   │   ├── tweet_list.html
│   │   ├── tweet_form.html
│   │   ├── base.html
├── static/
│   ├── css/
│   ├── js/
├── manage.py
└── README.md
└── Requirements.txt
```

## Contributing
Feel free to fork this repository and submit pull requests. If you find any issues, please create an issue on GitHub.

## License
This project is licensed under the MIT License.
