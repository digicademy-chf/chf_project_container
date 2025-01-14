..  include:: /Includes.rst.txt

.. _start:

=============
CHF Container
=============

:Package name:
    digicademy/chf_container

:Version:
    |release|

:Language:
    en

:Author:
    `Jonatan Jalle Steller <mailto:jonatan.steller@adwmainz.de>`__,
    CHF Container contributors

:License:
    This document is published under the
    `CC BY 4.0 <https://creativecommons.org/licenses/by/4.0/>`__
    license.

:Rendered:
    |today|

----

This is a container set-up for development and production environments of
projects based on the Cultural Heritage Framework (CHF). It is designed to be
usable across projects to either produce a fresh installation or to use a set
of project-specific files, which should be stored separately. The set-up
revolves around a file in accordance with the
`Compose specification <https://compose-spec.io/>`__ for container-based
applications that should allow you to set up your environment(s) on Linux,
macOS, or Windows via, for example, Podman Desktop or Docker Desktop. The
Compose file orchestrates a network consisting of an Apache webserver, a PHP-
and PHP Composer-capable Debian image that runs TYPO3, a MariaDB database,
Manticore search, Oxigraph triple store, and a Postfix container for email
jobs. An optional ``debug`` profile adds phpMyAdmin to this set-up. The
documentation provides install instructions as well as a few pointers towards
how to use the container-based environment.

----

**Table of contents:**

..  toctree::
    :maxdepth: 2
    :titlesonly:

    Introduction/Index
    InstallAndConfig/Index
    Usage/Index
    ProjectSpecificFiles/Index
    UsefulCommands/Index
    Maintenance/Index

..  Meta Menu

..  toctree::
    :hidden:

    Sitemap
