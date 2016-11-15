## Contributing

Please run `reposetup.sh` prior to committing. This will install a git hook
that will automatically re-generate `PKGBUILD` and `.SRCINFO` as needed
before the commit completes.

To install :
$ git clone https://github.com/Paullux/archlinux-amdgpu
$ cd archlinux-amdgpu
$ makepkg -sri

To uninstall :
$ cd archlinux-amdgpu
$ ./amdgpu-pro-uninstaller
