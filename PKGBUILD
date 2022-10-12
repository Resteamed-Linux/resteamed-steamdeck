# Maintainer: Your Name <youremail@domain.com>
pkgname=resteamed-steamdeck
pkgver=0.1
pkgrel=1
pkgdesc="Device specific files"
arch=('any')
url="https://github.com/Kevadroz/resteamed-steamdeck"
license=('GPL3')
depends=()
source=("$pkgname-$pkgver::https://github.com/Resteamed-Linux/$pkgname/releases/download/v$pkgver/resteamed-steamdeck-$pkgver-tarball.tar.gz")

package() {
	cp -r "$srcdir/usr" "$srcdir/etc" "$pkgdir/"
	chmod 644 -R "$pkgdir/etc/sddm.conf.d/"
	chmod 755 -R "$pkgdir/usr/share/X11/xorg.conf.d/"
}

sha256sums=('39a6f3331a2e998da02b28002076683a26cd1d73466b07c1d5940408a4e51df4')
