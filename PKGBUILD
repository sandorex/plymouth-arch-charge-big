pkgname=plymouth-theme-arch-charge-white
pkgver=20190326
pkgrel=1
pkgdesc="Plymouth theme like fedora but with an Arch logo."
arch=('any')
url="https://github.com/sandorex/plymouth-theme-arch-charge-white"
license=('GPL')
depends=('plymouth')
md5sums=('SKIP')
source=('git+git://github.com/sandorex/plymouth-theme-arch-charge-white')
install='plymouth-theme-arch-charge-white.install'

package() {
    cd $srcdir/${pkgname}
    mkdir -p $pkgdir/usr/share/plymouth/themes/arch-charge-white
    install -Dm644 arch-charge-white/* "${pkgdir}"/usr/share/plymouth/themes/arch-charge-white
}
