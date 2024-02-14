# Awesome Django Scale

> A curated list of awesome things related to building with Django "at scale".

<br>

<div align="center">
  <img alt="Django Logo." src="./assets/awesome-django-scale.png">
</div>

<br>

## Contents

TODO: Sort by topic.

TODO: Specify Django version.

- [Books](#books)
- [Repositories](#repositories)
- [Articles and blogs](#articles-and-blogs)
- [Audio](#audio)
- [Video](#video)

## Books

- [Building Multi Tenant Applications with Django](https://books.agiliq.com/projects/django-multi-tenant/en/latest/)
- [The Temple of Django Database Performance](https://spellbookpress.com/books/temple-of-django-database-performance/)
- [Boost Your Django DX](https://adamchainz.gumroad.com/l/byddx)
  - DX is crucial for large projects.

## Repositories

- [Django Cacheback](https://django-cacheback.readthedocs.io/en/latest/): Cacheback is an extensible caching library that refreshes stale cache items asynchronously using a Celery or rq task (utilizing django-rq). The key idea being that it’s better to serve a stale item (and populate the cache asynchronously) than block the response process in order to populate the cache synchronously.
- [django-bulk-update](https://pypi.org/project/django-bulk-update/): Simple bulk update over Django ORM or with helper function.
- [django-bulk-load](https://pypi.org/project/django-bulk-load/): Load large batches of Django models into the DB using the Postgres COPY command. This library is a more performant alternative to bulk_create and bulk_update in Django.
- [django-tenants](https://github.com/django-tenants/django-tenants): This application enables django powered websites to have multiple tenants via PostgreSQL schemas. A vital feature for every Software-as-a-Service (SaaS) website.

## Articles and blogs

- [Django - Documentation: Performance and optimization](https://docs.djangoproject.com/en/5.0/topics/performance/)
- [Reining in the thundering herd ⛈ Getting to 80% CPU utilization with Django](https://blog.clubhouse.com/reining-in-the-thundering-herd-with-django-and-gunicorn/)
- [A Guide to Using pgBouncer for PostgreSQL](https://severalnines.com/blog/guide-using-pgbouncer/)
- [Scaling Django for millions of users](https://medium.com/@cjgiridhar/scaling-django-for-millions-of-users-7658113e720)
- [Optimize the Django ORM](https://alldjango.com/articles/optimize-the-django-orm)
- [Efficient bulk deletions in Django](https://til.simonwillison.net/django/efficient-bulk-deletions-in-django)
- [Scaling Django with Postgres read replicas](https://andrewbrookins.com/python/scaling-django-with-postgres-read-replicas/)

## Audio

- [Django @Instagram - Carl Meyer | Django Chat](https://djangochat.com/episodes/django-instagram-carl-meyer/)

## Video

- [Carl Meyer about Django @ Instagram at Django: Under The Hood 2016](https://www.youtube.com/watch?v=lx5WQjXLlq8)
- [DjangoCon Europe 2023 | Squeezing Django performance for 14.9 million users on WhatsApp](https://www.youtube.com/watch?v=A_bkbAv9TQs)
- [Talk: A thousand Djangoes within (or Django multi-tenant) - Lorenzo Peña](https://www.youtube.com/watch?v=pmBDoC-d9yw)
