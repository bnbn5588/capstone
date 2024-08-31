# Little Lemon Backend

> Little Lemon Backend is a robust Django backend designed to power the Little Lemon app, the API offers endpoints for managing customers, menu items, categories, orders, delivery crew users and user groups.

## Project Requirements

- Users should be able to register, login and logout
- Customers should be able to browse menu items and categories, add items to cart, clear their cart, make orders
- Managers should be able to fully manage categories and menu items, they can also update orders, assign delivery crew orders and assign customers a group
- Delivery crew users should be able to update their assigned orders

## Live API

[View Live API Website/Docs](https://little-lemon-backend.onrender.com/)

![Deployed backend website with documentation screenshot](https://github.com/mehdiaitouchrif/little-lemon-backend/assets/112659075/349fb2ef-3156-4573-ac71-1e89e8a959f2)

## Installation

1. Clone the repository

```bash
git clone git@github.com:mehdiaitouchrif/little-lemon-backend.git
```

2. Create a virtual environment and activate it

```python
python3 -m venv env
source env/bin/activate
```

3. Install the dependencies
   pip install -r requirements.txt

4. Run the server

```bash
   python manage.py runserver
```
