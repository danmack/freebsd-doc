# $FreeBSD$

.if exists(../Makefile.conf)
.include "../Makefile.conf"
.endif
.if exists(../Makefile.inc)
.include "../Makefile.inc"
.endif

DOCS=	announce.xml relnotes.xml schedule.xml

DATA=	docbook.css
DATA+=	errata.html
DATA+=	hardware.html
DATA+=	readme.html
DATA+=	relnotes-detailed.html

.include "${DOC_PREFIX}/share/mk/web.site.mk"
