# Maintainer: kumax <>
pkgname=biliup-app-bin
pkgver=0.3.3
pkgrel=1
pkgdesc="Bilibili uploader, supports Windows, Linux, macOS."
arch=("x86_64")
url="https://github.com/ForgQi/biliup-app"
provides=("${pkgname%-bin}")
conflicts=("${pkgname%-bin}")
depends=("gtk3" "webkit2gtk")
source=("biliup-app_${pkgver}_amd64.deb::https://github.com/ForgQi/biliup-app/releases/download/app-v${pkgver}/biliup-app_${pkgver}_amd64.deb")
sha256sums=('16bf2e63531c05ad913a554273387bbe529c795b9da5e163618d1d5001bbdf06')

package() {
	tar xvf "${srcdir}/data.tar.gz" -C "${pkgdir}"
}
