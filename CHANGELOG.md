CHANGELOG
=========


0.4.9 (2019-03-19)
------------------

* pin 'django-select2' to 5.11.1 and 'django-taggit' to 0.24.0
* update code for django-select2


0.4.8 (2019-03-18)
------------------

* add for djangocms 3.2(rename cms_app.py, menu.py)


0.4.7 (2019-03-17)
------------------

* add support for django 1.7
* moved migrations to 'south_migrations' folder django<1.7
* make one native migration for django>=1.7
* fix 'get_query_set' method
* add fields = '__all__' for PostForm