# Awesome Django [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; [![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; [![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; [![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; [![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of Django packages, tools, libraries, guides, tutorials, boilerplates, and ecosystem resources — covering web development, APIs, admin customization, security, testing, deployment, DevOps, and modern Django practices.

## Contents

- [Official Resources](#official-resources)
- [Starter Templates & Boilerplates](#starter-templates--boilerplates)
- [Admin Enhancements](#admin-enhancements)
- [Authentication & Authorization](#authentication--authorization)
- [APIs & REST](#apis--rest)
- [GraphQL](#graphql)
- [Databases & ORM](#databases--orm)
- [Caching & Performance](#caching--performance)
- [Security](#security)
- [Testing](#testing)
- [Async & Real-Time](#async--real-time)
- [Deployment & DevOps](#deployment--devops)
- [Developer Tools](#developer-tools)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [Django Project](https://www.djangoproject.com/) – Official site.
- [Django Documentation](https://docs.djangoproject.com/) – Comprehensive official docs.
- [Django GitHub](https://github.com/django/django)
- [Django Packages](https://djangopackages.org/) – Directory of Django extensions.

## Starter Templates & Boilerplates

- [Cookiecutter Django](https://github.com/cookiecutter/cookiecutter-django) – Full-featured production-ready Django project template.
- [Django Starter Template](https://github.com/wsvincent/django-starter-template)
- [Django REST Boilerplate](https://github.com/encode/django-rest-framework) – DRF-based starter setups.

## Admin Enhancements

- [django-grappelli](https://github.com/sehmaschine/django-grappelli) – A modern UI for Django Admin.
- [django-jet](https://github.com/geex-arts/django-jet) – Admin dashboard interface.
- [django-admin-interface](https://github.com/fabiocaccamo/django-admin-interface) – Customizable admin theme.
- [django-import-export](https://github.com/django-import-export/django-import-export) – CSV/Excel import & export for admin.

## Authentication & Authorization

- [django-allauth](https://github.com/pennersr/django-allauth) – Authentication with social login.
- [django-rest-auth](https://github.com/iMerica/dj-rest-auth) – Authentication for DRF.
- [django-guardian](https://github.com/django-guardian/django-guardian) – Per-object permissions.
- [django-axes](https://github.com/jazzband/django-axes) – Brute-force protection.

## APIs & REST

- [Django REST Framework (DRF)](https://github.com/encode/django-rest-framework) – Most popular toolkit for building APIs.
- [DRF SimpleJWT](https://github.com/jazzband/djangorestframework-simplejwt) – JWT authentication for DRF.
- [DRF Spectacular](https://github.com/tfranzel/drf-spectacular) – OpenAPI 3 schema generator.
- [DRF CamelCase](https://github.com/vbabiy/djangorestframework-camel-case) – CamelCase formatting for APIs.

## GraphQL

- [Graphene-Django](https://github.com/graphql-python/graphene-django) – GraphQL integration for Django.
- [Strawberry](https://github.com/strawberry-graphql/strawberry) – Pythonic GraphQL library with Django support.
- [Ariadne](https://github.com/mirumee/ariadne) – Schema-first GraphQL implementation for Django.

## Databases & ORM

- [Django ORM](https://docs.djangoproject.com/en/stable/topics/db/models/) – Built-in ORM.
- [Django Extensions](https://github.com/django-extensions/django-extensions) – Additional management commands & utilities.
- [django-filter](https://github.com/carltongibson/django-filter) – Advanced filtering for querysets.
- [django-redis](https://github.com/jazzband/django-redis) – Redis cache & session backend.
  
## Caching & Performance

- [django-cachalot](https://github.com/noripyt/django-cachalot) – Cache ORM queries automatically.
- [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) – Performance debugging panel.
- [django-silk](https://github.com/jazzband/django-silk) – Profiling & performance analysis.

## Security

- [django-secure](https://github.com/django/django/tree/main/django/middleware/security.py) – Built-in security middleware.
- [django-axes](https://github.com/jazzband/django-axes) – Login attempt monitoring.
- [django-two-factor-auth](https://github.com/Bouke/django-two-factor-auth) – 2FA for Django apps.
- [django-csp](https://github.com/mozilla/django-csp) – Content Security Policy middleware.

## Testing

- [pytest-django](https://github.com/pytest-dev/pytest-django) – Use pytest with Django.
- [factory_boy](https://github.com/FactoryBoy/factory_boy) – Fixtures replacement using factories.
- [model-bakery](https://github.com/model-bakers/model_bakery) – Quick model instances for tests.
- [tox](https://github.com/tox-dev/tox) – Test automation framework.

## Async & Real-Time

- [Django Channels](https://github.com/django/channels) – WebSockets & async support.
- [Daphne](https://github.com/django/daphne) – ASGI server for Django.
- [Starlette + Django Hybrid Setups](https://www.starlette.io/) – Combining async frameworks with Django.

## Deployment & DevOps

- **Hosting**
  - [Heroku](https://devcenter.heroku.com/categories/django-support)
  - [Railway](https://railway.app/)
  - [Render](https://render.com/)
  - [DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform/)

- **Server Environments**
  - [Gunicorn](https://github.com/benoitc/gunicorn) – WSGI HTTP server.
  - [uWSGI](https://github.com/unbit/uwsgi) – Application server for Django.
  - [Nginx](https://www.nginx.com/) – Reverse proxy & static file serving.

- **Containers & CI/CD**
  - [Docker Django Example](https://docs.docker.com/samples/django/)
  - [GitHub Actions for Django](https://github.com/marketplace/actions/django-ci)
  - [Poetry + Django Setups](https://python-poetry.org/)

## Developer Tools

- [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar)
- [django-extensions](https://github.com/django-extensions/django-extensions)
- [Black](https://github.com/psf/black) – Code formatter for Python.
- [Pylint](https://pylint.pycqa.org/)
- [mypy](https://github.com/python/mypy) – Static typing for Python + Django.

## Learning Resources

- [Django Documentation](https://docs.djangoproject.com/)
- [Django Girls Tutorial](https://tutorial.djangogirls.org/)
- [RealPython Django Tutorials](https://realpython.com/tutorials/django/)
- [Try Django (YouTube)](https://www.youtube.com/results?search_query=try+django)
- [Mozilla Django Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django)

## Related Awesome Lists

- [Awesome Python](https://github.com/awesomelistsio/awesome-python)
- [Awesome Web Development](https://github.com/awesomelistsio/awesome-web-development)
- [Awesome APIs](https://github.com/awesomelistsio/awesome-apis)
- [Awesome Backend Development](https://github.com/awesomelistsio/awesome-backend)

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
