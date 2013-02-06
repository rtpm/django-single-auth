django-single-auth
==================

Restricts user logging to one session olny. If user logs in from another source the old session is deleted and so - user is logged out.

INSTALL:
Put the UserRestrictMiddleware class in your settings.py MIDDLEWARE_CLASSES after Sessions Middleware.

LICENSE:
Do whatever you want with this code.
