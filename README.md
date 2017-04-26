Odoo资源精选
============

Odoo资源精选列表
*Inspired by [awesome-python](https://github.com/vinta/awesome-python), itself inspired by  [awesome-php](https://github.com/ziadoz/awesome-php).*

Contributions are welcome - check the [guidelines](CONTRIBUTING.md).

Documentation
-------------

- [Technical Memento](https://www.odoo.com/files/memento/OpenERP_Technical_Memento_latest.pdf) (pdf) is a short reference, a little outdated, but that still can't be missed.
- [Current official documentation](https://www.odoo.com/documentation/8.0/) actively maintained by the R&D team.
- [New API Guidelines](http://odoo-new-api-guide-line.readthedocs.org/), by Nicolas Bessi, can provide additional insights not yet covered in the official docs.
- [OpenERP Tutorial: Module creation and modification of the Point Of Sale](http://thierry-godin.developpez.com/openerp/tutorial-module-creation-pos-modification-english-version/#), by Thierry Goodin, great tutorial.
- [Data Model Documentation](http://useopenerp.com/v8) with UML diagrams.
- [Odoo HOW TO](https://www.odoo.com/forum/how-to) A list of common forum questions.
- [The Hitchhikers guide to Odoo](https://www.odoo.com/forum/help-1/question/the-hitchhikers-guide-to-odoo-71524) A guide for getting started.
- [Blogs](https://www.odoo.com/forum/help-1/question/what-blogs-tutorials-forums-exist-about-odoo-68797) A curated list of several blogs.

Documentation for older version can sometimes fill a few gaps in the latest docs:
- [v7.0 official documentation](https://doc.odoo.com/)
- [v6 developer documentation](http://openerp-server.readthedocs.org/en/latest/index.html)

Tools
-----
- [ERPPeek](https://pypi.python.org/pypi/ERPpeek) provides both a fully featured low-level API, and an encapsulation of the methods on Active Record objects, plus helpers to administrate the server remotely ([docs](http://erppeek.readthedocs.org)).
- [Mandibule](https://bitbucket.org/mandibule/mandibule), an Odoo Model browser ([doc](http://mandibule.bitbucket.org/)).
- [OdooRPC](https://github.com/osiell/odoorpc) is a Python JSON-RPC library which aims to provide an easy way to remotely pilot and manage an Odoo server.
- [Odoo Code Search](http://www.odoo-code-search.com/). A searchable index of odoo source code.

RAD
---
- [POS Template](https://github.com/haroldtamo/Odoo-Pos-Inheritance-Template) a template for rapid inheritance of POS module.

IDEs
----
- [Pycharm](http://www.jetbrains.com/pycharm/) a great IDE with [Odoo fast development templates](https://github.com/mohamedmagdy/odoo-pycharm-templates).
- [Sublime Text](http://www.sublimetext.com/) provides many useful plugins for ease development in Python and Javascript.

Report Engines
--------------
- [Aeroo Reports](https://github.com/aeroo/aeroo_reports): a versatile reporting engine with Open/LibreOffice integration ([doc](http://www.alistek.com/wiki/index.php/Main_Page)).
- [Pentaho Reports](https://github.com/WillowIT/Pentaho-reports-for-OpenERP): run Pentaho reports in Odoo and design them using the Pentaho report designer ([doc](https://github.com/WillowIT/Pentaho-reports-for-OpenERP/wiki), [presentation](http://www.slideshare.net/openobject/openerp-pentaho-integration-willowit)).
- [Jasper Report Server](https://github.com/mga-team-odoo/jasperserver): Compose report with iReport or JasperStudio and defined printing action in odoo to retrieve the report seamlessly.
- [Birt Reports](https://github.com/vaab/report_birt) Use [Birt Viewer](http://eclipse.org/birt/documentation/integrating/viewer-setup.php) to generate a report

Modules
-------

### Collaboration
- [`initOS/openerp-dav`](https://github.com/initOS/openerp-dav): vCard and CardDAV support for Odoo ([presentation](http://www.slideshare.net/initOS/webdav-caldav-co-in-odoo)).

### Document Management
- [`anybox/advanced_attachment`](https://bitbucket.org/anybox/advanced_attachment): store attachments as PostgreSQL large objects ([doc](http://anybox.fr/blog/postgresql-large-object-storage-for-odoo)).
