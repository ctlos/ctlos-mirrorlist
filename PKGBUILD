pkgname=ctlos-mirrorlist
pkgver=stable
pkgrel=1
pkgdesc="Ctlos mirrorlist"
arch=('x86_64')
url="https://github.com/ctlos/ctlos-mirrorlist"
license=('GPL3')
backup=(etc/pacman.d/ctlos-mirrorlist)
source=('ctlos-mirrorlist')
sha256sums=('8d2912260cfc4ef0e4e0bf514c21a9557ad0400e8c9060767e2727d083e5de19')

package() {
  mkdir -p ${pkgdir}/etc/pacman.d
  install -Dm644 ${srcdir}/${source} ${pkgdir}/etc/pacman.d/
}
