# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: plasicgaming99 <plsplastic-roblox@protonmail.com>
pkgname=NAME
pkgver=VERSION

pkgrel=
epoch=
pkgdesc="Symlink for Busybox"
arch=('any')
url=""
license=('WTFPL')
depends=('busybox')
makedepends=()
checkdepends=()
optdepends=()
options=()
source=()
noextract=()

build() {
	cd "$pkgname-$pkgver"
	ln -s "/bin/busybox" ""
}

package() {
	cd "$pkgname-$pkgver"
	make DESTDIR="$pkgdir/" install
}
