==================
Welcome to SearXNG-SE
==================

  *Search without being tracked.*

.. jinja:: searx

   SearXNG-SE is a free internet metasearch engine which aggregates results from up
   to {{engines | length}} :ref:`search services <configured engines>`.  Users
   are neither tracked nor profiled.  Additionally, SearXNG-SE can be used over Tor
   for online anonymity.

Setup your own SearXNG-SE instance! See :ref:`installation`.

.. jinja:: searx

   .. sidebar::  features

      - :ref:`self hosted <installation>`
      - :ref:`no user tracking / no profiling <SearXNG-SE protect privacy>`
      - script & cookies are optional
      - secure, encrypted connections
      - :ref:`{{engines | length}} search engines <configured engines>`
      - `58 translations <https://translate.codeberg.org/projects/searxng/searxng/>`_
      - :ref:`easy integration of search engines <demo online engine>`
      - professional development: `CI <https://github.com/AeshEmi1/searxng-se/actions>`_,
   .. This will be taken care of eventually, need more maintaners...
	.. `quality assurance <https://dev.searxng.org/>`_ &
	.. `automated tested UI <https://dev.searxng.org/screenshots.html>`_

.. sidebar:: be a part

   SearXNG-SE is driven by an open community, come join us!  Don't hesitate, no
   need to be an *expert*, everyone can contribute:

   - `help to improve translations <https://translate.codeberg.org/projects/searxng/searxng/>`_
   - `discuss with the community <https://matrix.to/#/#searxng:matrix.org>`_
   - report bugs & suggestions
   - ...

.. sidebar:: the origin

   SearXNG-SE development has been started in the middle of 2021 as a fork of the
   searx project.


.. toctree::
   :maxdepth: 2

   user/index
   own-instance
   admin/index
   dev/index
   utils/index
   src/index
