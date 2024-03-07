# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-wallpapers
pkgver=2.0
pkgrel=1
pkgdesc='Kawaii walpapers.'
groups=('kawaii')
url='https://github.com/LeonidPilyugin/kawaii-wallpapers'
arch=('x86_64')
license=('GPL3')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('dd41c87c8f47d3cfff1976ed0a0782aed30ee4fe7b1fa128b9d95561f50c72a8')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/wallpapers
    install -dm755 $dir/
    cp -r $srcdir/* $dir/
}

