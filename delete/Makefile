# $FreeBSD: stable/10/usr.sbin/pkg_install/delete/Makefile 222035 2011-05-17 19:11:47Z flz $

PROG=	pkg_delete
SRCS=	main.c perform.c

CFLAGS+= -I${.CURDIR}/../lib

WARNS?=		6
WFORMAT?=	1

DPADD=	${LIBINSTALL} ${LIBMD}
LDADD=	${LIBINSTALL} -lmd

.include <bsd.prog.mk>
