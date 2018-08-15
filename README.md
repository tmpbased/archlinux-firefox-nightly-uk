git clone https://github.com/zVcXr/archlinux-firefox-nightly-uk.git firefox-nightly

cd firefox-nightly

makepkg -s

makepkg --printsrcinfo > .SRCINFO
