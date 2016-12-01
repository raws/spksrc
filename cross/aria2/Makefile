PKG_NAME = aria2
PKG_VERS = 1.29.0
PKG_EXT = tar.gz
PKG_DIST_NAME = $(PKG_NAME)-$(PKG_VERS).$(PKG_EXT)
PKG_DIST_SITE = https://github.com/aria2/aria2/releases/download/release-$(PKG_VERS)
PKG_DIR = $(PKG_NAME)-$(PKG_VERS)

DEPENDS = cross/c-ares cross/gnutls cross/libssh2 cross/libxml2 cross/sqlite cross/zlib

HOMEPAGE = https://aria2.github.io
COMMENT = A lightweight multi-protocol & multi-source command-line download utility.
LICENSE = GPLv2

GNU_CONFIGURE = 1

include ../../mk/spksrc.cross-cc.mk
