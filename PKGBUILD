# Maintainer: lobotomius@gmail.com

pkgname=ideserv
pkgver=0.24
pkgrel=1
pkgdesc="ide64 file server for idedos 0.90"
arch=('i686' 'x86_64')
url='http://singularcrew.hu/ide64warez/index2.php?menu=pctoolz'
license=('GPL')
source=('http://singularcrew.hu/ide64warez/site/other-OS/Unix/ideserv-024_150209.zip')
md5sums=('f6eecdd58d7e86ea04518dcf2a6d5b4c')

build() {
  cd "$srcdir/ideserv-0.24_150209/src"
  make
}

check() {
  :
}

package() {
  cd "$srcdir/ideserv-0.24_150209/src"
  mkdir -p "$pkgdir/usr/bin"
  install -t "$pkgdir/usr/bin/" ideservd
}

# vim:set ts=2 sw=2 et:
