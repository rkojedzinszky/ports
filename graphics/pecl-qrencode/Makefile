# Created by: vanilla
# $FreeBSD$

PORTNAME=	qrencode
PORTVERSION=	0.6
DISTVERSIONPREFIX=	v
CATEGORIES=	graphics pear
PKGNAMEPREFIX=	pecl-
DIST_SUBDIR=	PECL

MAINTAINER=	vanilla@FreeBSD.org
COMMENT=	PECL extension for generate qrcode

LICENSE=	BSD2CLAUSE

LIB_DEPENDS=	libqrencode.so:graphics/libqrencode \
		libpng16.so:graphics/png

USES=		php:ext
USE_GITHUB=	yes
GH_ACCOUNT=	vanillahsu
GH_PROJECT=	pecl-qrencode

.include <bsd.port.mk>
