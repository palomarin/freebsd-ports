# $FreeBSD$

PORTNAME=	pydantic
DISTVERSION=	0.28
CATEGORIES=	devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	yuri@FreeBSD.org
COMMENT=	Data validation and settings management using python 3.6 type hinting

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE

py36_RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}dataclasses>=0.6:devel/py-dataclasses@${PY_FLAVOR}

USES=		python:3.6+
USE_PYTHON=	distutils autoplist

NO_ARCH=	yes

.include <bsd.port.mk>
