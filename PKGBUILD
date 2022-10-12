# Maintainer: Kevadroz <kevinfdezdominguez@gmail.com>
pkgname=resteamed-core
pkgver=0.1
pkgrel=1
pkgdesc='Utilities for other resteamed packages'
arch=('any')
url="https://github.com/Kevadroz/resteamed-core"
license=('GPL3')
depends=()
source=("$pkgname-$pkgver::file:///home/kevin/Proyectos/Agrupaciones/Resteamed/ArchPackages/$pkgname/$pkgname.tar.gz")

package() {
	cp -r "$srcdir/usr" "$srcdir/etc" "$pkgdir/"
	chmod 755 -R "$pkgdir/usr/"
	chmod 644 -R "$pkgdir/etc/systemd/logind.conf.d"
}

sha256sums=('5455123986560ca48c545a3ad44fad1692776c867c7cc228835b08a5fb3cb6e0')
