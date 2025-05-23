WatchShop Web Application 

A full-stack e-commerce web application built with Django.

Technologies Used
Backend:** Python, Django, SQLite
Frontend:** HTML, CSS, JavaScript
Database:** SQLite3
Deployment:** (Mention if you’ve used Heroku, Render, etc.)

Features
- User Signup/Login
- Upload Watches (for Admin/Seller)
- Add to Cart / Wishlist
- Product Reviews
- AJAX-based frontend-backend interactions

How to Run Locally

1. Clone the Repository
```bash
git clone https://github.com/mohdabrar07/WatchShop.git
cd WatchShop
 
 2. Create a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Requirements
pip install -r requirements.txt

4. Run Migrations
python manage.py makemigrations
python manage.py migrate

5. Run the Development Server
python manage.py runserver

6. Recreate Admin User
python manage.py createsuperuser


Login credentials inside application:
Username: username
Password:password 

Or you can Signup by clicking on SignUp button.
