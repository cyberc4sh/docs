.. _install-ubuntu-1604-server:

Installing Ubuntu Server 16.04 LTS
==================================

.. warning::
  Ubuntu 16.04 is approaching its End of Life in April 2021.
  Because of this, we don't recommend installing new instances of Mattermost on Ubuntu 16.04. Rather use a newer version such as Ubuntu 20.04.

Install the 64-bit version of Ubuntu Server on each machine that hosts one or more of the components.

**To install Ubuntu Server 16.04:**

1. To install Ubuntu Server 16.04, see the `Ubuntu Installation Guide. <https://help.ubuntu.com/16.04/installation-guide/amd64/index.html>`__

2. After the system is installed, make sure that it's up to date with the most recent security patches. Open a terminal window and issue the following commands:

  ``sudo apt-get update``

  ``sudo apt-get upgrade``

Now that the system is up to date, you can start installing the components that make up a Mattermost system.
