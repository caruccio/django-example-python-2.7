django-example-python-2.7
=========================

Getup Cloud OpenShift django-1.5 quickstart. Static files are served by nginx.

Create your app:

```
$ rhc app create django python-2.7
$ cd django/
```

Add this quickstart repo, pull and push:

```
$ git remote add upstream https://github.com/caruccio/django-example-python-2.7.git
$ git pull -s recursive -X theirs upstream master
$ git push
```

Point your browser to http://django-$namespace.getup.io

There is an initial django app named `openshift`. Your settings.py is `wsgi/openshift/openshift/settings.py`.
