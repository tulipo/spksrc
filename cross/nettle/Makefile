PKG_NAME = nettle
PKG_VERS = 2.7
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = http://www.lysator.liu.se/~nisse/archive/
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/gmp

HOMEPAGE = http://www.lysator.liu.se/~nisse/nettle/
COMMENT  = Nettle is a cryptographic library that is designed to fit easily in more or less any context
LICENSE  = 

GNU_CONFIGURE = 1
CONFIGURE_ARGS = --enable-shared

include ../../mk/spksrc.cross-cc.mk

