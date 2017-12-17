========================
Even more Awesome Django
========================


#. `Good practices, conventions`_
   #. `General`_
   #. `Django`_
#. `Models, model fields, mixins`_
   #. `Flow control`_
   #. `Measurement data`_
   #. `Translations`_
#. `Forms, form fields, widgets`_
   #. `Autocomplete`_
#. `Admin interface`_
   #. `Themes`_
#. `Views, templates, templatetags`_
   #. `SEO & SEM`_
   #. `Typography`_
#. `File & image processing`_
   #. `Watermarks`_
#. `Security, authentication`_
#. `E-commerce`_
   #. `Cart`_
   #. `Taxes`_
#. `DevOps tools`_


***************************
Good practices, conventions
***************************

General
*******
- `The Twelve-Factor App <https://12factor.net/>`_
  (`GitHub <https://github.com/heroku/12factor>`_)
    "The twelve-factor app is a methodology for building software-as-a-service apps."
- `Zeromalist <http://verekia.com/zeromalist/>`_ – Zero is more
    "This manifesto documents my minimalism and simple living guidelines."

Frontend
********
- `BEM (bem.info) <https://bem.info//>`_ - Block Element Modifier
  (`GitHub <https://github.com/getbem>`_)
    "A component-based approach to web development."
- `BEM (getbem.com) <http://getbem.com/>`_ - Block Element Modifier
  (`GitHub <https://github.com/getbem>`_)
    "A methodology that helps you to create reusable components and code sharing in front-end development."

Django
******
- `Django Design Patterns <http://agiliq.com/books/djangodesignpatterns/>`_
  (`GitHub <https://github.com/agiliq/django-design-patterns>`_)
    "Django design patterns is a book about commonly occurring patterns in Django."
- `django-better500s <https://djangopackages.org/packages/p/django-better500s/>`_
  (`Newest GitHub fork <https://github.com/mwharrison/django-better500s>`_)
    "A library that makes 500 errors more user-friendly, and developer friendly."


****************************
Models, model fields, mixins
****************************
- `django-model-utils <https://djangopackages.org/packages/p/django-model-utils/>`_
  (`GitHub <https://github.com/jazzband/django-model-utils>`_)
    "Django model mixins and utilities."
    | - Fields: ``StatusField``, ``MonitorField``, ``SplitField``
    | - Models: ``TimeFramedModel``, ``TimeStampedModel``, ``StatusModel``, ``SoftDeletableModel``
    | - Miscellaneous Utilities: Choices, Field Tracker
- `django-polymorphic <https://djangopackages.org/packages/p/django-polymorphic/>`_
  (`GitHub <https://github.com/django-polymorphic/django-polymorphic>`_)
    "Improved Django model inheritance with automatic downcasting."

Flow control
************
- `Django Concurrency <https://djangopackages.org/packages/p/django-concurrency/>`_
  (`GitHub <https://github.com/saxix/django-concurrency>`_)
    "An optimistic locking library for Django Models... It prevents users from doing concurrent editing in Django both from UI and from a django command."
    | **My favourite part of this tool is `` `TriggerVersionField <https://django-concurrency.readthedocs.io/en/stable/fields.html#triggerversionfield>`_ ``, which "use a database trigger to update the version field".**
- `django-fsm <https://djangopackages.org/packages/p/django-fsm/>`_
  (`GitHub <https://github.com/kmmbvnr/django-fsm>`_)
    "Django friendly finite state machine support. Adds simple declarative states management for django models."

Measurement data
****************
- `django-measurement <https://djangopackages.org/packages/p/django-measurement/>`_
  (`GitHub <https://github.com/coddingtonbear/django-measurement>`_)
    "Easily store, retrieve, and convert measurements of weight, volume, distance, area and more."
- `django-unitology <https://djangopackages.org/packages/p/django-unitology/>`_
  (`GitHub <https://github.com/bashu/django-unitology>`_)
    "A custom model fields to store, retrieve and convert measurements of height, weight and more."

Tagging
*******
- `django-taggit <https://djangopackages.org/packages/p/django-taggit/>`_
  (`GitHub <https://github.com/alex/django-taggit>`_)
    "A simpler approach to tagging with Django."
- `taggit-selectize <https://djangopackages.org/packages/p/taggit-selectize/>`_
  (`GitHub <https://github.com/chhantyal/taggit-selectize>`_)
    "Auto-complete/auto-suggestion for django-taggit."


Translations
************
- `django-parler <https://djangopackages.org/packages/p/django-parler/>`_
  (`GitHub <https://github.com/django-parler/django-parler>`_)
    "Simple Django model translations without nasty hacks."


