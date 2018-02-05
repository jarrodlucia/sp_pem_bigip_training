Welcome
-------

Welcome to F5's Service Provider PEM Training


Getting Started
---------------

Please follow the instructions provided by this documentation to start your
lab and access your lab.

.. NOTE::


Prerequisites
-------------

In order to complete this series of training classes you will need to utilize
the provided blueprint for the course session.


All pre-built environments implement the :ref:`lab-topology` shown below.

There will be three methods to utilise:
-	Local Laptop (Docker + VM) - Preferred

- Ravello Pre-Built Labs

- UDF Pre-Built Labs

Local Laptop
~~~~~~~~~~~~~~~~~

Please follow the instructions provided by your lab instructor to build the lab.

.. NOTE:: Need to build this

UDF Blueprint
~~~~~~~~~~~~~~~~~

Please follow the instructions provided by your lab instructor to access your
lab environment. The lab environment will be delivered  via UDF blueprints to
each student.

.. NOTE:: Please deploy and start your lab as soon as you have access to the class as the lab takes some time to boot all the components.


Lab Topology
------------

The network topology below (need to add details)
The following components have been included in your lab environment:

-  1 x ``F5 BIG-IP VE`` (v13.0 HF2)

-  1 x Docker Container Ship

Include UDF / Ravello Lab stuff here as well

.. _lab-topology:

|lab_topo1|


The following table lists VLANS, IP Addresses and Credentials for all
components:

.. csv-table:: Lab Network Information
    :header: "Component", "VLAN", "IP Address", "Credentials"
    :widths: 40, 40, 40, 60

    "Linux Jumphost", "Mgmt", "10.1.1.20", ""
    "BIG-IP", "Mgmt", "10.1.1.4", "admin/admin"
    "", "Internal", "10.1.10.5", ""
    "", "External", "10.1.20.5", ""
    "", "Control", "10.1.30.5", ""
    "Client 00", "Mgmt", "10.1.1.9", "udfclient/S3rv1ceP0weR"
    "", "Internal", "10.1.10.25", ""
    "Client 01", "Mgmt", "10.1.1.7", "udfclient/S3rv1ceP0weR"
    "", "Internal", "10.1.10.30", ""
    "ELK Stack", "Mgmt", "10.1.1.5", "ubuntu/default"
    "", "Control", "10.1.30.15", ""

.. |lab_topo1| image:: /_static/lab_topology.png
   :width: 8in
   :height: 4in
