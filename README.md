Review of the Resource Representation in Institutional Repository
========

There are two groups of queries that have been made in **Scopus**, on November 5, 2014. The first group called *Problems of Elements* (**PE**), and the second group called *Problems of Process* (**PP**)


Group PE
--------

* types OR resources:
	`TITLE-ABS-KEY((resource* OR type*) AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) )`
* metadata:
	`TITLE-ABS-KEY(metadata AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )`
* storage:
	`TITLE-ABS-KEY(storage AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) )`
* cataloging:
	`TITLE-ABS-KEY(catalog* AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"SOCI" ) OR LIMIT-TO(SUBJAREA,"COMP" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) )`
* "controlled vocabular*":
	`TITLE-ABS-KEY("controlled vocabular*" AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"SOCI" ) OR LIMIT-TO(SUBJAREA,"COMP" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) )`
* thesaurus:
	`TITLE-ABS-KEY(thesaurus AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )`
* "abstract entities":
	`TITLE-ABS-KEY("abstract entities" AND problem* AND ("digital librar*" OR "institucional repositor*"))`
* author:
	`TITLE-ABS-KEY(author AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )`
* institution:
	`TITLE-ABS-KEY(institution AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"SOCI" ) OR LIMIT-TO(SUBJAREA,"COMP" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )`
* journal:
	`TITLE-ABS-KEY(journal AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"SOCI" ) OR LIMIT-TO(SUBJAREA,"COMP" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )`
* UNION:
	`TITLE-ABS-KEY((resource* OR type* OR metadata OR storage OR catalog* OR "controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )`

Group PP
--------

### Ingest process:

* `TITLE-ABS-KEY(ingest* AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(ingest* AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(ingest* AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(ingest* AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))`
* `(TITLE-ABS-KEY(ingest* AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(ingest* AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(ingest* AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(ingest* AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*")))`

### Storage process:

* `TITLE-ABS-KEY(storage AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(storage AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(storage AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(storage AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))`
* `(TITLE-ABS-KEY(storage AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(storage AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(storage AND problem* AND (resource* OR type*))AND ("digital librar*" OR "institucional repositor*"))`


### Cataloging process:

* `TITLE-ABS-KEY(cataloging AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(cataloging AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(cataloging AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(cataloging AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))`
* `(TITLE-ABS-KEY(cataloging AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(cataloging AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(cataloging AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(cataloging AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*")))`

### Indexing process:

* `TITLE-ABS-KEY(indexing AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(indexing AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(indexing AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(indexing AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))`
* `(TITLE-ABS-KEY(indexing AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(indexing AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(indexing AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(indexing AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*")))`

### Search Engine process:

* `TITLE-ABS-KEY("search engine" AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY("search engine" AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY("search engine" AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY("search engine" AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))`
* `(TITLE-ABS-KEY("search engine" AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY("search engine" AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY("search engine" AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY("search engine" AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*")))`

### Browsing process:

* `TITLE-ABS-KEY(browsing AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(browsing AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(browsing AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(browsing AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))`
* `TITLE-ABS-KEY(browsing AND problem* AND ("controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))AND (TITLE-ABS-KEY(browsing AND problem* AND storage AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(browsing AND problem* AND metadata AND ("digital librar*" OR "institucional repositor*"))) AND (TITLE-ABS-KEY(browsing AND problem* AND (resource* OR type*) AND ("digital librar*" OR "institucional repositor*")))`