***************************
Forms, form fields, widgets
***************************
- `Smart Selects <https://djangopackages.org/packages/p/django-smart-selects/>`_
  (`GitHub <https://github.com/digi604/django-smart-selects>`_)
    "Chained and grouped selects for django forms."

Autocomplete
************
- `django-autocomplete-light <https://djangopackages.org/packages/p/django-autocomplete-light//>`_
  (`GitHub <https://github.com/yourlabs/django-autocomplete-light>`_)
    "A fresh approach to autocomplete implementations, specially for Django."
- `Django-autocomplete-light filters <https://djangopackages.org/packages/p/dal_admin_filters/>`_
  (`GitHub <https://github.com/shamanu4/dal_admin_filters>`_)
    "Django-autocomplete-light filters for django admin."
- `Django-Select2 <https://djangopackages.org/packages/p/django_select2/>`_
  (`GitHub <https://github.com/applegrew/django-select2>`_)
    "A Django integration for Select2."


***************
Admin interface
***************
- `django Admin Shortcuts <https://djangopackages.org/packages/p/django-admin-shortcuts/>`_
  (`GitHub <https://github.com/alesdotio/django-admin-shortcuts>`_)
    "A simple dashboard app that adds shortcuts to your django admin homepage."

Themes
******
- `Django Suit <https://djangopackages.org/packages/p/django-suit/>`_
  (`GitHub <https://github.com/darklow/django-suit>`_)
    "A modern theme for Django admin interface"
- `django-admin-interface <https://djangopackages.org/packages/p/django-admin-interface/>`_
  (`GitHub <https://github.com/fabiocaccamo/django-admin-interface>`_)
    "A customizable responsive admin interface, based on a modern flat theme... Popup windows replaced by modals."


******************************
Views, templates, templatetags
******************************
- Towel
  (`GitHub <https://github.com/matthiask/towel/>`_)
    "A collection of tools which make your life easier if you are building a web application using Django. It contains helpers and templates for creating paginated, searchable object lists, CRUD functionality helping you safely and easily create and update objects..."
- `django-fullurl <https://djangopackages.org/packages/p/django-fullurl/>`_
  (`GitHub <https://github.com/Flimm/django-fullurl>`_)
    "Three new template tags... They always return an absolute URL with the scheme and authority/domain parts."

SEO & SEM
*********
- `django-meta <https://djangopackages.org/packages/p/django-meta/>`_
  (`GitHub <https://github.com/nephila/django-meta>`_)
    "Allows Django developers to quickly add meta tags and OpenGraph, Twitter, and Google Plus properties to their HTML responses."

Typography
**********
- `django-typogrify <https://djangopackages.org/packages/p/django-typogrify/>`_
  (`GitHub <https://github.com/chrisdrackett/django-typogrify>`_)
    "A set of custom filters for the Django template system which automatically apply various transformations to plain text in order to yield typographically-improved HTML."


***********************
File & image processing
***********************

Watermarks
**********
- `django-watermark <https://djangopackages.org/packages/p/django-watermark/>`_
  (`GitHub <https://github.com/bashu/django-watermark>`_)
    "A simple way for you to apply custom watermarks to images on your django-powered website."
- `django-watermarker <https://djangopackages.org/packages/p/django-watermarker/>`_
  (`GitHub <https://github.com/Skycker/watermarker>`_)
    "A tool for easy creating watermarks in you Django project"


************************
Security, authentication
************************
- `django-stronghold <https://djangopackages.org/packages/p/django-stronghold/>`_
  (`GitHub <https://github.com/mgrouchy/django-stronghold>`_)
    "Get inside your stronghold and make all your Django views default login_required "


**********
E-commerce
**********
- `django-SHOP <https://djangopackages.org/packages/p/django-shop/>`_
  (`GitHub <https://github.com/awesto/django-shop>`_)
    "A Django based shop system."

Cart
****
- `Django Carton <https://djangopackages.org/packages/p/django-carton/>`_
  (`GitHub <https://github.com/lazybird/django-carton>`_)
    "A simple and lightweight application for shopping carts and wish lists."
- `django-easycart <https://djangopackages.org/packages/p/django-easycart/>`_
  (`GitHub <https://github.com/nevimov/django-easycart>`_)
    "A flexible session-based shopping cart application for Django."

Taxes
*****
- django-oscar-eurotaxes
  (`Bitbucket <https://bitbucket.org/abalt/django-oscar-eurotaxes>`_)
    "This package manage taxes on django-oscar. The package is structured so that it can be used only with Oscar."


************
DevOps tools
************
- `django-watchman <https://djangopackages.org/packages/p/django-watchman/>`_
  (`GitHub <https://github.com/mwarkentin/django-watchman>`_)
    "Exposes a status endpoint for your backing services like databases, caches, etc."
