.. title: 56k modem
.. slug: 56k-modem
.. date: 2025-10-28 07:29:40 UTC-03:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

.. class:: lead

Here is some usefulness to save on bandwidth, if you don't spend too much you may not even need a family plan.

.. code:: console

  ~ # tc qdisc add dev wlp4s0 root handle 1: tbf rate 56kbit burst 32kbit latency 400ms

.. class:: lead

These parameters are up for discussion.
