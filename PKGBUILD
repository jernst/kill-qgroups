developer=http://upon2020.com/
url="https://github.com/jernst/kill-cgroups"
maintainer=$developer
pkgname=$(basename $(pwd))
pkgver=0.1
pkgrel=1
pkgdesc="Kill off and disable btrfs qgroups if they keep reappearing"
arch=( 'any' )
license=('AGPL3')

package() {
    install -D -m755 ${startdir}/kill-qgroups ${pkgdir}/usr/bin/kill-qgroups
}

