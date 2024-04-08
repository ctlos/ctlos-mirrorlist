pkgname=ctlos-mirrorlist
pkgver=stable
pkgrel=3
pkgdesc="Ctlos mirrorlist"
arch=('x86_64')
url="https://github.com/ctlos/ctlos-mirrorlist"
license=('GPL3')
# backup=(etc/pacman.d/ctlos-mirrorlist)
source=('ctlos-mirrorlist')
sha256sums=('SKIP')
# install=README.install

package() {
  mkdir -p ${pkgdir}/etc/pacman.d
  install -Dm644 ${srcdir}/${source} ${pkgdir}/etc/pacman.d/
}
