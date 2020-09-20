# Maintainer: Your Name <brilliant@koompi.org>
pkgname=koompi-maintenance
pkgver="0.1"
pkgrel=1
pkgdesc="Simple linux system maintenance tool for KOOMPI OS"
arch=('any')
url="https://github.com/koompi/os-maintenance-tools"
license=('MIT')

package() {
    install -Dm644 "$srcdir/LICENSE" "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
    install -Dm644 "$srcdir/usr/share/polkit-1/actions/org.koompi.os.maintenance.policy" "$pkgdir/usr/share/polkit-1/actions/org.koompi.os.maintenance.policy"
    install -Dm644 "$srcdir/usr/bin/koompi_maintenance" "$pkgdir/usr/bin/koompi_maintenance"
    install -Dm644 "$srcdir/etc/polkit-1/rules.d/koompi-maintence.rules" "$pkgdir/etc/polkit-1/rules.d/koompi-maintence.rules"
}
