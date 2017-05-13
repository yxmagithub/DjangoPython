just unzip the mygallery.zip into your local location

--------------
How to Run
--------------
django.get_version()  -> 1.4 


---------------
settings.py
---------------
You need to modify the MEDIA_ROOT，MEDIA_ROOT is the image uploaded location
you also have to specify the MEDIA_URL，it is URL access address
TEMPLAT_DIRS need to point to your templates address.

MEDIA_ROOT = '/home/freetstar/workspace/py/django/gallery/media/'
MEDIA_URL = 'media/'
TEMPLATE_DIRS = (
    "/home/freetstar/workspace/py/django/gallery/templates",
)
INSTALLED_APPS = (
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.sites',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'items',
     'django.contrib.admin',
    # 'django.contrib.admindocs',
)


------------------
urls.py
------------------

