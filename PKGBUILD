pkgname='upgradeall'
pkgdesc='A script for auto-upgrading all softwares.'
pkgver='0.1.0'
pkgrel='1'
url='https://github.com/GNUqb114514/upgradeall'
license=('LGPL-2.1-or-later')
source=("./upgradeall.sh")
md5sums=("SKIP")
arch=(any)
depends=('paru' 'flatpak')

package () {
	mkdir -p $pkgdir/usr/bin
	install $srcdir/upgradeall.sh $pkgdir/usr/bin/upgradeall
}