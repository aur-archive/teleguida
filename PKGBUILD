# Manteiner: Elia Notarangelo < elia dot notarangelo at gmail dot com>

pkgname=teleguida
pkgver=0.2
pkgrel=1
pkgdesc="programmi serali in tv"
arch=('any')
url="http://www.xfce-italia.it/index.php?topic=1045.0"
license=('GPL')
depends=()
source=("http://master.dl.sourceforge.net/project/archmind/$pkgname-$pkgver.tar.gz")


build() {
	cd ${srcdir}/${pkgname}-${pkgver}

	BIN_DIR=${pkgdir}/usr/bin
	CONFIG_DIR=${pkgdir}/usr/share/${pkgname}
	ICON_DIR=${pkgdir}/usr/share/icons
	DESK_DIR=${pkgdir}/usr/share/applications

	install -d ${BIN_DIR} ${CONFIG_DIR} ${ICON_DIR} ${DESK_DIR}

	install -D COPYING ${CONFIG_DIR}
	install -D teleguida.desktop ${DESK_DIR}
	install -D teleguida-logo.png ${ICON_DIR}
	install -D teleguida ${BIN_DIR}
}

md5sums=('7d272bf19330cb6bcb259f9647e0e237')
