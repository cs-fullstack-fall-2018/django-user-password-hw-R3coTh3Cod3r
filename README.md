# django-user_password-hw


Go over this documentation and list the default urls created for password management: https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Authentication.

Write your answer below:
Add Django site authentication urls (for login, logout, password management)
urlpatterns += [
    path('accounts/', include('django.contrib.auth.urls')),
]
