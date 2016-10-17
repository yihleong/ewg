Big Data Sample Heat Template
==============================

This heat templates deploy a Hadoop cluster with Apache Ambari.
This template was tested using Mitaka & Liberty release of OpenStack.

-----------------
Heat File Details
-----------------


-------------------------------
Running the heat template files
-------------------------------

First you need to source your credential file.  You may download a copy of the
credential file from Horizon under Project>Compute>Access & Security>API
Access

**Example to setup the Hadoop cluster environment**

  openstack stack create --template BigData.yaml HadoopCluster



