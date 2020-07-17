pkgname=ctlos-mirrorlist
pkgver=stable
pkgrel=1
pkgdesc="Ctlos mirrorlist"
arch=('x86_64')
url="https://github.com/ctlos/ctlos-mirrorlist"
license=('GPL3')
backup=(etc/pacman.d/ctlos-mirrorlist)
source=('ctlos-mirrorlist')
sha256sums=('8e9b27fea22b2602ac4873efa8909905927753529225dd30f041e8814e31286e')

package() {
  mkdir -p ${pkgdir}/etc/pacman.d
  install -Dm644 ${srcdir}/${source} ${pkgdir}/etc/pacman.d/
}
