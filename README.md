# Market

### Description

The store is made on django version 2.1, python 3.9. With bootstrap, CSS, HTML5, JavaScript for the front and PostgreSQL.
The store has the following features:

- List of all products;
- List of categories;
- Adding images to the product;
- Possibility of inclusion and removal from the basket;
- Place an order through the basket, thereby adding it to the database;
- Authorization of users;

---

### Technologies:
* Python
* Django
* Pytest
* Git

---

### Installation
Clone the repository on the local machine:

```$ git clone https://github.com/vkletkin/Market```

 Create a virtual environment:
 
 ```$ python -m venv venv```
 
 Install dependencies:

```$ pip install -r requirements.txt```

Creating and applying migrations:

```$ python manage.py makemigrations``` and  ```$ python manage.py migrate```

Starting the django server:

```$ python manage.py runserver```

---
