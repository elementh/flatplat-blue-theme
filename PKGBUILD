# Maintainer: elementh <lucasmmarino@icloud.com>
pkgname=flatplat-blue-theme
pkgrel=1
pkgver=3.26.2
pkgdesc="A Material Design-like flat theme for GTK3, GTK2, and GNOME-Shell."
arch=('any')
url="https://github.com/peterychuang/Flat-Plat-Blue"
license=('GPL2')
depends=('gtk3>=3.22' 'gtk-engine-murrine' 'gnome-themes-standard')
optdepends=()
provides=('flatplat-blue-theme')
conflicts=()
replaces=()
source=(Flat-Plat-Blue-3.26.2::"https://github.com/peterychuang/Flat-Plat-Blue/archive/3.26.2.tar.gz")
sha256sums=('8e4c6ee09591f0516d70b71fb8755cfa4bde7d09b8883a69701937f33aa88a24')

package() {
  cd "${srcdir}/Flat-Plat-Blue-3.26.2"
  destdir="${pkgdir}" ./install.sh
}
