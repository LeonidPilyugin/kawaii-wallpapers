# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-wallpapers
pkgver=1.2
pkgrel=1
pkgdesc='Kawaii walpapers.'
arch=('x86_64')
license=('GPL3')
groups=('kawaii')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('28b3077e86576a463cd550ac808003be39d06c9f78e9322cac878d31c7513cba')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/wallpapers
    install -dm755 $dir/
    cp -r $srcdir/* $dir/
}

