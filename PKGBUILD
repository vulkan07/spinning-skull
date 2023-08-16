pkgname=spinning-skull
pkgver=1.0
pkgrel=1
pkgdesc="Goofy ahh spinning ascii skull"
arch=('x86_64')
url="https://github.com/vulkan07/spinning-skull"
license=('MIT')
depends=('gcc-libs')

source=("$pkgname-$pkgver.tar.gz::https://github.com/vulkan07/spinning-skull/$pkgname-$pkgver.tar.gz")

build() {
    cd "$srcdir/$pkgname-$pkgver"
}

package() {
    cd "$srcdir/$pkgname-$pkgver"
    install -Dm755 skull "$pkgdir/usr/bin/skull"
}

