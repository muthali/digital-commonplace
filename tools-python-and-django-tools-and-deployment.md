# Python and Django Tools and Deployment

<!--
Blog Posts
https://www.vinta.com.br/blog/2021/testing-the-diff/ | Testing the diff - Vinta Blog
https://www.revsys.com/tidbits/tips-using-djangos-manytomanyfield/ | Tips for Using Django's ManyToManyField
-->

<!--
## Browser, Extensions, Bindings

Intel Python
https://software.intel.com/content/www/us/en/develop/tools/oneapi/components/distribution-for-python.html

Python Launcher Windows
https://github.com/brettcannon/python-launcher/releases/tag/v0.16.0 | Release v0.16.0 · brettcannon/python-launcher

https://github.com/pypa/manylinux
https://github.com/pypa/python-manylinux-demo

Cuda Python
https://developer.nvidia.com/cuda-toolkit

Python Browser
https://brython.info/
https://wxpython.org/ | Welcome to wxPython! | wxPython
https://github.com/pyodide/pyodide

PyOxidizer
A tool for roducing binaries that embed Python
https://github.com/indygreg/PyOxidizer

Python- Rust Bindings
https://github.com/PyO3/pyo3 | PyO3/pyo3: Rust bindings for the Python interpreter

C-Extensions for Python
https://cython.org/

Assembly Extensions
https://tonybaloney.github.io/posts/extending-python-with-assembly.html | Writing Python Extensions in Assembly

Python C API
https://pythoncapi.readthedocs.io/runtime.html
https://github.com/Quansight-Labs/python-api-inspect/blob/master/inspect_api/inspect.py | python-api-inspect/inspect.py at master · Quansight-Labs/python-api-inspect

https://docs.python.org/3/c-api/stable.html | Stable Application Binary Interface — Python 3.9.5 documentation

C++ and Python
https://github.com/boostorg/python | boostorg/python: Boost.org python module
-->


<!--
## Tool Choices

https://snarky.ca/thoughts-on-a-tooling-workflow/
https://twitter.com/brettsky/status/1260782564597366785

https://twitter.com/froidotdev/status/1248661469920714753

https://mobile.twitter.com/carltongibson/status/1243893076407603200 | Carlton Gibson 🇪🇺 on Twitter: "@zooba Clean My Mac is good. (Not sure about any particular malware but...)" / Twitter

Simon- Tools
https://twitter.com/simonw/status/1222726628314210311 | Simon Willison on Twitter: "Woohoo! Got continuous deployment of my new Django app working in GitLab CI, which builds a Docker image, runs tests in it, pushes it to the GitLab Container Registry then uses SSH to tell my server to pull the latest image and start serving it via Traefik!" / Twitter
https://simonwillison.net/2020/Feb/11/cheating-at-unit-tests-pytest-black/
This is a good starting point for getting Python, Django, Postgres running as a service, pytest, black, and pip caching rolling with GitHub Actions.
https://twitter.com/simonw/status/1248628140445855745

https://github.com/cortesi/devd
https://twitter.com/webology/status/1192623306840723456 | 🍂 Jeff Triplett 🍂 on Twitter: "Until I finish my blog post (which is about 100 items behind other priorities in life right now), this gist + screenshot are of my modd, django, python, tailwindcss, black, and pytest setup that I re-use from project-to-project." / Twitter
https://twitter.com/webology/status/1234940864687939586 | ✨ Jeff Triplett ✨ on Twitter: "I'm a coin flip on using pytest-black locally right now. I like it a lot for CI to avoid having to have an extra step, but it seems to step on my toes testing locally every so often. That said, I don't want two pytest.ini configs." / Twitter
https://mobile.twitter.com/webology/status/1195163668440334337

https://mobile.twitter.com/brettsky/status/1223731773147766784
https://twitter.com/gvanrossum/status/1227126706089021440
https://twitter.com/mariatta/status/1227286873413799936
https://twitter.com/jonasrk/status/1227028183469449216
https://twitter.com/WillingCarol/status/1227331652046770176
https://twitter.com/jacobian/status/1150072802801848320 | jacobian on Twitter: "This is my standard setup too. It's lovely, probably prevents half or more of the silly mistakes I'm prone to making.… https://t.co/ADRHdOq6A3"
https://twitter.com/hawkieowl/status/1150038262540431361 | -mtune=hawk -march=owl on Twitter: "But, anyway. The Ideal Python Development environment for me uses attrs in the code, black and isort to autoformat, flake8/pyflakes to verify, and tox and @nedbat 's Coverage to test. And pytest, if you don't have a particular affinity for xUnit like me :P"
-->

<!--
Feature Flags
https://github.com/cfpb/wagtail-flags | GitHub - cfpb/wagtail-flags: Feature flags for Wagtail sites
https://github.com/cfpb/django-flags/ | cfpb/django-flags: Feature flags for Django projects

https://bullet-train.io/ | Bullet Train - Feature Flags, Feature Toggles and Remote Config - Ship features with confidence
https://github.com/search?q=django+feature+flags | Search · django feature flags
https://github.com/django-waffle/django-waffle | django-waffle/django-waffle: A feature flipper for Django
https://github.com/disqus/gargoyle | disqus/gargoyle: Feature switches in Django
-->


<!--
## Testing and Stuff

https://ehmatthes.com/blog/messy_python_project/ | Cleaning up a messy, exploratory Python project - ehmatthes.com


Gidgethub
https://mobile.twitter.com/mariatta/status/1251733060812369920

https://github.com/Mariatta/requirements_atoz
https://github.com/Mariatta/cookiecutter_sprint_guide
https://github.com/Mariatta/pep_cookiecutter
https://github.com/hbristow/cookiecutter-cpp/blob/master/.travis.yml
https://github.com/jambonsw/cookiecutter-static-site

cross linter - Google Search

https://www.openssl.org/ | /index.html

https://launchpad.net/ubuntu | Ubuntu in Launchpad

https://www.pypy.org/ | PyPy
-->


<!--
Popular Python Tools

