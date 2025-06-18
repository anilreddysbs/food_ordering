# Food Ordering

A web-based food ordering application built with Django. Users can browse menus, add items to their cart, and place orders online.

## Features

- Browse food menu and categories
- Add items to cart
- Place and manage orders
- User authentication (login/register)
- Admin panel for managing menu and orders

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/anilreddysbs/food_ordering.git
   cd food_ordering
   ```

2. **Create and activate a virtual environment (recommended):**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   *(If `requirements.txt` is missing, install Django manually: `pip install django`)*

4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional, for admin access):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Open your browser and visit:**  
   [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Usage

- Browse the menu and select items to order.
- Register or log in to place an order.
- Manage your orders from your account.
- Admins can manage menu items and view orders via `/admin/`.

## Folder Structure

```
food_ordering/
├── foodapp/        # Django app for food ordering logic
├── templates/      # HTML templates
├── static/         # Static files (CSS, JS, images)
├── manage.py
└── requirements.txt
```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE)

---

*Order your favorite food online with this Django-powered application!*
