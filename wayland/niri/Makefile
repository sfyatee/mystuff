COMMENT=		a scrollable-tiling Wayland compositor

GH_ACCOUNT =		YaLTeR
GH_PROJECT =		niri
GH_TAGNAME =		v0.1.7

CATEGORIES =		wayland

# GPLv3
PERMIT_PACKAGE = 	Yes

MODULES =		devel/cargo

LIB_DEPENDS =		devel/pango \
			sysutils/seatd \
			wayland/libinput-openbsd \
			wayland/libudev-openbsd \
			x11/xkbcommon

WANTLIB =		cairo pango-1.0 pixman-1 xkbcommon

post-install:
	${INSTALL_DATA_DIR} ${PREFIX}/share/examples/niri

.include <bsd.port.mk>