https://github.com/asottile/all-repos | asottile/all-repos: Clone all your repositories and apply sweeping changes.	
https://adamj.eu/tech/2020/04/02/maintaining-multiple-python-projects-with-myrepos/ | Maintaining Multiple Python Projects With myrepos - Adam Johnson

Python Docker
https://twitter.com/brettsky/status/1146835613628293120 | Twitter
https://github.com/microsoft/vscode-dev-containers/blob/master/containers/python-3/.devcontainer/Dockerfile

Recommended by Jeff
https://github.com/direnv
https://direnv.net/ | direnv – unclutter your .profile | direnv

https://pypi.org/project/python-decouple/

pip-tools
https://twitter.com/webology/status/1324134889172701190 | Jeff "voted 🗳 and wears a mask 😷 " Triplett on Twitter: "@epicserve Pip-tools is solid and you should use it with pip. You may want to try out poetry to see if it works with your workflow." / Twitter
https://twitter.com/jonafato/status/1283429696471027713 | Jon Banafato on Twitter: "Listen to Jeff. pip-tools is great." / Twitter
https://lincolnloop.com/blog/python-dependency-locking-pip-tools/ | Python Dependency Locking with pip-tools | Lincoln Loop

https://dateutil.readthedocs.io/en/stable/ | dateutil - powerful extensions to datetime — dateutil 2.8.1 documentation

https://github.com/pganssle?tab=repositories | pganssle (Paul Ganssle) / Repositories
https://blog.ganssle.io/articles/2019/11/utcnow.html | Stop using utcnow and utcfromtimestamp
https://blog.ganssle.io/articles/2018/02/aware-datetime-arithmetic.html | Semantics of timezone-aware datetime arithmetic

https://pyformat.info/ | PyFormat: Using % and .format() for great good!

https://twitter.com/simonw/status/1302996263550377985 | Simon Willison on Twitter: "This is brilliant. I just ran "curlylint datasette/templates" and it spotted two closing &lt;/a&gt; tags that were not matched by an opening tag. https://t.co/rnfsnmPSoO" / Twitter

https://pypi.org/project/pypi-simple/ | pypi-simple · PyPI

https://pypi.org/project/mousebender/ | mousebender · PyPI

http://pluggy.readthedocs.io/en/latest/ | pluggy — pluggy 0.6.1.dev73+g76232fa documentation
https://pypi.org/project/pluggy/ | pluggy · PyPI

Python
Django self-update
https://github.com/pyupio/safety | pyupio/safety: Safety checks your installed dependencies for known security vulnerabilities
https://pyup.io/safety/

https://pypi.org/project/entry-point-inspector/ | entry-point-inspector · PyPI

https://twitter.com/KatiMichel/status/1302455369353039873 | Katherine Michel on Twitter: "The tutorial threw something at me that I can't remember ever having heard of before... `python https://t.co/jyO6G4g0ui shell_plus` autoloads the settings and the model classes." / Twitter
https://twitter.com/aliasoltaani/status/1302475667867676673 | Sol on Twitter: "@KatiMichel Check this, it's awesome! pip install jupyter python https://t.co/HI9CpiHRiU shell_plus --notebook" / Twitter
-->


## Awesome Python and Django

