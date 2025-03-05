.. SPDX-License-Identifier: AGPL-3.0-or-later

----

.. figure:: https://raw.githubusercontent.com/AeshEmi1/searxng-se/master/src/brand/SearXNG-SE_logo.png
   :target: https://aeshemi1.github.io/searxng-se/
   :alt: SearXNG-SE
   :width: 100%
   :align: center

----


An actual privacy-respecting, hackable `metasearch engine`_

It is NOT advised to use public SearXNG or SearXNG-SE instances. It is impossible to know if they are collecting logs, inspecting your web searches, or selling your data.

A user_, admin_ and developer_ handbook is available on the homepage_.

|SearXNG-SE install|
|SearXNG-SE homepage|
|SearXNG-SE wiki|
|AGPL License|
|Issues|
|commits|
|weblate|
|SearXNG-SE small logo|

----

.. _user: https://aeshemi1.github.io/searxng-se/user/
.. _admin: https://aeshemi1.github.io/searxng-se/admin
.. _developer: https://aeshemi1.github.io/searxng-se/dev
.. _homepage: https://aeshemi1.github.io/searxng-se/
.. _metasearch engine: https://en.wikipedia.org/wiki/Metasearch_engine

.. |SearXNG-SE install| image:: https://img.shields.io/badge/-install-red
   :target: https://aeshemi1.github.io/searxng-se/admin/installation.html

.. |SearXNG-SE homepage| image:: https://img.shields.io/badge/-homepage-red
   :target: https://aeshemi1.github.io/searxng-se/

.. |SearXNG-SE wiki| image:: https://img.shields.io/badge/-wiki-red
   :target: https://github.com/AeshEmi1/searxng-se/wiki

.. |AGPL License|  image:: https://img.shields.io/badge/license-AGPL-red.svg
   :target: https://github.com/AeshEmi1/searxng-se/blob/master/LICENSE

.. |Issues| image:: https://img.shields.io/github/issues/AeshEmi1/searxng-se?color=yellow&label=issues
   :target: https://github.com/AeshEmi1/searxng-se/issues

.. |PR| image:: https://img.shields.io/github/issues-pr-raw/AeshEmi1/searxng-se?color=yellow&label=PR
   :target: https://github.com/AeshEmi1/searxng-se/pulls

.. |commits| image:: https://img.shields.io/github/commit-activity/y/AeshEmi1/searxng-se?color=yellow&label=commits
   :target: https://github.com/AeshEmi1/searxng-se/commits/master

.. |weblate| image:: https://translate.codeberg.org/widgets/searxng/-/searxng/svg-badge.svg
   :target: https://translate.codeberg.org/projects/searxng/


Contact
=======

Open a discussion to ask questions or chat with the SearXNG-SE community!

Setup
=====

- A well maintained `Docker image`_, also built for ARM64 and ARM/v7
  architectures.
- Alternatively there are *up to date* `installation scripts`_.
- For individual setup consult our detailed `Step by step`_ instructions.
- To fine-tune your instance, take a look at the `Administrator documentation`_.

.. _Administrator documentation: https://aeshemi1.github.io/searxng-se/admin/index.html
.. _Step by step: https://aeshemi1.github.io/searxng-se/admin/installation-searxng.html
.. _installation scripts: https://aeshemi1.github.io/searxng-se/admin/installation-scripts.html
.. _Docker image: https://github.com/AeshEmi1/searxng-se-docker

Translations
============

.. _Weblate: https://translate.codeberg.org/projects/searxng/searxng/

This is not maintained by us, but translations to SearXNG help our project as well. Help translate SearXNG at `Weblate`_

.. figure:: https://translate.codeberg.org/widgets/searxng/-/multi-auto.svg
   :target: https://translate.codeberg.org/projects/searxng/


Contributing
============

.. _development quickstart: https://aeshemi1.github.io/searxng-se/dev/quickstart.html
.. _developer documentation: https://aeshemi1.github.io/searxng-se/dev/index.html

Are you a developer?  Have a look at our `development quickstart`_ guide, it's
very easy to contribute.  Additionally we have a `developer documentation`_.


Codespaces
==========

You can contribute from your browser using `GitHub Codespaces`_:

- Fork the repository
- Click on the ``<> Code`` green button
- Click on the ``Codespaces`` tab instead of ``Local``
- Click on ``Create codespace on master``
- VSCode is going to start in the browser
- Wait for ``git pull && make install`` to appear and then disappear
- You have `120 hours per month`_ (see also your `list of existing Codespaces`_)
- You can start SearXNG using ``make run`` in the terminal or by pressing ``Ctrl+Shift+B``

.. _GitHub Codespaces: https://docs.github.com/en/codespaces/overview
.. _120 hours per month: https://github.com/settings/billing
.. _list of existing Codespaces: https://github.com/codespaces
