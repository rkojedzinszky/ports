# Created by: Bruce Simpson
# $FreeBSD$

PORTNAME=	pyang
PORTVERSION=	1.7.3
CATEGORIES=	net-mgmt python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	bofh@FreeBSD.org
COMMENT=	Validator and code generator for YANG (RFC 4741)

LICENSE=	MIT

USES=		python
USE_PYTHON=	autoplist distutils
NO_ARCH=	yes

DATADIR=	${PREFIX}/share/yang

post-patch:
	@${REINPLACE_CMD} -e \
		's|share/man|man|' ${WRKSRC}/setup.py

.include <bsd.port.mk>
