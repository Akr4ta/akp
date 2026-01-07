# Maintainer: Akrata

pkgname=akp
pkgver=20251210
pkgrel=1
pkgdesc="A package manager wrapper for pacman, yay and flatpak"
arch=('any')
url="https://github.com/Akr4ta/$pkgname"
license=('GPL3')
depends=(bash pacman-contrib expac gawk ncurses)
makedepends=(git)
optdepends=(
	'yay: for AUR support'
	'flatpak: for Flatpak support'
	)
source=("git+$url.git")
sha256sums=('SKIP')

package() {
	cd "$srcdir/$pkgname"
	install -Dm755 "$pkgname" "$pkgdir/usr/bin/akp"
}
