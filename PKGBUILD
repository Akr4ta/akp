# Maintainer: Akrata

pkgname=akp
pkgver=20241120
pkgrel=1
pkgdesc="A package manager wrapper for pacman, yay and flatpak"
arch=('any')
url="https://github.com/Akr4ta/$pkgname"
license=('GPL3')
depends=(pacman-contrib reflector flatpak)
makedepends=(git)
source=("git+$url.git")
sha256sums=('SKIP')
install=$pkgname.install

package() {
	cd "$srcdir/$pkgname"
	install -Dm755 "$pkgname" "$pkgdir/usr/bin/akp"
}

#PGP
#SSH
#https://wiki-archlinux-org.translate.goog/title/AUR_submission_guidelines?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt-BR&_x_tr_pto=wapp
#https://wiki-archlinux-org.translate.goog/title/SSH_keys?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt-BR&_x_tr_pto=wapp
