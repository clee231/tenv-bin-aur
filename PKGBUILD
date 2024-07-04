# Maintainer: Chase 李 <aur@chase.ninja>

pkgname=tenv-bin
pkgver=2.3.0
pkgrel=1
pkgdesc="OpenTofu / Terraform / Terragrunt and Atmos version manager"
arch=('x86_64' 'i386' 'armv6' 'arm64')
url="https://github.com/tofuutils/tenv"
license=('Apache-2.0')
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=('cosign: package validation for OpenTofu')
provides=("atmos" "tenv" "terraform" "terragrunt" "tf" "tofu")
conflicts=('atmos' 'atmos-bin' 'opentofu' 'opentofu-bin' 'opentofu-bin-stable' 'opentofu-git' 'terraform' 'terragrunt' 'tfenv' 'tgenv' 'tofuenv')
replaces=()
backup=()
options=()
install=
changelog=
source_x86_64=("https://github.com/tofuutils/tenv/releases/download/v${pkgver}/tenv_v${pkgver}_Linux_x86_64.tar.gz")
source_i386=("https://github.com/tofuutils/tenv/releases/download/v${pkgver}/tenv_v${pkgver}_Linux_i386.tar.gz")
source_armv6=("https://github.com/tofuutils/tenv/releases/download/v${pkgver}/tenv_v${pkgver}_Linux_armv6.tar.gz")
source_arm64=("https://github.com/tofuutils/tenv/releases/download/v${pkgver}/tenv_v${pkgver}_Linux_arm64.tar.gz")
noextract=()
md5sums=()

package() {
  install -Dm 0755 "atmos" "${pkgdir}/usr/bin/atmos"
  install -Dm 0755 "tenv" "${pkgdir}/usr/bin/tenv"
  install -Dm 0755 "terraform" "${pkgdir}/usr/bin/terraform"
  install -Dm 0755 "terragrunt" "${pkgdir}/usr/bin/terragrunt"
  install -Dm 0755 "tf" "${pkgdir}/usr/bin/tf"
  install -Dm 0755 "tofu" "${pkgdir}/usr/bin/tofu"
  install -Dm 0644 "LICENSE" "${pkgdir}/usr/share/doc/tenv/LICENSE"
  install -Dm 0644 "README.md" "${pkgdir}/usr/share/doc/tenv/README.md"
}

sha256sums_x86_64=('e8589786bedf3a70c247d579d2f48b6c75f6e06feb3355e4d32ac107a6410d01')
sha256sums_i386=('0719c18c34aa5e1d8504aabb6c3a5407f86acb37779476062459cff38db32a29')
sha256sums_armv6=('aba4d65d06308176527970e5d368a50fcad2d976fa416e69cff685f767c207d8')
sha256sums_arm64=('8f6b85e80eff826200c750cd47d57da485c9a9e98d81596815eff5e7c6f74052')
