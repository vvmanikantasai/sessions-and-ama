#### AMA

### What is a secret key?
A secret key is a unique random string used by Django for cryptographic signing, sessions, and security purposes.

### If you send a JSON response then there is parameter `safe=True`. Why?
`safe=True` allows only dictionaries to be returned. To return lists or other objects, set `safe=False`.

### Use of `ALLOWED_HOSTS` in `settings.py`
`ALLOWED_HOSTS` specifies which domain names or IP addresses can serve the Django application to prevent host header attacks.

### Why can't we use `python manage.py runserver` in production?
`runserver` is a development server; it is slow, single-process, and not designed to handle production traffic securely.

### Why do we use WhiteNoise in production?
WhiteNoise serves static files efficiently in production without requiring a separate web server like Nginx.

### What is `on_delete=models.CASCADE`?
When a parent object is deleted, all related child objects are deleted automatically.

### What is ORM?
ORM (Object Relational Mapper) lets you interact with the database using Python objects instead of writing SQL queries.

### How can we access data in a `.env` file?
Load the `.env` file using packages like `python-dotenv` and access values with `os.getenv()`.

### How do you create a superuser?
Run `python manage.py createsuperuser` and provide the username, email, and password.

### Purpose of Gunicorn
Gunicorn is a production-grade WSGI server used to run Django applications efficiently and handle multiple requests.

### What do you mean by namespacing and why do we use it?
Namespacing gives unique names to URLs to avoid conflicts when different apps have URLs with the same name.
