.. GeoPy documentation master file, created by
   sphinx-quickstart on Thu Oct 24 19:28:11 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to GeoPy's documentation!
=================================

.. automodule:: geopy
   :members: __doc__

Geocoders
~~~~~~~~~

.. automodule:: geopy.geocoders
   :members: __doc__

.. autoclass:: geopy.geocoders.Bing
    :members: __init__, geocode, reverse

.. autoclass:: geopy.geocoders.GoogleV3
    :members: __init__, geocode, reverse

.. autoclass:: geopy.geocoders.GeocoderDotUS
    :members: __init__, geocode

.. autoclass:: geopy.geocoders.GeoNames
    :members: __init__, geocode

.. autoclass:: geopy.geocoders.MapQuest
    :members: __init__, geocode

.. autoclass:: geopy.geocoders.OpenMapQuest
    :members: __init__, geocode

.. autoclass:: geopy.geocoders.YahooPlaceFinder
    :members: __init__, geocode

Calculating Distance
~~~~~~~~~~~~~~~~~~~~

.. automodule:: geopy.distance
    :members: __doc__

.. autoclass:: geopy.distance.vincenty
    :members: __init__

.. autoclass:: geopy.distance.great_circle
    :members: __init__

Data
~~~~

.. autoclass:: geopy.point.Point
    :members: __new__, from_string, from_sequence, from_point

Indices and search
==================

* :ref:`genindex`
* :ref:`search`
