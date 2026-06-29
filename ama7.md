# AMA7 - Django

### Q1. What is `reverse()` used for in Django views?
**Answer:**  
`reverse()` is used to generate a URL from a URL name instead of writing the URL manually.

**Example:**
```python
return redirect(reverse("home"))
```

---

### Q2. What is Celery?
**Answer:**  
Celery is a background task queue used to run long or time-consuming tasks asynchronously.

**Example:**
- Sending emails
- Processing large files

---

### Q3. How do you optimize slow Django ORM queries?
**Answer:**  
Use `select_related()` and `prefetch_related()` to reduce database queries, and fetch only the required data.

**Example:**
```python
Book.objects.select_related("author")
```

---

### Q4. How can we access images in a form?
**Answer:**  
Use `request.FILES` along with `request.POST` and make sure the form uses `enctype="multipart/form-data"`.

**Example:**
```python
form = ImageForm(request.POST, request.FILES)
```

---

### Q5. What is an `F` object?
**Answer:**  
An `F` object lets you perform database operations using the current field value without loading it into Python.

**Example:**
```python
Product.objects.update(stock=F("stock") - 1)
```

---

### Q6. What is `get_object_or_404()`?
**Answer:**  
It retrieves an object if it exists; otherwise, it returns a 404 error instead of crashing.

**Example:**
```python
book = get_object_or_404(Book, id=1)
```

---

### Q7. How do you add a horizontal scrollbar?
**Answer:**  
Use CSS `overflow-x: auto;` or `overflow-x: scroll;`.

**Example:**
```css
.container {
    overflow-x: auto;
}
```

---

### Q8. What is a `.env` file?
**Answer:**  
A `.env` file stores environment variables like secret keys, passwords, and API keys outside the source code.

**Example:**
```env
SECRET_KEY=abc123
DEBUG=False
```

---

### Q9. What does `get_or_create()` do?
**Answer:**  
It gets an existing object if found; otherwise, it creates a new one.

**Example:**
```python
user, created = User.objects.get_or_create(username="mani")
```

---

### Q10. What is debouncing?
**Answer:**  
Debouncing delays the execution of a function until the user stops triggering the event for a specified time.

**Example:**
- Search box API calls
- Window resize events
