# Maintainer: schalox < schalox at gmail dot com >

pkgname=bwman
pkgver=1.0a
pkgrel=1
pkgdesc='Password manager using bash and gpg'
arch=('any')
license=('schalox')
groups=('own')
depends=('bash' 'coreutils' 'file' 'gawk' 'gnupg' 'grep' 'xsel')
source=("$pkgname"
        "${pkgname}.1"
        "${pkgname}.conf")

package() {
    install -D -m755 "$pkgname" "${pkgdir}/usr/bin/${pkgname}"
    install -D -m644 "${pkgname}.1" "${pkgdir}/usr/share/man/man1/${pkgname}.1"
    install -D -m644 "${pkgname}.conf" "${pkgdir}/etc/${pkgname}.conf"
}
sha256sums=('ddf8aaf72730b9a2678afc1b198931cc0b5ed6d82456d7a49842232e94c7b350'
            'd93d2d0b872ff3a919336c67fb201107963299df6a84314b1ed47f587499f927'
            '5350bddee0c7d3ee0fd54c0adfd025deec73178df24670d0f2599a4da5228474')
sha256sums=('655ed8891892653fcdd32a12463feef2acd64bae7f99d4c7c080e116b2c18e62'
            'd93d2d0b872ff3a919336c67fb201107963299df6a84314b1ed47f587499f927'
            'd5fa971f83a5d43f6aff7660d3377ddf080fb7d83076b513f73572cac1cbc1ae')
