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
sha256sums=('a3421e0db16e3bf12cdf9ea98b59d29f30a5725c4b44dcbf136fef14d286efc7'
            'd93d2d0b872ff3a919336c67fb201107963299df6a84314b1ed47f587499f927'
            '56a398e26ca6d34786db31cd9e169ffb1dea72b5586de3b4490613090accb000')
