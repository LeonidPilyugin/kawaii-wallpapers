# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-wallpapers
pkgver=1.3
pkgrel=1
pkgdesc='Kawaii walpapers.'
groups=('kawaii')
url='https://github.com/LeonidPilyugin/kawaii-wallpapers'
arch=('x86_64')
license=('GPL3')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('32f30c52febd24c413390895ecd41e1dfa212aa96b81e49d38bb0ba7dc8fabb0')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/wallpapers
    install -dm755 $dir/
    cp -r $srcdir/* $dir/
}

