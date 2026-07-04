# AMA 8

### Q: What is Celery?
**A:** Celery is a background task queue used to run long or scheduled tasks asynchronously, so they don't block the main application.

### Q: Difference between User and AbstractUser?
**A:** `User` is Django's built-in user model. `AbstractUser` lets you create a custom user model by extending the default fields.

### Q: What is the use of Authentication Middleware?
**A:** Authentication Middleware identifies the logged-in user from the session and makes it available as `request.user` in every request.

### Q: What is Elasticsearch?
**A:** Elasticsearch is a search engine used for fast full-text searching, filtering, and analyzing large amounts of data.

### Q: What is the Q object in Django?
**A:** A `Q` object is used to build complex database queries with `AND`, `OR`, and `NOT` conditions.

### Q: What are some common form fields in Django?
**A:** Common form fields include `CharField`, `EmailField`, `IntegerField`, `BooleanField`, `DateField`, `ChoiceField`, and `FileField`.

### Q: What is the use of a class method?
**A:** A class method works with the class instead of an object and is commonly used for alternative constructors or class-level operations.

### Q: What do the `login()` and `logout()` methods do?
**A:** `login()` authenticates a user and starts a session. `logout()` ends the user's session and logs them out.

### Q: Difference between `preventDefault()` and `stopPropagation()`?
**A:** `preventDefault()` stops the browser's default action, while `stopPropagation()` stops the event from bubbling to parent elements.
