Lieferspatz - Liefrando simulation <br/>
A food delivery web application built with Flask (Python backend) and HTML/CSS (frontend).
------------------------

Project Overview
This project is a food delivery platform where:

<li> Restaurants can manage menus and orders.
<li> Customers can browse restaurants and place orders.
<li> Admins can oversee operations.

Key features:
<li>✅ User authentication (Customers & Restaurants)
<li>✅ Order management system
<li>✅ Database integration (Lieferspatz.db)
<li>✅ Flask routing & blueprints for modularity
<br/>
<br/>
  
| Category |	Technologies |
| --- | --- |        
| Backend	 |  Python, Flask, SQLite |
| Frontend |	HTML, CSS (no JavaScript framework) |
| Database |	SQLite (Lieferspatz.db) |
| Routing	 |  Flask Blueprints (customer_blueprint.py, restaurant_blueprint.py) |

Project Structure
-------------------------------------
```
├── static/               # Static files (CSS, images, etc.)
├── templates/            # HTML templates
├── app.py                # Main Flask application
├── Lieferspatz.db        # SQLite database
├── customer_blueprint.py # Customer-related routes
├── restaurant_blueprint.py # Restaurant-related routes
├── decorator.py          # Auth decorators (e.g., @login_required)
├── functions.py          # Helper functions
├── Class_f.py            # Custom classes (if any)
└── Restaurant.py         # Restaurant management logic
```

Setup & Installation
------------------------------------
1. Clone the Repository
  ```bash
  git clone https://github.com/your-username/Lieferspatz.git
  cd Lieferspatz
  ```
2. Install Dependecies
  ```bash
  pip install flask flask-sqlalchemy
  ```
3. Run the Application
  ```bash
  python app.py
  ```
4. access at :
  ```bash
  http://localhost:5000
  ```

