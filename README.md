reliance-grocery-frontend/
│
├── index.html                # Main HTML page
├── app/
│   ├── components/           # Reusable AngularJS components (Navbar, Products, Cart)
│   ├── services/             # AngularJS services for API calls
│   ├── app.js                # AngularJS main app script
│   └── styles/
│       ├── main.css          # Custom CSS
│       └── bootstrap.min.css # Bootstrap CSS
├── images/                   # Product images and assets
└── assets/

reliance-grocery-backend/
│
├── reliance_grocery/        # Django project directory
│   ├── __init__.py
│   ├── settings.py          # Database & other settings
│   ├── urls.py              # URL routing
│   ├── wsgi.py              # WSGI configuration
│   └── asgi.py              # ASGI configuration
├── products/                # Django app for product management
│   ├── migrations/
│   ├── models.py            # Database models (Product, Order)
│   ├── views.py             # Views for the API
│   ├── serializers.py       # Serializers for converting models to JSON
│   └── urls.py              # API routing for products and orders
├── manage.py               # Django management script
└── db.sqlite3              # SQLite database (can be replaced with MySQL/PostgreSQL for production)
