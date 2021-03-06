..  Do not change this document name!
    Referred to by: Aldryn django CMS repository
    Where: https://github.com/divio/aldryn-django-cms/readme.rst
    Referred to by: Intercom welcome message
    Where: https://app.intercom.com/a/apps/wcfe7111/outbound/messages/auto/354454445
    As: https://docs.divio.com/en/latest/introduction


.. raw:: html

    <style>
        .row {clear: both}

        @media only screen and (min-width: 1000px),
               only screen and (min-width: 500px) and (max-width: 768px){

            .column {
                padding-left: 5px;
                padding-right: 5px;
                float: left;
            }

            .column2  {
                width: 50%;
            }
        }

        .main-visual {
            margin-bottom: 0 !important;
        }
    </style>


.. _introduction:

Get started
===========

The tutorial will introduce you to the Divio toolchain, and the complete cycle of project creation, development,
deployment and management as a developer, from setting up a project locally to deploying your own application on the
cloud. It assumes you are comfortable with the command line, and understand the basics of using SSH keys, Git
and so on.

**Before you do anything else, start here.** The local development environment is where you'll be doing most of your
work.

..  toctree::
    :maxdepth: 1

    01-installation


Next, select your path through the tutorial.

..  What follows is a terrible hack to force the behaviour we want from Sphinx. It could end badly. See hacks.rst for
    more.

..  raw:: html

    <div class="tabs">
      <div class="tabs__nav">
         <a href="#django-tab" class="tabs__link tab__link--active">
           <img src="../_images/django-logo-negative.svg" alt="Django" width="60">
         </a>
         <a href="#aldryn-tab" class="tabs__link tab__link--active">
           Django with <img src="../_images/aldryn-logo.svg" alt="Aldryn" width="100">
         </a>
         <a href="#wagtail-tab" class="tabs__link tab__link--active">
           <img src="../_images/wagtail-logo.svg" alt="Wagtail" width="60"></a>
         </a>
         <a href="#php-laravel-tab" class="tabs__link">
           <img src="../_images/laravel-logo.svg" alt="Laravel" width="60"> (beta)</a>
        </a>
      <div>
      <div class="tabs__content">


.. _django:

..  rst-class:: tabs-pane

Django
~~~~~~~~~~~~~~~~~~~~~~

This tutorial is recommended as an introduction for all Python/Django developers.

.. toctree::
    :maxdepth: 1
    :numbered: 1

    django-02-create-project
    django-03-setup-project-locally
    django-04-deploy
    django-05-database
    django-06-static
    django-07-media
    django-08-refinements


.. _aldryn-django-chapters:

..  rst-class:: tabs-pane

Django with Aldryn
~~~~~~~~~~~~~~~~~~~~~~

Aldryn is our auto-configuration framework for Django.

.. toctree::
    :maxdepth: 1
    :numbered: 1

    aldryn-django-02-create-project
    aldryn-django-03-setup-project-locally.rst
    aldryn-django-04-add-application
    aldryn-django-05-more-complex-configuration


.. _wagtail:

..  rst-class:: tabs-pane

Wagtail
~~~~~~~~~~~~~~~~~~~~~~

Aldryn is our auto-configuration framework for Django. Wagtail is one of the most popular Django-based content
management systems.

.. toctree::
    :maxdepth: 1
    :numbered: 1

    wagtail-02-create-project
    wagtail-03-setup-project-locally
    wagtail-04-add-application


.. |flavours| image:: /images/flavours.svg
   :width: 9


.. _php-laravel:

..  rst-class:: tabs-pane

PHP/Laravel, using Flavours
~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Flavours <https://flavours.dev>`_ is an open specification for web application configuration>.

.. toctree::
    :maxdepth: 1
    :numbered: 1

    laravel-02-create-project
    laravel-03-setup-project-locally
    laravel-04-add-application
    laravel-05-flavours


.. raw:: html

    </div><!-- .tabs__content -->
    </div><!-- .tabs -->
