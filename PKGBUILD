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
    cp -r "${srcdir}/usr/" "${pkgdir}/"
} 

post_install() {
    sed -i 's|/usr/bin/||g' /usr/share/applications/chromium.desktop 2> /dev/null
    sed -i 's|/usr/lib/firefox/||g' /usr/share/applications/firefox.desktop 2> /dev/null
    sed -i 's|/usr/bin/||g' /usr/share/applications/vivaldi-stable.desktop 2> /dev/null
    sed -i 's|/usr/bin/||g' /usr/share/applications/google-chrome.desktop 2> /dev/null
}
