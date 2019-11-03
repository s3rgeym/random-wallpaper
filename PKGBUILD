pkgname=random-wallpaper
pkgver=0.1.0
pkgrel=1
pkgdesc='Changes the desktop wallpaper to random from the site wallhaven.cc'
arch=('any')
url='https://githib.com/tz4678'
license=('MIT')
depends=('jq')
source=($pkgname{,.{service,timer}})
md5sums=('SKIP')

package() {
  cd $srcdir
  install -Dm755 $pkgname $pkgdir/usr/bin/$pakgname
  install -Dm644 $pkgname.service $pkgdir/usr/lib/systemd/system/$pakgname.service
  install -Dm644 $pkgname.timer $pkgdir/usr/lib/systemd/system/$pakgname.timer
}
