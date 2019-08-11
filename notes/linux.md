# Linux

## Packages
- nvme-cli: NVMe Management tool (https://github.com/linux-nvme/nvme-cli)
- hddtemp

## Virtual Environment for Build
- https://help.ubuntu.com/community/BasicChroot
- https://wiki.debian.org/Schroot

### Summary
1. Edit `/etc/schroot/schroot.conf`
2. Run `debootstrap [distro-name] [target-path]`
3. Run `schroot [target-path]` OR `schroot [schroot-name]`
