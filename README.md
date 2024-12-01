# Online-Bookstore
An online bookstore built with Django, featuring user-friendly interfaces for browsing, searching, and purchasing books. Includes advanced features like category filters, personalized recommendations, a secure checkout system, and an admin panel for efficient inventory and order management.
# Online Bookstore Project

An online bookstore application built with Django, designed to provide a seamless experience for book lovers. Users can browse, search, and purchase books effortlessly. The project includes features like category filtering, personalized recommendations, secure checkout, and an intuitive admin panel for managing inventory and orders. Perfect for learning Django's capabilities or launching a full-fledged online bookstore.  

## Features  
- **User-Friendly Book Browsing:** Explore books by categories, search by title, or use filters.  
- **Personalized Recommendations:** Display books based on user preferences.  
- **Secure Checkout:** Safe payment integration for a reliable shopping experience.  
- **Admin Panel:** Manage inventory, update book details, and track orders efficiently.  
- **Responsive Design:** Accessible on desktops, tablets, and mobile devices.  

## Requirements  
- Python 3.x  
- Django 4.x  
- SQLite or any other supported database  
- Basic understanding of Django framework  

## Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/online-bookstore.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd online-bookstore  
   ```  
3. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
4. Run migrations:  
   ```bash  
   python manage.py migrate  
   ```  
5. Start the development server:  
   ```bash  
   python manage.py runserver  
   ```  
#!/usr/bin/env python
import os
import sys

if __name__ == '__main__':
    os.environ.setdefault('DJANGO_SETTINGS_MODULE', 'bookstore.settings')
    try:
        from django.core.management import execute_from_command_line
    except ImportError as exc:
        raise ImportError(
            "Couldn't import Django. Are you sure it's installed and "
            "available on your PYTHONPATH environment variable? Did you "
            "forget to activate a virtual environment?"
        ) from exc
    execute_from_command_line(sys.argv)

# Installation 


```
    pip install django-cors-headers
    pip install django-crispy-forms
    pip install xhtml2pdf
```

</br>

![screenshot_2019-02-18 online book store 2](https://user-images.githubusercontent.com/28836413/52928808-cddf6e00-336b-11e9-9db9-58cb0fc0f0e5.png)


![Screenshot_2019-09-07 Online Book Store](https://user-images.githubusercontent.com/16104417/64470406-7a483c80-d164-11e9-93b1-cbca68a966cb.png)


## Contribution  
Contributions are welcome! Feel free to fork the repository and submit pull requests.  

## License  
This project is licensed under the MIT License.  

---  
Ready to set up your online bookstore? Dive in and start coding!
