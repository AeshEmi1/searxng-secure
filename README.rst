.. SPDX-License-Identifier: AGPL-3.0-or-later

----

.. figure:: https://raw.githubusercontent.com/AeshEmi1/searxng/master/src/brand/searxng_secure.svg
   :target: https://aeshemi1.github.io/searxng-secure/
   :alt: SearXNG Secure
   :width: 100%
   :align: center

----


An actual privacy-respecting, hackable `metasearch engine`_

I highly suggest AGAINST using public SearXNG or SearXNG secure instances. It is impossible to know if they are collecting logs, or even worse inspecting your web searches in cleartext.
The pool of SearXNG and SearXNG secure users is much smaller than those of more mainstream search engines, thus making individual users much easier to track on public instances.

A user_, admin_ and developer_ handbook is available on the homepage_.

|SearXNG Secure install|
|SearXNG Secure homepage|
|SearXNG Secure wiki|
|AGPL License|
|Issues|
|commits|
|weblate|
|SearXNG Secure logo|

----

.. _user: https://aeshemi1.github.io/searxng-secure/user/
.. _admin: https://aeshemi1.github.io/searxng-secure/admin
.. _developer: https://aeshemi1.github.io/searxng-secure/dev
.. _homepage: https://aeshemi1.github.io/searxng-secure/
.. _metasearch engine: https://en.wikipedia.org/wiki/Metasearch_engine

.. |SearXNG Secure logo| image:: https://raw.githubusercontent.com/AeshEmi1/searxng/master/src/brand/searxng_secure.svg
   :target: https://aeshemi1.github.io/
   :width: 5%

.. |SearXNG Secure install| image:: https://img.shields.io/badge/-install-blue
   :target: https://docs.searxng.org/admin/installation.html

.. |SearXNG Secure homepage| image:: https://img.shields.io/badge/-homepage-blue
   :target: https://docs.searxng.org/

.. |SearXNG Secure wiki| image:: https://img.shields.io/badge/-wiki-blue
   :target: https://github.com/searxng/searxng/wiki

.. |AGPL License|  image:: https://img.shields.io/badge/license-AGPL-blue.svg
   :target: https://github.com/searxng/searxng/blob/master/LICENSE

.. |Issues| image:: https://img.shields.io/github/issues/searxng/searxng?color=yellow&label=issues
   :target: https://github.com/searxng/searxng/issues

.. |PR| image:: https://img.shields.io/github/issues-pr-raw/searxng/searxng?color=yellow&label=PR
   :target: https://github.com/searxng/searxng/pulls

.. |commits| image:: https://img.shields.io/github/commit-activity/y/searxng/searxng?color=yellow&label=commits
   :target: https://github.com/searxng/searxng/commits/master

.. |weblate| image:: https://translate.codeberg.org/widgets/searxng/-/searxng/svg-badge.svg
   :target: https://translate.codeberg.org/projects/searxng/


Contact
=======

Open a discussion to ask questions or chat with the SearXNG Secure community!

Setup
=====

- A well maintained `Docker image`_, also built for ARM64 and ARM/v7
  architectures.
- Alternatively there are *up to date* `installation scripts`_.
- For individual setup consult our detailed `Step by step`_ instructions.
- To fine-tune your instance, take a look at the `Administrator documentation`_.

.. _Administrator documentation: https://aeshemi1.github.io/searxng-secure/admin/index.html
.. _Step by step: https://aeshemi1.github.io/searxng-secure/admin/installation-searxng.html
.. _installation scripts: https://aeshemi1.github.io/searxng-secure/admin/installation-scripts.html
.. _Docker image: https://github.com/AeshEmi1/searxng-docker

Translations
============

.. _Weblate: https://translate.codeberg.org/projects/searxng/searxng/

Help translate SearXNG at `Weblate`_

.. figure:: https://translate.codeberg.org/widgets/searxng/-/multi-auto.svg
   :target: https://translate.codeberg.org/projects/searxng/


Contributing
============

.. _development quickstart: https://aeshemi1.github.io/searxng-secure/dev/quickstart.html
.. _developer documentation: https://aeshemi1.github.io/searxng-secure/dev/index.html

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
