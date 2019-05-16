.. _index:

sgsession
=========

.. image:: https://secure.travis-ci.org/westernx/sgsession.png
    :alt: Test Status
    :target: http://travis-ci.org/westernx/sgsession

This Python package is a wrapper around `shotgun_api3 <https://github.com/shotgunsoftware/python-api>`_ for  `Shotgun <http://www.shotgunsoftware.com/>`_ which provides a local data cache and some additional intelligence on top of bare entities.

This has been crafted to mimick the normal interface, and graft extra features on top. However, this is **not** a drop-in replacement for the normal API. While any individual entity in isolation should behave in the same way as with the normal API, the entities are linked behind the scenes and so complex behaviour is likely to break.

Contents
--------

.. toctree::
   :maxdepth: 2
   
   overview
   session
   entity
   pool

