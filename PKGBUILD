# Maintainer: Sven-Hendrik Haase <sh@lutzhaase.com>

pkgname=cowsay-futurama
pkgver=1
pkgrel=4
pkgdesc="Cowsay art for Fry, Bender, Leela, Dr. Zoidberg and Hypnotoad."
arch=('any')
url="http://www.nog.net/~tony/warez/cowsay.shtml"
license=('CCPL')
depends=('cowsay')
source=(http://dl.dropboxusercontent.com/u/4776753/${pkgname}.tar.bz2)
md5sums=('43febfcd13cc4da2022c0ccd84d446b0')

package() {
  install -Dm644 ${srcdir}/bender.cow ${pkgdir}/usr/share/cows/bender.cow
  install -Dm644 ${srcdir}/fry.cow ${pkgdir}/usr/share/cows/fry.cow
  install -Dm644 ${srcdir}/hypnotoad.cow ${pkgdir}/usr/share/cows/hypnotoad.cow
  install -Dm644 ${srcdir}/leela.cow ${pkgdir}/usr/share/cows/leela.cow
  install -Dm644 ${srcdir}/zoidberg.cow ${pkgdir}/usr/share/cows/zoidberg.cow
}
