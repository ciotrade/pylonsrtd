Pyramid Documentation
=====================

Getting Started
---------------

If you are new to Pyramid, we have a few resources that can help you get up to
speed right away:

* Check out  our `FAQ </faq/pyramid.html>`_.

* For help getting Pyramid set up, try the `install guide
  <pyramid_install.html>`_.

* To get the feel of how a Pyramid web application is created, go to the 
  `single file tasks tutorial </projects/pyramid_tutorials/en/latest/single_file_tasks/single_file_tasks.html>`_ page. 

* Like learning by example? Check out to the `wiki tutorial
  </projects/pyramid/en/1.2-branch/tutorials/wiki2/index.html>`_.

* Need help?  See :ref:`support-desc`.

Main Documentation
------------------

* `Pyramid documentation 1.3 </projects/pyramid/en/1.3-branch/>`_ (`1.3 PDF
  <http://media.readthedocs.org/pdf/pyramid/1.3-branch/pyramid.pdf>`_) (`1.3 Epub
  <http://media.readthedocs.org/epub/pyramid/1.3-branch/pyramid.epub>`_) - narrative and API
  documentation for Pyramid's alpha/beta release.

* `Pyramid documentation 1.2 </projects/pyramid/en/1.2-branch/>`_ (`1.2 PDF
  <http://media.readthedocs.org/pdf/pyramid/1.2-branch/pyramid.pdf>`_) (`1.2 Epub
  <http://media.readthedocs.org/epub/pyramid/1.2-branch/pyramid.epub>`_) - narrative and API
  documentation for Pyramid's current stable release.

* `Pyramid documentation 1.1 </projects/pyramid/en/1.1-branch/>`_ (`1.1 PDF
  <http://media.readthedocs.org/pdf/pyramid/1.1-branch/pyramid.pdf>`_) (`1.1 Epub
  <http://media.readthedocs.org/epub/pyramid/1.1-branch/pyramid.epub>`_) - narrative and API
  documentation for Pyramid's 1.1 version.

* `Pyramid documentation 1.0 </projects/pyramid/en/1.0-branch/>`_ (`1.0 PDF
  <http://media.readthedocs.org/pdf/pyramid/1.0-branch/pyramid.pdf>`_) (`1.0 Epub
  <http://media.readthedocs.org/epub/pyramid/1.0-branch/pyramid.epub>`_) - narrative and API
  documentation for Pyramid's 1.0 version.

* `Pyramid development documentation </projects/pyramid/en/latest/>`_ - narrative
  and API documentation for Pyramid's unreleased in-development version.

* `The Pyramid Tutorials
  </projects/pyramid_tutorials/en/latest/>`_ presents
  tutorial resources for Pyramid.

* `The Pyramid Cookbook
  </projects/pyramid_cookbook/en/latest/>`_ presents
  topical, practical usages of Pyramid.  The cookbook is unfinished.

Pyramid Add-On Documentation
----------------------------

Pyramid supports extensibility through add-ons.  The following add-ons are
officially endorsed by the Pylons Project, and their documentation is hosted
here.

* `pyramid_beaker </projects/pyramid_beaker/en/latest/>`_: Beaker session backend
  plug-in.

  - Maintained by: Ben Bangert, Chris McDonough

  - Version Control: https://github.com/Pylons/pyramid_beaker

* `pyramid_chameleon_genshi </projects/pyramid_chameleon_genshi/en/latest/>`_:
  template renderer for `Chameleon's Genshi implementation
  <http://chameleon.repoze.org/docs/latest/genshi.html>`_.

  - Maintained by: Chris McDonough

  - Version Control: https://github.com/Pylons/pyramid_chameleon_genshi

* `pyramid_debugtoolbar </projects/pyramid_debugtoolbar/en/latest/>`_, an interactive
  HTML debug toolbar for Pyramid.

  - Maintained by:  Chris McDonough, Blaise Laflamme

  - Version Control: https://github.com/Pylons/pyramid_debugtoolbar

