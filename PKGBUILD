pkgname=mozc-configration-tools
pkgver=2.28.4715.102
pkgrel=1
pkgdesc="Audio and MIDI Workstation (DAW)"
arch=('x86_64' 'aarch64')
url="https://packages.ubuntu.com/search?keywords=mozc-utils-gui"
license=('custom')
depends=('qt5-base' 'fcitx5')
source_aarch64=(http://th.archive.ubuntu.com/ubuntu/pool/universe/m/mozc/mozc-utils-gui_2.28.4715.102+dfsg-2.2build1_amd64.deb)
source_x86_64=(http://th.archive.ubuntu.com/ubuntu/pool/universe/m/mozc/mozc-utils-gui_2.28.4715.102+dfsg-2.2build1_amd64.deb)
sha256sums_x86_64=('0f3b1059c4c57c12b71da54f00017fdf659306f7061099acee91c8902d83884d')
sha256sums_aarch64=('0f3b1059c4c57c12b71da54f00017fdf659306f7061099acee91c8902d83884d')

package() {
    ar vx mozc-utils-gui_2.28.4715.102+dfsg-2.2build1_amd64.deb
    tar -xvf control.tar.zst
    tar -xvf data.tar.zst
}
