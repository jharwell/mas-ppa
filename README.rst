=============================
Multi-Agent Systems (MAS) PPA
=============================

This is the PPA for CI/CD builds of the following repositories:

.. list-table::
   :header-rows: 1
   :widths: 40 40 20

   * - Name
     - Repository URL
     - Package name

   * - Reusable C SoftWare (RCSW)
     - https://github.com/jharwell/rcsw.git
     - ``rcsw``

   * - Reusable C++ SoftWare (RCPPSW)
     - https://github.com/jharwell/rcppsw.git
     - ``rcppsw``

   * - Core Swarm (COSM)
     - https://github.com/jharwell/cosm.git
     - ``cosm``

To enable it::

  curl -s --compressed "https://jharwell.github.io/ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/ppa.gpg >/dev/null
  sudo curl -s --compressed -o /etc/apt/sources.list.d/ppa.list "https://jharwell.github.io/ppa/ppa.list"
  sudo apt update

You can then perform all the usual package actions.
