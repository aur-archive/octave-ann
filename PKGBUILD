_pack=ann
pkgname=octave-$_pack
pkgver=1.0.2
pkgrel=1
pkgdesc="The Octave-forge ANN package wraps the ANN library, which provides data structures and functions for computing exact and approximate nearest neighbors on an arbitrarily high dimensional point set."
arch=('i686' 'x86_64')
url="http://octave.sourceforge.net/$_pack/index.html"
license=('GPL')
depends=('octave>=2.9.12')
makedepends=()
optdepends=()
backup=()
options=()
install=$pkgname.install
source=("http://downloads.sourceforge.net/octave/$_pack-$pkgver.tar.gz")
noextract=("$_pack-$pkgver.tar.gz")
md5sums=('3b383fdec459cf4f66c221e7b698aab0')

build() {
  cd "$srcdir"
  mkdir -p $pkgdir/usr/share/octave/packages
  mkdir -p $pkgdir/usr/lib/octave/packages
  cp $_pack-$pkgver.tar.gz $pkgdir/usr/share/octave/$_pack.tar.gz
}