# Maintainer: Akrata

pkgname=akp
pkgver=20250729
pkgrel=1
pkgdesc="A package manager wrapper for pacman, yay and flatpak"
arch=('any')
url="https://github.com/Akr4ta/$pkgname"
license=('GPL3')
depends=(pacman-contrib reflector flatpak expac)
makedepends=(git)
optdepends=('yay: for AUR support')
source=("git+$url.git")
sha256sums=('SKIP')

package() {
	cd "$srcdir/$pkgname"
	install -Dm755 "$pkgname" "$pkgdir/usr/bin/akp"
}
