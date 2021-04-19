# Maintainer: Bruno Goncalves <bigbruno@gmail.com>

pkgname=auto-tweaks-browser
pkgver=1.0.0
pkgrel=0
arch=('any')
license=('GPL')
url="https://github.com/biglinux/auto-tweaks-browser"
pkgdesc="Auto optimize brave, chromium, epiphany, falkon, firefox, google-chrome, opera and vivaldi"
depends=('nosync-browser')
source=("git+https://github.com/biglinux/auto-tweaks-browser.git")
md5sums=(SKIP)


package() {
    cp -r "${srcdir}/auto-tweaks-browser/auto-tweaks-browser/usr/" "${pkgdir}/"
} 
