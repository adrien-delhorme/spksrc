PKG_NAME = boto
PKG_SHORT_VERS = 2.38
PKG_VERS = $(PKG_SHORT_VERS).0
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = https://github.com/$(PKG_NAME)/$(PKG_NAME)/archive
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

#DEPENDS = cross/librsync

HOMEPAGE = https://github.com/boto
COMMENT  = A Python interface to Amazon Web Services
LICENSE  = MIT License

include ../../mk/spksrc.python-wheel.mk
