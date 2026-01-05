.. image:: https://odoo-community.org/readme-banner-image
   :target: https://odoo-community.org/get-involved?utm_source=readme
   :alt: Odoo Community Association

==============================
MRP Production Allow Recursive
==============================

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/license-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fmanufacture-lightgray.png?logo=github
    :target: https://github.com/OCA/manufacture/tree/17.0/mrp_production_allow_recursive
    :alt: OCA/manufacture

|badge1| |badge2| |badge3|

This module allows the same product to be used as both a component and a
finished product in manufacturing orders.

**Table of contents**

.. contents::
   :local:

Use Cases / Context
===================

In some manufacturing environments where procedures and master data
setup are not complete (such as during pre-mass-production phases),
there are often situations where you need to add extra components or
operations to already-produced products in order to reflect the actual
production situation.

Configuration
=============

1. Navigate to Manufacturing > Configuration > Settings.
2. Find and enable the 'Allow Same Product for Component and Finish'
   option to allow using the same product as both a component and a
   finished product in manufacturing orders.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/manufacture/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/manufacture/issues/new?body=module:%20mrp_production_allow_recursive%0Aversion:%2017.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
-------

* Quartile

Contributors
------------

- `Quartile <https://www.quartile.co>`__:

  - Aung Ko Ko Lin

Maintainers
-----------

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-yostashiro| image:: https://github.com/yostashiro.png?size=40px
    :target: https://github.com/yostashiro
    :alt: yostashiro
.. |maintainer-aungkokolin1997| image:: https://github.com/aungkokolin1997.png?size=40px
    :target: https://github.com/aungkokolin1997
    :alt: aungkokolin1997

Current `maintainers <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-yostashiro| |maintainer-aungkokolin1997| 

This module is part of the `OCA/manufacture <https://github.com/OCA/manufacture/tree/17.0/mrp_production_allow_recursive>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
