### What are the key components of a Docker container, and how do they help streamline the development and deployment of applications?

Docker containers consist of two main components:

1. Docker Image: A read-only template with all application dependencies and configurations.
2. Docker Container: An instance of a Docker image that runs the application in an isolated environment.

These components streamline development and deployment by ensuring consistency, portability, and ease of management across different systems. Docker images are versioned and easily reproducible, while containers offer a lightweight, isolated runtime environment for applications. Docker's standardized approach simplifies application deployment and scaling, making it more efficient for developers and system administrators.

### Describe the primary steps involved in building a library website using Django, including essential components like models, views, and templates.

1. **Setup and Installation:** Install Django and create a new project and app.

2. **Create Models:** Define Django models for books, authors, and categories in the `models.py` file.

3. **Create Views:** Write views as Python functions to handle user requests and render data from the models.

4. **URL Configuration:** Map URLs to views using URL patterns in the `urls.py` file.

5. **Create Templates:** Design HTML templates to render data from the views and display them to users.

6. **Static Files:** Manage static files (e.g., CSS, JavaScript) to style and enhance the website.

7. **Migrations:** Apply database migrations to create tables for models in the database.

8. **Admin Interface:** Optionally, set up the Django admin interface for easy content management.

9. **Testing and Debugging:** Test the website and debug issues, if any.

10. **Deployment:** Deploy the Django application to a web server for public access.



### Can you explain the primary differences between Django and Django REST framework?



| Feature                                | Django                                     | Django REST framework                        |
|----------------------------------------|--------------------------------------------|----------------------------------------------|
| Purpose                                | Full-stack web framework for web apps     | Framework for building RESTful APIs          |
| API Support                            | Possible, but requires manual handling    | Specifically designed for creating APIs      |
| Serialization                         | Requires manual serialization             | Built-in serialization with serializers     |
| View and URL Patterns              | Generic views and URL patterns            | Class-based views and URL patterns           |
| Authentication and Permissions | Basic authentication & permissions       | Enhanced authentication & permission options |
| Browsable API                         | No                                       | Yes                                          |

