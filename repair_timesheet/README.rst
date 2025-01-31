================
Repair Timesheet
================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:96631264a3c89c87489c8233a4d83c738ada5634b66a4714d7636405fe1e4b90
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Frepair-lightgray.png?logo=github
    :target: https://github.com/OCA/repair/tree/17.0/repair_timesheet
    :alt: OCA/repair
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/repair-17-0/repair-17-0-repair_timesheet
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/repair&target_branch=17.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module integrates timesheet tracking with repair orders. It adds a
"Timesheets" tab to the repair order form, allowing users to log and
track the time spent on each repair through timesheet entries. Users can
record detailed timesheet data, such as the project, task, date, and
duration for each repair. Additionally, the module automatically
calculates the total hours spent on repairs and displays this
information in both the form view and the list view of repair orders.

**Table of contents**

.. contents::
   :local:

Usage
=====

When creating or editing a repair order, you will find a new Timesheets
tab within the repair order form. In this tab, you can log and track the
time spent on the repair by adding timesheet entries. Each entry allows
you to specify the project, task, date, and the time spent on the repair
in hours and minutes.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/repair/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/repair/issues/new?body=module:%20repair_timesheet%0Aversion:%2017.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
-------

* APSL-Nagarro

Contributors
------------

-  `APSL-Nagarro <https://apsl.tech>`__:

      -  Patryk Pyczko <ppyczko@apsl.net>

Maintainers
-----------

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

.. |maintainer-ppyczko| image:: https://github.com/ppyczko.png?size=40px
    :target: https://github.com/ppyczko
    :alt: ppyczko

Current `maintainer <https://odoo-community.org/page/maintainer-role>`__:

|maintainer-ppyczko| 

This module is part of the `OCA/repair <https://github.com/OCA/repair/tree/17.0/repair_timesheet>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
