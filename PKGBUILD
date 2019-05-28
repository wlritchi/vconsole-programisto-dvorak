# Maintainer: William Luc Ritchie <luc dot ritchie at gmail dot com>

pkgname=vconsole-programisto-dvorak
pkgver=1.0.0
pkgrel=1
pkgdesc='Dvorak-based console layout for programmers, with Esperanto keys'
arch=('any')
license=('custom')
source=('programisto-dvorak.map'
        'vconsole.conf'
        'UNLICENSE')
sha256sums=('784102a4df1bd87b6c32c70f6508de4520d0822fc07d3993f9a0ba7d1aaf2d58'
            '5785a921d949bfa9657631b0d10d2c9de58f872aacf84c5f33a696c6a09e1ed2'
            '7e12e5df4bae12cb21581ba157ced20e1986a0508dd10d0e8a4ab9a4cf94e85c')

package() {
    cd "$srcdir"
    install -Dm644 'programisto-dvorak.map' "$pkgdir/usr/share/kbd/keymaps/i386/dvorak/programisto-dvorak.map"
    install -Dm644 'vconsole.conf' "$pkgdir/etc/vconsole.conf"
    install -Dm644 'UNLICENSE' "$pkgdir/usr/share/licenses/$pkgname/UNLICENSE"
}
