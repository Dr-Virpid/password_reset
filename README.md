# password_reset
This files are used to overwrite the default templates supplied by django for password reset process
Django automatically checks for them and once it doesn't find them it uses 
default django templates
These files should be placed in the templates/registration folder 
And you can add styles and edit it the way you want 
To link your project to the views that uses it in your
url patterns add a path that points to "django.contrib.auth.urls"
i.e path('accounts/', include('django.contrib.auth.urls'))
For more information visit the official django documentation
Or visit [this tutorial](https://learndjango.com/tutorials/django-password-reset-tutorial)
