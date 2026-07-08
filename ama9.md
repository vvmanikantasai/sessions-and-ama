# AMA9

### Q: How do we create a constructor in a Python class?
**A:** A constructor is created using the `__init__()` method, which is automatically called when an object is created.

### Q: Difference between APIView and GenericAPIView?
**A:** `APIView` requires you to write most of the logic manually, while `GenericAPIView` provides reusable functionality like querysets, serializers, and mixins.

### Q: What is a ViewSet?
**A:** A ViewSet groups related CRUD operations into a single class, reducing code duplication in Django REST Framework.

### Q: What is JWT Authentication?
**A:** JWT (JSON Web Token) Authentication authenticates users using a signed token instead of storing session data on the server.

### Q: What is a Nested Serializer?
**A:** A nested serializer includes related model data inside another serializer, allowing you to return related objects in a single API response.

### Q: What is the use of the `super()` method in Python?
**A:** `super()` calls methods from the parent class, allowing child classes to reuse or extend parent functionality.

### Q: What are HTTP Status Codes?
**A:** HTTP status codes are standard response codes returned by a server to indicate the result of a client's request (e.g., 200, 404, 500).

### Q: What is the advantage of Django REST Framework (DRF)?
**A:** DRF simplifies API development by providing serializers, authentication, permissions, validation, and browsable APIs.

### Q: Difference between `Serializer` and `ModelSerializer`?
**A:** `Serializer` requires you to define all fields manually, while `ModelSerializer` automatically generates fields from a Django model.
