MQTT Message Broker
===================

This is a MQTT Message Broker under development. It consists of a MQTT-client (we use Paho), a MQTT-server, any database and some logic connecting all.

All rights reserved except for Paho.
The Eclipse Foundation is not liable for any modifications of Paho for this project.

Developers
----------
* Pierre-Antoine Rault
* Oskar Dario Schlösinger
* Michael Chlepakov
* Philipp Ostertag

Eclipse Paho MQTT Python Client
===============================

This document describes the source code for the `Eclipse Paho <http://eclipse.org/paho/>`_ MQTT Python client library, which implements versions 3.1 and 3.1.1 of the MQTT protocol.

This code provides a client class which enable applications to connect to an `MQTT <http://mqtt.org/>`_ broker to publish messages, and to subscribe to topics and receive published messages. It also provides some helper functions to make publishing one off messages to an MQTT server very straightforward.

It supports Python 2.7 or 3.x, with limited support for Python 2.6.

The MQTT protocol is a machine-to-machine (M2M)/"Internet of Things" connectivity protocol. Designed as an extremely lightweight publish/subscribe messaging transport, it is useful for connections with remote locations where a small code footprint is required and/or network bandwidth is at a premium.

Paho is an `Eclipse Foundation <https://www.eclipse.org/org/foundation/>`_ project.
