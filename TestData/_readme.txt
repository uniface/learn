The xml files in this folder are exports of data used in the e-learning development environment.
If you used the installer, they will have already been imported into a single-use SQLite database (dbms\userdata.db).

If using a different database, they can be imported into your database (after configuring asn\dbms.asn) from the IDE command line, e.g.

	/cpy xml:TestData\*.xml def:

The following entity definitions are not provided in the starting environment, but are created manually in core exercises:
	artcat
	article
	category
	countryflag