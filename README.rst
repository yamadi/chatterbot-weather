===============================
chatterbot-weather
===============================

.. image:: https://img.shields.io/pypi/v/chatterbot-weather.svg
        :target: https://pypi.python.org/pypi/chatterbot-weather

.. image:: https://img.shields.io/travis/gunthercox/chatterbot-weather.svg
        :target: https://travis-ci.org/gunthercox/chatterbot-weather

.. image:: https://readthedocs.org/projects/chatterbot-weather/badge/?version=latest
        :target: http://chatterbot-weather.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

A ChatterBot logic adapter that returns information about the weather.
For more information about ChatterBot see https://github.com/gunthercox/ChatterBot

* Documentation: https://chatterbot-weather.readthedocs.org.

Installation
------------

.. code-block:: bash

   pip install chatterbot-weather

Example
-------

.. code-block:: python

   from chatterbot import ChatBot

   chatbot = ChatBot(
       'My Weather Bot',
       logic_adapters=[
           'chatterbot_weather.WeatherLogicAdapter'
       ]
   )
