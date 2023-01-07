# **[Django Admin Material2 PRO](https://appseed.us/product/material-dashboard2-pro/django/)**

**Django** starter styled with **[Admin Material PRO](https://appseed.us/product/material-dashboard2-pro/django/)**, a premium `Boostrap 5` design from [Creative-Tim](https://bit.ly/3fKQZaL)
The product is designed to deliver the best possible user experience with highly customizable feature-rich pages. 

> 👉 **NOTE**: This product `requires a License` in order to access the theme:

**Private REPO**: `git+https://github.com/app-generator/priv-django-admin-material2-pro`

<br />

## Features: 

- **UI Kit**: Material Dashboard2 BS5 PRO `v3.0.5` by Creative-Tim
- [Django Material2 PRO](https://appseed.us/product/material-dashboard2-pro/django/) - `sample project`
- **Sections Covered**: 
  - `Admin Section`, reserved for `superusers`
  - `All pages` managed by `Django.contrib.AUTH`
  - `Registration` page
  - `Misc pages`: colors, icons, typography, blank-page 

<br />

![Material Dashboard BS5 - Modern Dashboard design by Creative-Tim.](https://user-images.githubusercontent.com/51070104/209104783-22f04139-8919-457c-b21d-7383d57f07b1.png)

<br />

## Why `Django Admin Material PRO`

- Modern [Bootstrap 5](https://www.admin-dashboards.com/bootstrap-5-templates/) Design
- `Responsive Interface`
- `Minimal Template` overriding
- `Easy integration`

Material Dashboard 2 PRO makes use of light, surface and movement. The general layout comes with two modes: Light & Dark. Inside the archive you will find multiple example pages on how to use all components. And, of course, every element is documented.

<br />

## How to use it

<br />

> **Install the package** via `PIP` 

```bash
$ pip install git+https://github.com/app-generator/priv-django-admin-material2-pro.git
```

<br />

> Add `admin_material2_pro` application to the `INSTALLED_APPS` setting of your Django project `settings.py` file (note it should be before `django.contrib.admin`):

```python
    INSTALLED_APPS = (
        ...
        'admin_material2_pro.apps.AdminMaterial2ProConfig',
        'django.contrib.admin',
    )
```

<br />

> Add `LOGIN_REDIRECT_URL` and `EMAIL_BACKEND` of your Django project `settings.py` file:

```python
    LOGIN_REDIRECT_URL = '/'
    # EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
    EMAIL_BACKEND = 'django.core.mail.backends.console.EmailBackend'
```

<br />

> Add `admin_material2_pro` urls in your Django Project `urls.py` file

```python
    from django.urls import path, include

    urlpatterns = [
        ...
        path('', include('admin_material2_pro.urls')),
    ]
```

<br />

> **Collect static** if you are in `production environment`:

```bash
$ python manage.py collectstatic
```

<br />

> **Start the app**

```bash
$ # Set up the database
$ python manage.py makemigrations
$ python manage.py migrate
$
$ # Create the superuser
$ python manage.py createsuperuser
$
$ # Start the application (development mode)
$ python manage.py runserver # default port 8000
```

Access the `admin` section in the browser: `http://127.0.0.1:8000/`

<br />

## Screenshots

![Theme Material Dashboard PRO - Main (Dark-Mode active), crafted by AppSeed.](https://user-images.githubusercontent.com/51070104/209695422-7863697f-e6c5-4b08-b395-422074e399df.jpg)

<br />

> [Django Admin Material PRO](https://github.com/app-generator/django-admin-material-pro) - `Calender` Page

![Theme Material Dashboard PRO - Calender Page, crafted by AppSeed.](https://user-images.githubusercontent.com/51070104/209695529-f4cea8ee-68d9-4658-bb54-110ff530c8da.jpg)

<br />

> [Django Admin Material PRO](https://github.com/app-generator/django-admin-material-pro) - `Automotive` Page

![Theme Material Dashboard PRO - Automotive Page, crafted by AppSeed.](https://user-images.githubusercontent.com/51070104/209695692-e681b3c8-fca8-4ebf-8803-2795bcd8f7d1.jpg)

<br />

---
**[Django Admin Material2 PRO](https://appseed.us/product/material-dashboard2-pro/django/)** - Modern Admin Interface provided by **[AppSeed](https://appseed.us/)**