Awesome Python
* [Awesome Python GitHub](https://github.com/vinta/awesome-python) and [Awesome Python](http://awesome-python.com)
* [Awesome Pythonidae GitHub](https://github.com/svaksha/pythonidae)  
* [Awesome Pycrumbs GitHub](https://github.com/kirang89/pycrumbs)  

Awesome Django
* [Awesome Django](https://github.com/wsvincent/awesome-django)
* [Awesome Django GitLab](https://gitlab.com/rosarior/awesome-django) and [Awesome Django GitHub (Deprecated)](https://github.com/rosarior/awesome-django) 
* [Awesome Django Admin GitHub](https://github.com/originalankur/awesome-django-admin)
* [Awesome Django Rest Framework GitHub](https://github.com/nioperas06/awesome-django-rest-framework)

## Python and Django

Python
* [Python](https://www.python.org/)

Django GitHub
* [Django GitHub](https://github.com/django/django)

<!--
https://plone.org/
-->

## General Python and Django Links- Getting Started

Python Official Tutorial
* [Python Official Tutorial](https://docs.python.org/3/tutorial/) 

Django Tutorials (Official, Mozilla Developer Network and SIBTC) 
* [Django Official Tutorial](https://docs.djangoproject.com/en/2.0/intro/tutorial01)

Django Install
* [Django Install](https://docs.djangoproject.com/en/dev/topics/install)

## Python and Django Links- Style

Python Style
* [PEP 0008 Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008) and [PEP 0008 Style Guide for Python Code .txt](https://hg.python.org/peps/file/tip/pep-0008.txt)
* [PEP 0257 Doc String Conventions](https://www.python.org/dev/peps/pep-0257)

Django Coding Style Guide
* [Django Coding Style Guide](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style)

Django JavaScript Style Guide
* [Django JavaScript Style Guide](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/javascript)

## Design Choices

Django Architecture and Scaling
* [Shared-Nothing Architecture Wikipedia](https://en.wikipedia.org/wiki/Shared-nothing_architecture)
* [Does Django Scale?](https://docs.djangoproject.com/en/dev/faq/general/#does-django-scale)
* [Django Design Philosophies](https://docs.djangoproject.com/en/dev/misc/design-philosophies)

## General Python and Django Links

Django Views
* [Class-Based Views](https://docs.djangoproject.com/en/dev/topics/class-based-views/)

Django ORM
* [Queries](https://docs.djangoproject.com/en/dev/topics/db/queries)

Django Request/Response

<!--
https://docs.djangoproject.com/en/2.2/_modules/django/http/request/ | django.http.request | Django documentation | Django

https://docs.djangoproject.com/en/dev/_modules/django/http/request/#HttpRequest
https://docs.djangoproject.com/en/dev/ref/request-response/#jsonresponse-objects

https://docs.djangoproject.com/en/2.1/ref/request-response/#django.http.HttpRequest.GET
https://docs.djangoproject.com/en/1.11/ref/request-response/#django.http.HttpRequest.POST
https://docs.djangoproject.com/en/1.11/ref/request-response/#django.http.QueryDict


https://docs.djangoproject.com/en/3.1/ref/request-response/
https://docs.djangoproject.com/en/3.1/ref/request-response/#module-django.http
https://docs.djangoproject.com/en/3.1/ref/request-response/#httprequest-objects
https://docs.djangoproject.com/en/3.1/ref/request-response/#httpresponse-objects
https://docs.djangoproject.com/en/3.1/ref/request-response/#jsonresponse-objects
-->

## Django Source

<!--
https://github.com/django/django/blob/master/django/core/handlers/base.py#L71 | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/core/handlers/base.py#L85 | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/urls/resolvers.py#L66 | django/resolvers.py at master · django/django
https://github.com/django/django/blob/master/django/template/context.py | django/context.py at master · django/django
https://github.com/django/django/blob/master/django/template/response.py | django/response.py at master · django/django
https://github.com/django/django/blob/master/django/http/__init__.py | django/__init__.py at master · django/django
https://github.com/django/django/blob/master/django/core/files/uploadhandler.py | django/uploadhandler.py at master · django/django

https://www.youtube.com/watch?v=tkwZ1jG3XgA | James Bennett - Django in Depth - PyCon 2015 - YouTube	
https://twitter.com/ubernostrum/status/1115023968925130752 | James Bennett on Twitter: "Let me know if you have questions. It's old/out-of-date, and tried to cover too much stuff (which is why I switched to doing an ORM-focused tutorial last year).… https://t.co/btm7lzK7rI"

Django Source Code
https://github.com/django/django/blob/master/django/__init__.py	
https://github.com/django/django/tree/master/django/apps	
https://github.com/django/django/blob/master/django/apps/config.py	
https://github.com/django/django/blob/master/django/apps/registry.py
https://github.com/django/django/blob/master/django/conf/__init__.py | django/__init__.py at master · django/django
https://github.com/django/django/blob/master/django/urls/conf.py	
https://github.com/django/django/blob/master/django/urls/resolvers.py
https://github.com/django/django/blob/master/django/middleware/common.py

https://github.com/django/django/blob/master/django/core/handlers/wsgi.py | django/wsgi.py at master · django/django
https://github.com/django/django/blob/master/django/http
https://github.com/django/django/blob/master/django/http/request.py | django/request.py at master · django/django	
https://github.com/django/django/blob/master/django/http/response.py	

https://github.com/django/django/blob/master/django/views/generic/__init__.py | django/__init__.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/base.py | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/base.py#L83 | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/detail.py | django/detail.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/list.py | django/list.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/list.py#L113	
	
https://github.com/django/django/blob/master/django/shortcuts.py
https://github.com/django/django/blob/master/django/core/exceptions.py	
	
https://github.com/django/django/tree/master/django/db/backends | django/django/db/backends at master · django/django	
https://github.com/django/django/blob/master/django/db/models/__init__.py 	
https://github.com/django/django/blob/master/django/db/models/query.py	
https://github.com/django/django/blob/master/django/db/models/query.py#L337	
https://github.com/django/django/blob/master/django/contrib/auth/base_user.py | 	
https://github.com/django/django/blob/master/django/db/models/lookups.py
-->

## Django Serialization

Python- Django- Rest Framework (Serialization/Deserialization)
* [Django Rest Framework: Tutorial 1: Serialization](http://www.django-rest-framework.org/tutorial/1-serialization)
* [Serializing Django objects](https://docs.djangoproject.com/en/dev/topics/serialization)
* [JSON](https://docs.djangoproject.com/en/dev/topics/serialization/#serialization-formats-json)

## Django Internationalization and Localization, Translation

* [Django i18n Forum](https://groups.google.com/forum/#!forum/django-i18n)  
* [Python Gettext Multilingual Internationalization Services](https://docs.python.org/2/library/gettext.html)  
* [Django Local Flavor](https://docs.djangoproject.com/en/dev/topics/localflavor)  
* [Django Local Flavor Read the Docs](https://django-localflavor.readthedocs.org/en/latest)  
* [Django Local Flavor GitHub](https://github.com/django/django-localflavor)  
* [Django Local Flavor PyPi](https://pypi.python.org/pypi/django-localflavor)  
* [Django Internationalization and Localization](https://docs.djangoproject.com/en/dev/topics/i18n)  
* [Django Internationalization and Localization, Translation](https://docs.djangoproject.com/en/dev/topics/i18n/translation) 

<!--
https://github.com/django/django-formtools
https://github.com/django/django-contrib-comments
-->

## Python and Django Geo

GeoDjango
* [GeoDjango](http://geodjango.org)  
* [GeoDjango Installation Postgresapp](https://docs.djangoproject.com/en/1.9/ref/contrib/gis/install/#postgresapp)

Python- Django- Rest Framework GIS
* [Django Rest Framework GIS API Guide Fields](http://www.django-rest-framework.org/api-guide/fields/#django-rest-framework-gis)  
* [Django Rest Framework GIS GitHub](https://github.com/djangonauts/django-rest-framework-gis)  
* [Django Rest Framework GIS PyPi](https://pypi.python.org/pypi/djangorestframework-gis)  
* [Django Rest Framework GIS Forum](https://groups.google.com/forum/#!forum/django-rest-framework-gis)  

PostGIS (Spatial Database Extender for PostgreSQL)
* [PostGIS](http://postgis.net)  
* [PostGIS Wikipedia](http://en.wikipedia.org/wiki/PostGIS)  
* [UbuntuGIS](https://wiki.ubuntu.com/UbuntuGIS)  
* [UbuntuGIS Wiki](http://trac.osgeo.org/ubuntugis/wiki)  
* [Heroku PostGIS Wiki](https://devcenter.heroku.com/articles/postgis)  

SpatiaLite (Spatial Database Extender for SQLite)
* [SpatiaLite](https://www.gaia-gis.it/fossil/libspatialite/index)  
* [SpatiaLite Downloads Page](http://www.gaia-gis.it/gaia-sins/libspatialite-sources)  
* [SpatiaLite Wikipedia](http://en.wikipedia.org/wiki/SpatiaLite)  

<!--
GIS

Important
https://simonwillison.net/2021/May/3/adding-geodjango-to-an-existing-django-project/ | Adding GeoDjango to an existing Django project

https://realpython.com/location-based-app-with-geodjango-tutorial/ | Make a Location-Based Web App With Django and GeoDjango – Real Python
https://en.wikipedia.org/wiki/Spatial_database | Spatial database - Wikipedia

https://postgis.net/docs/manual-3.0/
https://postgis.net/docs/manual-3.0/ch06.html
https://www.gaia-gis.it/fossil/libspatialite/index

GIS
https://docs.djangoproject.com/en/3.2/ref/contrib/gis/ | GeoDjango | Django documentation | Django
https://docs.djangoproject.com/en/3.2/ref/contrib/gis/tutorial/ | GeoDjango Tutorial | Django documentation | Django
-->

## Django Rest Framework

Python- Django- Rest Framework (Including Authentication and Generic Views)
* [Django Rest Framework](http://www.django-rest-framework.org) and [Django Rest Framework GitHub](https://github.com/encode/django-rest-framework) 
* [Django Rest Framework Generic Views](http://www.django-rest-framework.org/api-guide/generic-views)  
* [Django Rest Framework Authentication](http://www.django-rest-framework.org/api-guide/authentication)  

<!--
DRF
https://twitter.com/nextdayvideo/status/1363639281726623745 | Next Day Video on Twitter: "#pycascades What You Should Know About Django REST Framework - Lacey Williams Henschel https://t.co/E9pg9roNoL" / Twitter
https://speakerdeck.com/williln/what-you-should-know-about-django-rest-framework | What You Should Know About Django REST Framework - Speaker Deck
https://www.laceyhenschel.com/blog/2021/2/23/what-you-should-know-about-drf-part-2-customizing-built-in-methods | What You Should Know About DRF, Part 2: Customizing built-in methods — Lacey Williams Henschel
https://www.laceyhenschel.com/blog/2021/2/23/what-you-should-know-about-django-rest-framework-part-3-adding-custom-endpoints | What You Should Know About DRF, Part 3: Adding custom endpoints — Lacey Williams Henschel

https://www.django-rest-framework.org/tutorial/3-class-based-views/ | 3 - Class based views - Django REST framework
https://www.django-rest-framework.org/api-guide/serializers/ | Serializers - Django REST framework
https://www.django-rest-framework.org/api-guide/viewsets/#modelviewset
https://www.django-rest-framework.org/api-guide/serializers/#modelserializer

https://github.com/encode/django-rest-framework/

https://github.com/encode/django-rest-framework/issues
https://github.com/encode/django-rest-framework/projects

https://github.com/encode/rest-framework-tutorial | encode/rest-framework-tutorial
http://www.tomchristie.com/rest-framework-2-docs/api-guide
https://www.django-rest-framework.org/tutorial/1-serialization/ | 1 - Serialization - Django REST framework

https://github.com/carltongibson/rest-framework-tutorial | carltongibson/rest-framework-tutorial
https://github.com/carltongibson/rest-framework-tutorial/blob/master/docs/azure/1-vscode.md | rest-framework-tutorial/1-vscode.md at master · carltongibson/rest-framework-tutorial
https://github.com/carltongibson/rest-framework-tutorial/blob/master/docs/azure/2-appservice.md | rest-framework-tutorial/2-appservice.md at master · carltongibson/rest-framework-tutorial

https://twitter.com/carltongibson/status/1072951282502172678 | Carlton Gibson on Twitter: "Been having fun with @code for about a year and a half. I got together with @nnja to talk about using it with Django and DRF…… https://t.co/XmFcENotrc"
https://www.youtube.com/watch?list=PLlrxD0HtieHjQMK-jWHRy3aHGLhbAFqbR&time_continue=10&v=0Bk0dw2Ktbg | Python on Azure: Part 1—Building Django apps with Visual Studio Code | Azure Friday - YouTube
https://www.youtube.com/watch?list=PLlrxD0HtieHjQMK-jWHRy3aHGLhbAFqbR&v=FHJvsvbD_cQ | Python on Azure: Part 2—Deploying Django services to Azure Web Apps | Azure Friday - YouTube
-->


<!--
## DRF

DRF Example
* https://github.com/simplworld/simpl-games-api/blob/master/simpl/webhook/serializers.py

https://www.django-rest-framework.org/community/3.10-announcement/ | 3.10 Announcement - Django REST framework

DRF Resources
* https://realpython.com/django-rest-framework-quick-start/ | Django Rest Framework – An Introduction – Real Python
* https://www.django-rest-framework.org/tutorial/quickstart/ | Quickstart - Django REST framework
* https://www.django-rest-framework.org/#example | Home - Django REST framework

https://www.django-rest-framework.org/api-guide/testing/ | Testing - Django REST framework

https://www.django-rest-framework.org/api-guide/status-codes/ | Status codes - Django REST framework

Valentino
https://www.valentinog.com/blog/testing-django/ | Django Testing Cheat Sheet
https://www.valentinog.com/blog/drf/ | Tutorial: Django REST with React (and a sprinkle of testing)
https://github.com/valentinogagliardi/django-rest-react-pycon
 -->


## Django Rest Framework- Extras

* [Django Rest Framework Swagger](https://github.com/marcgibbons/django-rest-swagger) 

Python- Django- Alternative Rest Framework
* [django-tastypie Read the Docs](http://django-tastypie.readthedocs.org)

<!--
https://swagger.io/docs/

https://github.com/caktus/drf-sample | caktus/drf-sample: Django REST Framework Sample
https://github.com/vintasoftware/drf-rw-serializers/

https://wsvincent.com/django-rest-framework-tutorial/ | Django Rest Framework - Blog API - William S. Vincent
https://github.com/wsvincent/rest-framework-tutorial
-->

## Django Classy

Django Classy
* [Classy Class-Based Views](http://ccbv.co.uk)
* [Classy Django Forms](http://cdf.9vo.lt) and [Classy Django Forms GitHub](https://github.com/ana-balica/classy-django-forms)
* [Classy Django REST Framework](http://cdrf.co) and [Classy Django REST Framework GitHub](https://github.com/vintasoftware/classy-django-rest-framework)

## Django Third Party Tools

<!--
https://github.com/jazzband/django-debug-toolbar


HTMX + DJango
https://twitter.com/htmx_org/status/1432498119464259585 | htmx.org on Twitter: "what's really satisfying about this is how htmx + django allows developers to a ditch complicated server side tool in favor of small, properly factored snippets of HTML templates simpler, more dynamic *and* more flexible what's not to like? 🍻 @justdjangocode" / Twitter

Django Tool
https://github.com/rtts/djhtml | rtts/djhtml: Django/Jinja template indenter

django_deprecate_fields
https://twitter.com/lalongueduree/status/1418518067294900226 | Jeremy Gibson on Twitter: "If you haven't read a piece yet by my colleague @danpoirier, you really should especially if you develop with #Django. This one... django_deprecate_fields... 🤯 Truly a "I can't believe I haven't been using this before" moment. https://t.co/ArgrMXl8CK" / Twitter
https://twitter.com/CaktusGroup/status/1418316667776606215 | Caktus Group on Twitter: "By using django-add-default-value and django-deprecate-fields to simplify the migration and deployment process, you will eliminate a common #Django #deployment headache. This has been a challenge for a while now. https://t.co/Fi0j51BmmX" / Twitter

django-lifecycle
https://github.com/rsinger86/django-lifecycle
https://twitter.com/webology/status/1291058206056251393 | Jeff says, "wear a mask" 😷 on Twitter: "@andrewgodwin @carltongibson If you want to see something that's both different and lifted from Rails, check out https://t.co/nvQXTiFIkw I can't unsee them after using them in a few projects." / Twitter
https://twitter.com/carltongibson/status/1279334203457523713 | Carlton Gibson 🇪🇺 on Twitter: "Folks still using django-lifecycle? What are the thoughts Some Time Later?" / Twitter

django-allauth
https://github.com/pennersr/django-allauth | pennersr/django-allauth: Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party (social) account authentication.
https://pyphilly.org/know-thy-user-custom-user-models-django-allauth/
https://twitter.com/FlipperPA/status/1317214250193031168 | Tim A. on Twitter: "@pystar As promised, here's a blog post: https://t.co/M4I1ktg5P3" / Twitter

https://django-extensions.readthedocs.io/en/latest/shell_plus.html | shell_plus — django-extensions 3.0.8 documentation
https://github.com/django-extensions/django-extensions | django-extensions/django-extensions: This is a repository for collecting global custom management extensions for the Django Framework.


Django filter
https://github.com/carltongibson/django-filter | carltongibson/django-filter: A generic system for filtering Django QuerySets based on user selections
https://django-filter.readthedocs.io/en/
https://pypi.org/project/django-filter/ | django-filter · PyPI
https://pypi.org/project/djangorestframework-filters/ | djangorestframework-filters · PyPI
https://www.django-rest-framework.org/api-guide/filtering/ | Filtering - Django REST framework
https://github.com/philipn/django-rest-framework-filters | philipn/django-rest-framework-filters: Better filtering for Django REST Framework

Django Crispy Forms
http://django-crispy-forms.readthedocs.io/en/latest/ | Forms have never been this crispy — django-crispy-forms 1.0.0 documentation
https://pypi.org/project/django-crispy-forms/ | django-crispy-forms · PyPI
https://github.com/django-crispy-forms/django-crispy-forms | django-crispy-forms/django-crispy-forms: The best way to have DRY Django forms. The app provides a tag and filter that lets you quickly render forms in a div format while providing an enormous amount of capability to configure and control the rendered HTML.

https://pypi.org/project/django-countries/ | django-countries · PyPI
https://github.com/SmileyChris/django-countries#countryfield | SmileyChris/django-countries: A Django application that provides country choices for use with forms, flag icons static files, and a country field for models.


https://pypi.org/project/pep8/ | pep8 · PyPI

https://pypi.org/project/coverage/ | coverage · PyPI
https://devguide.python.org/coverage/ | 5. Increase Test Coverage — Python Developer's Guide

Formatting
https://pypi.org/project/black/ | black · PyPI
https://pypi.org/project/isort/ | isort · PyPI
https://github.com/PyCQA/isort | PyCQA/isort: A Python utility / library to sort imports.
https://twitter.com/webology/status/1393520619262730249 | Jeff Triplett 😷💉💉💯 on Twitter: "TIL: There are a couple of nice isort tips here that I didn't know were possible like add_imports and remove_imports which I will use Monday. 🤔" / Twitter
https://flake8.pycqa.org/en/latest/
https://launchpad.net/pyflakes/ | Pyflakes in Launchpad
https://pypi.org/project/flake8/ | flake8 · PyPI


Simon
https://twitter.com/simonw/status/1321612923442098177 | (26) Simon Willison on Twitter: "Just found out Jupyter is available via Homebrew: brew install jupyter I wonder if this could be a good recommended starting point for newcomers to Python? You can pip install packages for it in the right place directly in a cell using: %pip install httpx" / Twitter

https://ipython.org/ | Jupyter and the future of IPython — IPython

Model History
https://django-simple-history.readthedocs.io/en/latest/quick_start.html | Quick Start — django-simple-history 3.0.0.post23+ga63eec8 documentation

https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance

https://pyphilly.org/virtualenvwrapper-aliases-venv-users/ | virtualenvwrapper Aliases for venv Users - PyPhilly: Home of Tim Allen, aka FlipperPA

Attrs
https://pepy.tech/project/attrs | PePy - attrs Download Stats
-->

## Docs

<!--
Django YAML
https://django-yamlfield.readthedocs.io/en/latest/ | django-yamlfield
https://github.com/datadesk/django-yamlfield | datadesk/django-yamlfield: A Django database field for storing YAML data

Docs
https://docutils.sourceforge.io/rst.html | reStructuredText
https://pandoc.org/

Furo Theme
https://twitter.com/AdamChainz/status/1432678359276863494 | Adam Johnson on Twitter: "Just moved the Django-MySQL docs to @pradyunsg 's excellent Furo theme 😎 https://t.co/ippjR6VV4b" / Twitter
https://django-mysql.readthedocs.io/en/latest/ | Django-MySQL 4.0.0 documentation
-->


## Common Django Features

<!--
http://django-vanilla-views.org/ | Django Vanilla Views - Beautifully simple class based views
https://github.com/tomchristie/django-vanilla-views | tomchristie/django-vanilla-views: Beautifully simple class-based views.

http://www.discoversdk.com/blog/understanding-the-request-response-lifecycle-of-a-django-web-application | Understanding the request-response lifecycle of a Django web application | DiscoverSDK Blog

Django Request and Response Cycle
* [Django Request and Response Cycle](http://rnevius.github.io/django_request_response_cycle.png)
-->

## Django Performance, Optimization, Deployment, Architecture

<!--
https://djangobook.com/deploying-django/
-->

## Django Twelve Factor

<!--
https://12factor.net/config | The Twelve-Factor App

https://github.com/doismellburning/django12factor | doismellburning/django12factor: Making Django configuration more 12factor-y
-->


## Wagtail

Wagtail
* [Wagtail](https://wagtail.io/)

<!--
Django Wagtail
https://github.com/Jean-Zombie/cookiecutter-django-wagtail | Jean-Zombie/cookiecutter-django-wagtail: Cookiecutter Django + Wagtail

Wagtail
https://wagtail.io/blog
https://github.com/wagtail/wagtail/
https://wagtail.io/packages/ | Packages | Wagtail CMS
https://wagtail.io/blog/wagtail-packages/ | Wagtail Packages | Wagtail CMS
https://github.com/vsalvino/wagtail-tutorial | vsalvino/wagtail-tutorial: Build your first simple wagtail website!
https://github.com/coderedcorp/coderedcms | coderedcorp/coderedcms: A content management system for marketing websites based on Django and Wagtail.
-->

## Structuring Your Python Project

Kenneth Reitz- Sample Project Structure, Sample Module, and setup.py
* [Kenneth Reitz: Structuring Your Project](http://docs.python-guide.org/en/latest/writing/structure)
* [Sample Module for The Hitchhiker’s Guide to Python! GitHub](https://github.com/kennethreitz/samplemod) and [Sample Module Docs](https://github.com/kennethreitz/samplemod/tree/master/docs)
* [Repository Structure and Python](https://www.kennethreitz.org/essays/repository-structure-and-python)
* [A Human's Ultimate Guide to setup.py GitHub](https://github.com/kennethreitz/setup.py)

## Django Project Structure

Python- Django- Project Stucture
* [RevSys Recommended Django Project Layout](http://www.revsys.com/blog/2014/nov/21/recommended-django-project-layout)
* [SIBTC Starting a New Django 1.8 Project](http://simpleisbetterthancomplex.com/2015/11/30/starting-a-new-django-18-project.html)

## Python Non-Official Styleguides and Code Formatting

Style
* [Coding Conventions Wikipedia](https://en.wikipedia.org/wiki/Coding_conventions)
* [Programming Style Wikipedia](https://en.wikipedia.org/wiki/Programming_style)

Python- Kenneth Reitz Contributor's Guide and Style Guides
* [Kenneth Reitz: The Hitchhiker’s Guide to Python! Code Style](http://docs.python-guide.org/en/latest/writing/style)

Python- Style Guides
* [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)
* [Khan Academy Python Style Guide Python](https://github.com/Khan/style-guides/blob/master/style/python.md)
* [The Chromium Project Python Style Guide](https://www.chromium.org/chromium-os/python-style-guidelines)

<!--
https://docs.python-guide.org/#writing-great-python-code
-->

Python- PEP 8
* [Kenneth Reitz: PEP 8 — the Style Guide for Python](http://pep8.org) and [Kenneth Reitz: PEP 8 — the Style Guide for Python GitHub](https://github.com/kennethreitz/pep8.org)

## Choices

Vinta Django Apps Checklist	
* [Vinta Django Apps Checklist](https://devchecklists.com/django-apps-checklist)	

Vinta API Checklist	
* [Vinta API Checklist](https://devchecklists.com/python-api-checklist) and [Vinta API Checklist GitHub](https://github.com/vintasoftware/python-api-checklist)

<!--
https://devchecklists.com
https://devchecklists.com/django-production-launch/
https://devchecklists.com/vintas-high-quality-standards/

Check if you need a Django app or a regular Python package: Django apps need to be added to INSTALLED_APPS . Regular Python packages do not. Examples of regular Python packages:
-->

## Eldarion and Pinax

Package Tools
* [django-appconf Read the Docs](https://django-appconf.readthedocs.io) and [django-appconf PyPI](https://pypi.org/project/django-appconf)

<!--
https://github.com/django-compressor/django-appconf | django-compressor/django-appconf: An app to handle configuration defaults of packaged Django apps gracefully
-->

Continuous Integration and Delivery
* [CircleCI](https://circleci.com)

Coverage
* [Coverage Read the Docs](http://coverage.readthedocs.org) and [Coverage Bitbucket](https://bitbucket.org/ned/coveragepy)
* [Codecov](https://codecov.io)

Testing Tools
* [Tox Read the Docs](https://tox.readthedocs.org)
* [Tox Parallel Mode](https://tox.readthedocs.io/en/latest/example/basic.html#parallel-mode)
* [Detox GitHub (Archived)](https://github.com/tox-dev/detox) and [Detox PyPi](https://pypi.python.org/pypi/detox)

<!--
Tox GitHub Action
https://github.com/tox-dev/action | tox-dev/action: A Github Action to run tox environments within Github

https://docs.codecov.io/docs/python
https://codecov.io/#features | Codecov

"[Integration with coverage.py](https://docs.djangoproject.com/en/dev/topics/testing/advanced/#topics-testing-code-coverage)."
"[Running tests using tox](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/unit-tests/#running-tests-using-tox)"

https://github.com/marketplace?utf8=%E2%9C%93&query=tox | GitHub Marketplace · Tools to improve your workflow
https://tox.readthedocs.io/en/latest/example/basic.html#a-simple-tox-ini-default-environments | Basic usage — tox 3.14.6.dev2 documentation

https://github.com/codecov/example-python#testing-with-tox | codecov/example-python: Python coverage example
https://github.com/pallets/flask/blob/master/tox.ini
https://github.com/pganssle/tox-examples | pganssle/tox-examples

https://stackoverflow.com/questions/21991765/how-to-generate-coverage-from-setup-py | python - How to generate coverage from setup.py - Stack Overflow
https://github.com/codecov/example-python#how-to-generate-coverage-reports
"coverage.py is required to collect coverage metrics."
-->

tox Alternative (not used)
* [Nox](http://nox.thea.codes) and [Nox GitHub](https://github.com/theacodes/nox)

Import Sorting
* [isort](http://isort.readthedocs.io) and [isort GitHub](https://github.com/timothycrosley/isort)

Formatting
* [Flake8 GitHub](https://gitlab.com/pycqa/flake8) and [Flake8 Docs](http://flake8.pycqa.org)
* [doc8 GitHub](https://github.com/openstack/doc8)
* [pydocstyle GitHub](https://github.com/PyCQA/pydocstyle)
* [mccabe GitHub](https://github.com/PyCQA/mccabe)
* [Flake8 Quotes GitHub](https://github.com/zheller/flake8-quotes)

<!--
https://github.com/timothycrosley/isort/issues/694

?
https://pypi.org/project/pyflakes/
https://github.com/PyCQA/pyflakes
-->

Not used?
* [Factory Boy GitHub](https://github.com/FactoryBoy/factory_boy) and [Factory Boy PyPI](https://pypi.python.org/pypi/factory_boy)

Kubernetes
* [Kubernetes](https://kubernetes.io)

Webpack Versus Browserify
* [Vue](https://vuejs.org/)
* [Webpack](https://webpack.js.org)
* [Copy Webpack Plugin GitHub](https://github.com/webpack-contrib/copy-webpack-plugin)
* [Browserify](http://browserify.org)
* [Browsersync](https://www.browsersync.io/)

<!--
http://fontawesome.io/ | Font Awesome, the iconic font and CSS toolkit
https://fontawesome.com | Font Awesome 5 | Font Awesome

https://circleci.com/blog/setting-up-continuous-integration-with-github/ | GitHub Continuous Integration - GitHub CI | CircleCI

https://github.com/CircleCI-Public/circleci-cli | CircleCI-Public/circleci-cli: Use CircleCI from the command line
https://github.com/CircleCI-Public/circleci-demo-python-django | CircleCI-Public/circleci-demo-python-django: Example Django application running on CircleCI

https://circleci.com/docs/2.0/ | Welcome to CircleCI Documentation - CircleCI
https://circleci.com/docs/2.0/example-configs/ | Example Public Repos - CircleCI
https://circleci.com/docs/2.0/caching/ | Caching Dependencies - CircleCI
https://circleci.com/docs/2.0/env-vars/ | Using Environment Variables - CircleCI
https://circleci.com/docs/2.0/language-python/ | Configuring a Python Application on CircleCI - CircleCI
https://github.com/CircleCI-Public/circleci-demo-python-django | CircleCI-Public/circleci-demo-python-django: Example Django application running on CircleCI

https://coverage.readthedocs.io/en/coverage-5.0/config.html | Configuration files — Coverage.py 4.4.2 documentation


http://flake8.pycqa.org/en/3.1.1/user/ignoring-errors.html | Ignoring Errors with Flake8 — flake8 3.1.1 documentation

flake8 
noqa: E501
https://pypi.org/project/flake8-confusables/ | flake8-confusables · Warehouse (PyPI)
-->

### Package Tools and Testing

<!--
attrs, pre-commit, tox, nox, flake8, check-manifest, twine, isort, seed-isort-config, black, pytest-cov, codecov action, flake8-black

Not used- but could be?
* [attrs GitHub](https://github.com/python-attrs/attrs)
* [pytest-cov Read the Docs](https://pytest-cov.readthedocs.io)

https://github.com/codecov/codecov-action | codecov/codecov-action: GitHub Action that uploads coverage to Codecov

https://github.com/pytest-dev/pytest-cov | pytest-dev/pytest-cov: Coverage plugin for pytest.

Black and single quotes
https://github.com/peterjc/flake8-black | peterjc/flake8-black: flake8 plugin to run black for checking Python coding style
https://github.com/python/black/issues/118 | Single quotes option · Issue #118 · python/black
-->

### Code Formatting Tools

Code Formatting
* [Black GitHub](https://github.com/psf/black)
* [Black Online (Playground) GitHub](https://github.com/jpadilla/black-online)
* [Black Out GitHub](https://github.com/mariatta/black_out)
* [White GitHub](https://github.com/kennethreitz/white)
* [Google YAPF](https://github.com/google/yapf)

<!--
https://black.readthedocs.io/en/stable/installation_and_usage.html | Installation and usage — Black 19.10b1.dev0+g6bedb5c.d20191029 documentation

https://github.com/bots-for-humanity/black-out

https://black.now.sh/ | Black Playground
-->

## Third Party Load Balancing, Task Queue/Job Queue, Distributed Message Passing, Caching

* [NGINX](https://www.nginx.com/)
* [Celery](http://www.celeryproject.org) and [Celery GitHub](https://github.com/celery/celery)  
* [Celery and Django](http://docs.celeryproject.org/en/2.5/django/first-steps-with-django.html) 
* [RQ (Redis Queue)](http://python-rq.org/)
* [RabbitMQ](https://www.rabbitmq.com/)
* [Redis](https://redis.io/)
* [Memcached](https://memcached.org/)

<!--
https://en.wikipedia.org/wiki/MQTT | MQTT - Wikipedia

https://realpython.com/asynchronous-tasks-with-django-and-celery/ | Asynchronous Tasks With Django and Celery – Real Python
https://www.fullstackpython.com/task-queues.html
-->

## Azure

<!--
https://twitter.com/anthonypjshaw/status/1270205981616529408 | Anthony Shaw 🐍 on Twitter: "If you use @AzureDevOps Pipelines and @pytestdotorg please can you try pytest-azurepipelines==1.0.0rc3 it has loads of changes including embedding code coverage into the Pipelines UI from https://t.co/NjlLN1tfOD I need more testers! https://t.co/Mza0ke6UiS https://t.co/0FiABgr3l5" / Twitter

https://github.com/Azure/azure-quickstart-templates
https://twitter.com/di_codes/status/1295793468762136576

https://tonybaloney.github.io/posts/django-on-azure-beyond-hello-world.html | Django on Azure - beyond "hello world"

Hynek- Azure Pipelines
Publish Python packages in Azure Pipelines
https://docs.microsoft.com/en-us/azure/devops/pipelines/artifacts/pypi?view=azure-devops&tabs=yaml&viewFallbackFrom=vsts
https://docs.microsoft.com/en-us/azure/devops/pipelines/artifacts/pypi?view=azure-devops&tabs=yaml
https://hynek.me/articles/simple-python-azure-pipelines/ | Python in Azure Pipelines, Step by Step · Homepage of Hynek Schlawack
https://docs.microsoft.com/en-us/azure/devops/pipelines/process/container-phases?view=azure-devops&tabs=yaml | Container Jobs in Azure Pipelines and TFS - Azure Pipelines | Microsoft Docs

Azure Piplines
https://azure.microsoft.com/en-us/services/devops/pipelines/
https://docs.microsoft.com/en-us/azure/devops/pipelines/migrate/from-travis?view=azure-devops
https://medium.com/@anthonypjshaw/azure-pipelines-with-python-by-example-aa65f4070634
https://github.com/asottile/azure-pipeline-templates

https://github.com/trallard/pycon2020-azure-functions | trallard/pycon2020-azure-functions: ⚡️ 🏻‍♀️ Sponsored tutorial content for PyCon 2020
-->

## Hosts, Containers, Serverless, Functions, Pipelines

Containers
* [Kubernetes](http://kubernetes.io) and [Kubernetes Docs](https://kubernetes.io/docs/home)
* [Docker](https://www.docker.com) and [Docker Docs](https://docs.docker.com)
* ["Getting Started with Docker for Mac"](https://docs.docker.com/docker-for-mac)

AWS- Lambda
* [AWS Lambda](http://aws.amazon.com/lambda) and [AWS Lambda Documentation](http://docs.aws.amazon.com/lambda/latest/dg/welcome.html) 
* [AWS API Gateway](https://aws.amazon.com/api-gateway/)
* [Serverless GitHub](https://github.com/serverless/serverless) 
* [Zappa GitHub](https://github.com/Miserlou/Zappa)

Additional Serverless
* [Google Cloud Functions](https://cloud.google.com/functions/docs)
* [Firebase Functions](https://firebase.google.com/features/functions)
* [Azure Functions](https://azure.microsoft.com/en-us/services/functions) and [Azure Functions GitHub](https://github.com/Azure/Azure-Functions)

<!--
https://developers.google.com/actions/templates/first-app | Templates  |  Actions on Google  |  Google Developers

Google Cloud

https://twitter.com/di_codes/status/1215368211211923456 | Dustin Ingram on Twitter: "Happy to announce the release of a Function Framework for Python via @GoogleOSS. 🎉 It lets you run a Cloud Function locally for development or deploy it to other services (like Cloud Run)... without having to change your function at all. More details: https://t.co/87xrnAdvg3" / Twitter
https://dev.to/googlecloud/portable-cloud-functions-with-the-python-functions-framework-a6a | Portable Cloud Functions with the Python Functions Framework - DEV Community 👩‍💻👨‍💻

Google Cloud Django/Python
https://github.com/GoogleCloudPlatform/django-cloud-deploy | GoogleCloudPlatform/django-cloud-deploy: Easier deployment of Django applications in the cloud.
https://github.com/GoogleCloudPlatform/python-docs-samples | GoogleCloudPlatform/python-docs-samples: Code samples used on cloud.google.com

https://twitter.com/glasnt/status/1208096663887216641 | Katie McLaughlin ✨ on Twitter: "@jacobian Yes, just to avoid raw secrets. Berglas is a helper/wrapper for Cloud KMS" / Twitter

https://github.com/Miserlou/lambda-packages | Miserlou/lambda-packages: Various popular python libraries, pre-compiled to be compatible with AWS Lambda
https://github.com/Miserlou/zappa-django-utils | Miserlou/zappa-django-utils: A handy Django application to supercharge your Zappa deployments.

https://blog.zappa.io/posts/s3sqlite-a-serverless-relational-database

https://serverless.com
https://github.com/serverless/site
https://github.com/serverless/examples | serverless/examples: Serverless Examples – A collection of boilerplates and examples of serverless architectures built with the Serverless Framework and AWS Lambda

https://aws.amazon.com/step-functions/ | AWS Step Functions – Coordinate Microservices using Visual Workflows
http://docs.aws.amazon.com/lambda/latest/dg/concurrent-executions.html | Lambda Function Concurrent Executions - AWS Lambda
https://cloud.google.com/functions/docs/ | Google Cloud Functions Documentation  |  Cloud Functions  |  Google Cloud Platform
    
https://github.com/awslabs/chalice
https://github.com/apex/apex
https://github.com/apex/up | apex/up: Deploy infinitely scalable serverless apps, apis, and sites in seconds.
-->

## Automation

Terraform
* [Terraform](https://www.terraform.io) and [Terraform Module Registry](https://registry.terraform.io)

Python- Fabric
* [Fabric](http://www.fabfile.org), [Fabric PyPi](https://pypi.python.org/pypi/Fabric), and [Fabric GitHub](https://github.com/fabric/fabric) 

<!--
salt, ansible

http://docs.fabfile.org/en/1.13/api/contrib/django.html

https://www.digitalocean.com/community/tutorials/how-to-use-fabric-to-automate-administration-tasks-and-deployments
-->