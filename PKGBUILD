# Author: Mikolaj Nowak <ivan.legnica@gmail.com>

pkgname=xpong
pkgver=1.1.2
pkgrel=1
pkgdesc="A popular pong game"
arch=('i686' 'x86_64')
depends=('sfml>=1.99')
url="http://ivan1pl.cba.pl/page/projects/xpong"
license=(GPL)
source=(http://ivan1pl.cba.pl/$pkgname-$pkgver.tar.gz)

build() { 
  cd $srcdir/$pkgname-$pkgver
  make 
}

package() {
  cd $srcdir/$pkgname-$pkgver
  make DEST=$pkgdir install
}

md5sums=('2342ab199d851441ff40e0bffa5a0323')
