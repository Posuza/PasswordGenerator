# Django Password Generator

A simple web application built with Django that generates random passwords based on user-selected criteria.

## Features

- Generate random passwords with customizable length (6-14 characters)
- Include uppercase letters
- Include numbers
- Include special characters
- Clean and simple user interface

## Screenshots

(Add screenshots of your application here)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/django-password-generator.git
   cd django-password-generator
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```
   python manage.py migrate
   ```

5. Start the development server:
   ```
   python manage.py runserver
   ```

6. Open your browser and navigate to `http://127.0.0.1:8000/`

## Usage

1. Visit the homepage
2. Select the desired password length from the dropdown menu
3. Check the boxes for the character types you want to include:
   - Uppercase letters
   - Numbers
   - Special characters
4. Click "Generate Password"
5. Your generated password will be displayed on the next page

## Project Structure

```
django-password-generator/
├── generator/                # Main application
│   ├── templates/generator/  # HTML templates
│   │   ├── about.html        # About page
│   │   ├── home.html         # Homepage with password options
│   │   └── password.html     # Page displaying generated password
│   ├── views.py              # View functions
│   └── ...
├── password_generator/       # Project settings
│   ├── settings.py
│   ├── urls.py               # URL configurations
│   └── ...
└── manage.py                 # Django management script
```

## Technologies Used

- Django 3.x
- Python 3.x
- HTML

## Future Improvements

- Add password strength indicator
- Save generated passwords (with encryption)
- Add user authentication
- Improve UI with CSS/Bootstrap
- Add copy to clipboard functionality
