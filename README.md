ReviewRR
========

Review of the resource representation in institutional repository

Group PE
--------

* types OR resources:
	`TITLE-ABS-KEY((resource* OR type*) AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) )`
* metadata:
	`TITLE-ABS-KEY(metadata AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )`
* storage:
	TITLE-ABS-KEY(storage AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) )
* cataloging:
	TITLE-ABS-KEY(catalog* AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"SOCI" ) OR LIMIT-TO(SUBJAREA,"COMP" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) )
* "controlled vocabular*":
	TITLE-ABS-KEY("controlled vocabular*" AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"SOCI" ) OR LIMIT-TO(SUBJAREA,"COMP" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) )
* thesaurus:
	TITLE-ABS-KEY(thesaurus AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )
* "abstract entities":
	TITLE-ABS-KEY("abstract entities" AND problem* AND ("digital librar*" OR "institucional repositor*"))
* author:
	TITLE-ABS-KEY(author AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"COMP" ) OR LIMIT-TO(SUBJAREA,"SOCI" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )
* institution:
	TITLE-ABS-KEY(institution AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"SOCI" ) OR LIMIT-TO(SUBJAREA,"COMP" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )
* journal:
	TITLE-ABS-KEY(journal AND problem* AND ("digital librar*" OR "institucional repositor*")) AND ( LIMIT-TO(DOCTYPE,"ar" ) OR LIMIT-TO(DOCTYPE,"re" ) ) AND ( LIMIT-TO(SUBJAREA,"SOCI" ) OR LIMIT-TO(SUBJAREA,"COMP" ) ) AND ( LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital libraries" ) OR LIMIT-TO(EXACTKEYWORD,"Digital library" ) )


Group PP
--------

### Ingest process

* TITLE-ABS-KEY((load* OR ingest*) AND ("digital librar*" OR "institucional repositor*"))
* TITLE-ABS-KEY((workflow* OR ingest*) AND (resource* OR type* OR metadata OR storage OR catalog* OR "controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*"))
* TITLE-ABS-KEY(ingest* AND problem* AND (resource* OR type* OR metadata OR storage OR catalog* OR "controlled vocabular*" OR thesaurus OR "abstract entities" OR author OR institution OR journal) AND ("digital librar*" OR "institucional repositor*")) 

