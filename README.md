# Atlantis Dark Django

Open-source **Django Dashboard** generated by `AppSeed` op top of a modern `Bootstrap` design. **Atlantis Lite** is a free bootstrap 4 admin dashboard that is beautifully and elegantly designed to display various metrics, numbers or data visualization. Atlantis Lite admin dashboard has 2 layouts, many plugins and UI components to help developers create dashboards quickly and effectively so they can save development time and also help users to make the right and fast decisions based on existing data.

- 👉 [Atlantis Dark Django](https://appseed.us/product/atlantis-dark/django/) - Product page
- 👉 [Atlantis Dark Django](https://django-atlantis-dark.appseed-srv1.com/) - LIVE Demo
- 👉 [Complete documentation](https://docs.appseed.us/products/django-dashboards/atlantis-dark) - `Learn how to use and update the product`
  - ✅ [Set up the environment](https://docs.appseed.us/products/django-dashboards/atlantis-dark#environment)
  - ✅ [Manage App users](https://docs.appseed.us/products/django-dashboards/atlantis-dark#manage-app-users)
  - ✅ [Application Bootstrap Flow](https://docs.appseed.us/products/django-dashboards/atlantis-dark#application-bootstrap-flow)
  - ✅ [App Routing](https://docs.appseed.us/products/django-dashboards/atlantis-dark#project-routing)
  - ✅ [UI Assets and Templates](https://docs.appseed.us/products/django-dashboards/atlantis-dark#ui-assets-and-templates)
  - ✅ [Set up the MySql Database](https://docs.appseed.us/products/django-dashboards/atlantis-dark#set-up-the-mysql-database)
  - ✅ [Adding a new app](https://docs.appseed.us/products/django-dashboards/atlantis-dark#adding-a-new-app)
  - ✅ [Static Assets for production](https://docs.appseed.us/products/django-dashboards/atlantis-dark#static-assets-for-production)  
  
<br />

> Built with [Atlantis Dark Generator](https://appseed.us/generator/atlantis-dark/)

- Timestamp: `2022-06-16 00:21`
- Build ID: `b999611e-7c4d-49cf-8b09-3d0c0c36041b`
- **Free [Support](https://appseed.us/support/)** (registered users) via `Email` and `Discord`

<br />

> Features

- `Up-to-date dependencies`
- Database: `sqlite`
- UI-Ready app, Django Native ORM
- `Session-Based authentication`, Forms validation

<br />

![Atlantis Dark - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172799909-4cbc8eed-fdde-4408-ab61-123f235212d0.png)

<br />





## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/b999611e-7c4d-49cf-8b09-3d0c0c36041b.git
$ cd b999611e-7c4d-49cf-8b09-3d0c0c36041b
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Database

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> Start the app

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

## ✨ Create Users

By default, the app redirects guest users to authenticate. In order to access the private pages, follow this set up: 

- Start the app via `flask run`
- Access the `registration` page and create a new user:
  - `http://127.0.0.1:8000/register/`
- Access the `sign in` page and authenticate
  - `http://127.0.0.1:8000/login/`

<br />

## ✨ Code-base structure

The project is coded using a simple and intuitive structure presented below:

```bash
< PROJECT ROOT >
   |
   |-- core/                               # Implements app configuration
   |    |-- settings.py                    # Defines Global Settings
   |    |-- wsgi.py                        # Start the app in production
   |    |-- urls.py                        # Define URLs served by all apps/nodes
   |
   |-- apps/
   |    |
   |    |-- home/                          # A simple app that serve HTML files
   |    |    |-- views.py                  # Serve HTML pages for authenticated users
   |    |    |-- urls.py                   # Define some super simple routes  
   |    |
   |    |-- authentication/                # Handles auth routes (login and register)
   |    |    |-- urls.py                   # Define authentication routes  
   |    |    |-- views.py                  # Handles login and registration  
   |    |    |-- forms.py                  # Define auth forms (login and register) 
   |    |
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/                     # Templates used to render pages
   |         |-- includes/                 # HTML chunks and components
   |         |    |-- navigation.html      # Top menu component
   |         |    |-- sidebar.html         # Sidebar component
   |         |    |-- footer.html          # App Footer
   |         |    |-- scripts.html         # Scripts common to all pages
   |         |
   |         |-- layouts/                   # Master pages
   |         |    |-- base-fullscreen.html  # Used by Authentication pages
   |         |    |-- base.html             # Used by common pages
   |         |
   |         |-- accounts/                  # Authentication pages
   |         |    |-- login.html            # Login page
   |         |    |-- register.html         # Register page
   |         |
   |         |-- home/                      # UI Kit Pages
   |              |-- index.html            # Index page
   |              |-- 404-page.html         # 404 page
   |              |-- *.html                # All other pages
   |
   |-- requirements.txt                     # Development modules - SQLite storage
   |
   |-- .env                                 # Inject Configuration via Environment
   |-- manage.py                            # Start the app - Django default start script
   |
   |-- ************************************************************************
```

<br />



## ✨ PRO Version

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Black Dashboard is a premium Bootstrap Design now available for download in Django. Made of hundred of elements, designed blocks, and fully coded pages, Black Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [Atlantis Dark PRO Django](https://appseed.us/product/atlantis-dark-pro/django/) - Product Page
- 👉 [Atlantis Dark PRO Django](https://django-atlantis-dark-pro.appseed-srv1.com/) - LIVE Demo

<br >

![Atlantis Dark PRO - Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/172800034-4d3adb79-d05e-430d-8ffe-f6860fc755f1.png)

<br />

---
Atlantis Dark Django - Open-source starter generated by **[AppSeed Generator](https://appseed.us/generator/)**.
