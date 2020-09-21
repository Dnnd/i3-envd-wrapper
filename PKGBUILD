# Maintainer: Danila Maslennikov <d.v.maslennikov@outlook.com>
pkgname=i3-envd
pkgver=1.0.1
pkgrel=1
pkgdesc="Wrapper to load env variables in i3 session"
arch=("any")
url="https://github.com/Dnnd/i3-envd-wrapper"
license=('MIT')
depends=("i3-wm")
provides=("${pkgname%}")
conflicts=("${pkgname%}")
source=("i3-envd-wrapper"
	"i3-envd.desktop")
md5sums=('SKIP'
	 'SKIP')

package() {
	install -Dm755 "$srcdir/i3-envd-wrapper" "$pkgdir/usr/bin/i3-envd-wrapper"
	install -Dm644 "$srcdir/i3-envd.desktop" "$pkgdir/usr/share/xsessions/i3-envd.desktop"
}
