Installing pbuilder
===================

::

  sudo aptitude install pbuilder
  sudo pbuilder create

Building package
================

::

  sudo pbuilder build postgresql-tablelog_0.4.4-1.dsc

package can then be found at /var/cache/pbuilder/result/postgresql-tablelog_0.4.4-1*.deb
