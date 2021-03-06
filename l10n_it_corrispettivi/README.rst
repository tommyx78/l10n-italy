====================================
Italian Localization - Corrispettivi
====================================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-LGPL--3-blue.png
    :target: http://www.gnu.org/licenses/lgpl-3.0-standalone.html
    :alt: License: LGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fl10n--italy-lightgray.png?logo=github
    :target: https://github.com/OCA/l10n-italy/tree/11.0/l10n_it_corrispettivi
    :alt: OCA/l10n-italy
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/l10n-italy-11-0/l10n-italy-11-0-l10n_it_corrispettivi
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/122/11.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 

**Italiano**

Questo modulo permette di generare le ricevute specificando le varie aliquote per riga
(le righe della ricevuta hanno gli stessi automatismi di quelle della fattura) e quindi registrare le ricevute una per una.
Un esempio tipico di questo caso d’uso è la vendita tramite sito di e-commerce.

Chi invece emette scontrini (e non ha un POS integrato con Odoo) dovrà registrare in contabilità, a fine giornata, gli incassi totali.

**English**

This module allows you to generate receipts by specifying the different taxes per line
(the receipt lines have the same automatisms as those on the invoice) and then record the receipts one by one.
A typical example of this use case is the sale via e-commerce site.

On the other hand, those who issue receipts (and do not have an integrated POS with Odoo) will have to record the total revenue at the end of the day.

**Table of contents**

.. contents::
   :local:

Configuration
=============

**Italiano**

Creare almeno un sezionale di tipo vendita su cui saranno registrati i corrispettivi,
deve avere il flag corrispettivi abilitato.

Se necessario, creare una posizione fiscale per i corrispettivi, deve avere il flag corrispettivi abilitato.
Questa posizione fiscale verrà assegnata a tutti i nuovi partner aventi il flag *Usa corrispettivi* abilitato.

Utilizzando un utente del gruppo Contabilità & Finanza > Contabilità, sul partner associato al public user:

* Modificare, se necessario, i conti di debito e di credito da utilizzare per i corrispettivi;
* Abilitare il flag *Usa corrispettivi*

Nota: di default, il public user è disabilitato (flag active disabilitato).

**English**

Create at least one journal of type sales on which the fees will be recorded,
it must have the corrispettivi flag enabled.

If necessary, create a fiscal position for the corrispettivi, it must have the corrispettivi flag enabled.
This fiscal position will be assigned to all new partners with the *Use corrispettivi* flag enabled.

Using a user of the Accounting & Finance > Accounting group, on the partner associated with the public user:

* Change, if necessary, the debit and credit accounts to be used for the corrispettivi;
* Enable the flag *Use corrispettivi*

Note: by default, the public user is disabled (active flag disabled).

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/l10n-italy/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/l10n-italy/issues/new?body=module:%20l10n_it_corrispettivi%0Aversion:%2011.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Odoo Italian Community
* Agile Business Group

Contributors
~~~~~~~~~~~~

* Lorenzo Battistini <lorenzo.battistini@agilebg.com>
* Simone Rubino <simone.rubino@agilebg.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/l10n-italy <https://github.com/OCA/l10n-italy/tree/11.0/l10n_it_corrispettivi>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