* `pyramid_exclog </projects/pyramid_exclog/en/latest/>`_, a package which logs
  exceptions from Pyramid applications.

  - Maintained by:  Chris McDonough

  - Version Control: https://github.com/Pylons/pyramid_exclog

* `pyramid_handlers </projects/pyramid_handlers/en/latest/>`_: analogue of
  Pylons-style "controllers" for Pyramid.

  - Maintained by: Ben Bangert, Chris McDonough

  - Version Control: https://github.com/Pylons/pyramid_handlers

* `pyramid_jinja2 </projects/pyramid_jinja2/en/latest/>`_: `Jinja2
  <http://jinja.pocoo.org/>`_ template renderer for Pyramid

  - Maintained by: Rocky Burt

  - Version Control: https://github.com/Pylons/pyramid_jinja2

* `pyramid_jqm </projects/pyramid_jqm/en/latest/>`_, scaffolding for developing
  jQuery Mobile apps with Pyramid.

  - Maintained by:  Chris McDonough

  - Version Control: https://github.com/Pylons/pyramid_jqm

* `pyramid_mailer </projects/pyramid_mailer/en/latest/>`_: a package for the
  Pyramid framework to take the pain out of sending emails.

  - Maintained by:  Dan Jacobs, Chris McDonough

  - Version Control: https://github.com/Pylons/pyramid_mailer

* `pyramid_rpc </projects/pyramid_rpc/en/latest/>`_: RPC service add-on for
  Pyramid, supports XML-RPC in a more extensible manner than `pyramid_xmlrpc`
  with support for JSON-RPC and AMF.

  - Maintained by: Ben Bangert

  - Version Control: https://github.com/Pylons/pyramid_rpc

* `pyramid_tm </projects/pyramid_tm/en/latest/>`_: Centralized transaction 
  management for Pyramid applications (without middleware).

  - Maintained by: Rocky Burt

  - Version Control: https://github.com/Pylons/pyramid_tm

* `pyramid_who </projects/pyramid_who/en/latest/>`_: Authentication policy for 
  pyramid using repoze.who 2.0 API.

  - Maintained by: Chris McDonough, Tres Seaver

  - Version Control: https://github.com/Pylons/pyramid_who

* `pyramid_xmlrpc </projects/pyramid_xmlrpc/en/latest/>`_: XML-RPC add-on for
  Pyramid

  - Maintained by: Chris McDonough

  - Version Control: https://github.com/Pylons/pyramid_xmlrpc

* `pyramid_zcml </projects/pyramid_zcml/en/latest/>`_: Zope Configuration Markup
  Language configuration support for Pyramid.

  - Maintained by: Chris McDonough

  - Version Control: https://github.com/Pylons/pyramid_zcml

Pyramid Development Environment Documentation
---------------------------------------------

Development environments are packages which use Pyramid as a core, but offer
alternate services and scaffolding.  Each development environment presents a
set of opinions and a "personality" to its users.  Although users of a
development environment can still use all of the services offered by the
Pyramid core, they are usually guided to a more focused set of opinions
offered by the development environment itself.  Development environments
often have dependencies beyond those of the Pyramid core.

.. _akhet-desc:

* `Akhet </projects/akhet/en/v1.0.2/>`_: Akhet is an application scaffolding for
  Pyramid that's closer to the Pylons 1 style than Pyramid's built-in
  scaffolding. The manual also tries to be a gentler introduction to Pyramid
  for those from a Pylons-ish background.

  - Maintained by: Mike Orr

  - Version Control: https://bitbucket.org/sluggo/akhet

* `Khufu Project <http://khufuproject.github.com/>`_: Khufu is an application
  scaffolding for Pyramid that provides an environment to work with Jinja2 and
  SQLAlchemy.

  - Maintained by: Rocky Burt

  - Version Control: https://github.com/khufuproject

