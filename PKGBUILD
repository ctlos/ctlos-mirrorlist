pkgname=ctlos-mirrorlist
pkgver=stable
pkgrel=1
pkgdesc="Ctlos mirrorlist"
arch=('x86_64')
url="https://github.com/ctlos/ctlos-mirrorlist"
license=('GPL3')
backup=(etc/pacman.d/ctlos-mirrorlist)
source=('ctlos-mirrorlist')
sha256sums=('cfdced50192944c6e66648d0dd40cdddbeddb1ef3c4cefbecd29569ea1cb7d80')

package() {
  mkdir -p ${pkgdir}/etc/pacman.d
  install -Dm644 ${srcdir}/${source} ${pkgdir}/etc/pacman.d/
}
