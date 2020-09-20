# Maintainer: Your Name <brilliant@koompi.org>
pkgname=koompi-maintenance
pkgver="0.1"
pkgrel=1
pkgdesc="Simple linux system maintenance tool for KOOMPI OS"
arch=('any')
url="https://github.com/koompi/os-maintenance-tools"
license=('MIT')
provides=('koompi-maintenance')
package() {
    install -Dm644 "$srcdir/LICENSE" "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
    install -Dm644 "$srcdir/usr/share/polkit-1/actions/org.koompi.os.maintenance.policy" "$pkgdir/usr/share/polkit-1/actions/org.koompi.os.maintenance.policy"
    install -Dm775 "$srcdir/usr/bin/koompi-maintenance" "$pkgdir/usr/bin/koompi-maintenance"
    install -Dm644 "$srcdir/etc/polkit-1/rules.d/koompi-maintenance.rules" "$pkgdir/etc/polkit-1/rules.d/koompi-maintenance.rules"
}
