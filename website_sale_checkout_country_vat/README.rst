.. image:: https://img.shields.io/badge/licence-LGPL--3-blue.svg
   :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
   :alt: License: LGPL-3

=================================
Website Sale Checkout Country VAT
=================================

This module extends the functionality of website_sale module to autocomplete
VAT country code in checkout process.

Configuration
=============

The default country that will appear is the one of the current user, or the one
of the Public User assigned to the website, or the one of the company that owns
the website. Change it in the corresponding place to get a sane default.

If you want to have a sane default also in the country address, check the
`website_sale_default_country
<https://github.com/OCA/e-commerce/tree/8.0/website_sale_default_country>`_
module.

Usage
=====

When a customer makes a purchase and do the checkout process, the VAT country
code can be selected separated from the code itself. This is useful in 2 ways:

- User is implicitly forced to input (select) a country with its code.
- Error in the VAT now only can be raised by an incorrect vat, not the absence
  of the country code, which usually confuses users.

If you change the country for the address and the VAT is empty, the VAT country
changes automatically too.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/113/9.0

Known issues / Roadmap
======================

* Add tests

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/OCA/e-commerce/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
=======

Images
------

* Odoo Community Association: `Icon <https://github.com/OCA/maintainer-tools/blob/master/template/module/static/description/icon.svg>`_.

Contributors
------------

* Sergio Teruel <sergio.teruel@tecnativa.com>
* Carlos Dauden <carlos.dauden@tecnativa.com>
* Pedro M. Baeza <pedro.baeza@tecnativa.com>
* Jairo Llopis <jairo.llopis@tecnativa.com>

Maintainer
----------

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.
