pkgname=docker-credential-gcr-bin
_pkgname=docker-credential-gcr
pkgver=2.0.4
pkgrel=1
pkgdesc='Standalone gcloud SDK-independent Docker credential helper.'
arch=('x86_64')
license=('Apache')
url="https://github.com/GoogleCloudPlatform/$_pkgname"
source_x86_64=("$url/releases/download/v$pkgver/${_pkgname}_linux_amd64-$pkgver.tar.gz")
sha256sums_x86_64=('4fca8441c41802f4bcc4912672c55d4b1232decb90639f8a684d3b389e4e6e91')
package() {
  install -Dm755 "${srcdir}/${_pkgname}" "${pkgdir}/usr/bin/${_pkgname}"
}
