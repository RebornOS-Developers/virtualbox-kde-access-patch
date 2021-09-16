# Maintainer: Rafael <rafael@rebornos.org>
# Copy virtualbox-kde.desktop adapted for KDE in /usr/share/applications

pkgname=virtualbox-kde-access-patch
deskname=virtualbox-kde.desktop
pkgver=0.1
pkgrel=1.3
pkgdesc='New shortcut for VirtualBox that fixes the file selection dialog problem'
arch=('any')
url='https://github.com/RebornOS-Developers'
license=('GPL3')
source=("${deskname}")
sha512sums=('a3119c538dc9f5b875924f5d10db789511c0f518556aca14c6a3c46d991cafc7805cf5956bf7bfc5d95239ae2e4191554eecb7246e5e9bb301e3b226c85a0add')

package() {
    mkdir -p ${pkgdir}/usr/share/applications
    install -D -m 644 ${deskname} ${pkgdir}/usr/share/applications
    }

