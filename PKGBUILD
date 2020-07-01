pkgname=ctlos-mirrorlist
pkgver=$(date +%Y%m%d)
pkgrel=1
pkgdesc="Ctlos mirrorlist"
arch=('any')
url="https://github.com/ctlos/ctlos-mirrorlist"
license=('GPL3')
backup=(etc/pacman.d/ctlos-mirrorlist)
source=('ctlos-mirrorlist')
sha256sums=('b690c63bb3f838b7c34590e1426b03ac76b2871d8d22666d898327b058cf46d6')

package() {
  mkdir -p ${pkgdir}/etc/pacman.d
  install -Dm644 ${srcdir}/${source} ${pkgdir}/etc/pacman.d/ctlos-mirrorlist
}
