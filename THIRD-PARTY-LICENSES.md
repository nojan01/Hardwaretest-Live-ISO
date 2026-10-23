# Drittsoftware und Lizenzen

Das ISO enthält die folgenden Pakete. Jedes Paket steht unter seiner eigenen Lizenz;
der vollständige Text liegt im System unter `/usr/share/doc/<paket>/copyright`.
Quellcode: `apt source <quellpaket>=<version>` oder https://snapshot.debian.org/

Zusätzlich enthält das Hardwaretest-Paket:

- **Prime95/mprime** (GIMPS, freeware) – Lizenz: https://www.mersenne.org/legal/ (`/opt/hardwaretest/_internal/vendor/prime95/license.txt`)
- **Qt 6 / PySide6** – LGPL-3.0 (https://www.qt.io/licensing/)
- **Python** – PSF License
- **NVIDIA-Treiber 595** (nvidia-driver-cuda, libcuda1, firmware-nvidia-gsp u. a.) – proprietäre NVIDIA-Lizenz, laut Debian (non-free) frei weitergebbar; Kernelmodul: Open-Kernelmodul (MIT/GPL-2)

| Paket | Version | Quellpaket | Lizenz(en) laut copyright |
|---|---|---|---|
| adduser | 3.152 | adduser | GPL-2+ |
| adwaita-icon-theme | 48.1-1 | adwaita-icon-theme | CC-BY-3.0-US, CC-BY-SA-2.0-IT, CC-BY-SA-3.0 or LGPL-3, and CC-BY-SA-4.0, CC-BY-SA-3.0-US, CC-BY-SA-3.0-US or LGPL-3, CC- |
| apt | 3.0.3 | apt | BSD-3-clause, Expat, GPL-2, GPL-2+, GPL-2+ and curl, curl |
| apt-utils | 3.0.3 | apt | BSD-3-clause, Expat, GPL-2, GPL-2+, GPL-2+ and curl, curl |
| at-spi2-common | 2.56.2-1+deb13u2 | at-spi2-core | AFL-2.1, AFL-2.1 or GPL-2+, GPL-2, GPL-2+, LGPL-2+, LGPL-2.1+, public-domain |
| base-files | 13.8+deb13u7 | base-files | GPL-2+, verbatim |
| base-passwd | 3.6.7 | base-passwd | GPL-2, public-domain |
| bash | 5.2.37-2+b10 | bash | BSD-4-clause-UC, BSD-4-clause-UC and MIT-like, GFDL-NIV-1.3, GPL-2+, GPL-3+, GPL-3+ with Bison exception, Latex2e, MIT-l |
| bash-completion | 1:2.16.0-7 | bash-completion | GPL-2+ |
| binutils | 2.44-3 | binutils | siehe /usr/share/doc/binutils/copyright |
| binutils-common | 2.44-3 | binutils | siehe /usr/share/doc/binutils-common/copyright |
| binutils-x86-64-linux-gnu | 2.44-3 | binutils | siehe /usr/share/doc/binutils-x86-64-linux-gnu/copyright |
| bsdutils | 1:2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| btop | 1.3.2-0.1 | btop | Apache-2.0, Expat |
| bubblewrap | 0.12.0-1~deb13u1 | bubblewrap | LGPL-2+, LGPL-2+ and LGPL-2.1+, LGPL-2.1+, pd-bubblewrap.jpg |
| busybox | 1:1.37.0-6+b9 | busybox | This package is free software; you can redistribute it and/or modify |
| bzip2 | 1.0.8-6 | bzip2 | BSD-variant, GPL-2 |
| ca-certificates | 20250419+deb13u1 | ca-certificates | GPL-2+, MPL-2.0 |
| console-setup | 1.242~deb13u1 | console-setup | siehe /usr/share/doc/console-setup/copyright |
| console-setup-linux | 1.242~deb13u1 | console-setup | siehe /usr/share/doc/console-setup-linux/copyright |
| coreutils | 9.7-3 | coreutils | BSD-4-clause-UC, FSFULLR, GFDL-NIV-1.3, GPL-3+, GPL-3+ and BSD-4-clause-UC, GPL-3+ and ISC, ISC |
| cpio | 2.15+dfsg-2 | cpio | GPL-3+, LGPL-3+ |
| cron | 3.0pl1-197 | cron | Artistic, GPL-1+, GPL-1+ or Artistic, GPL-2+, ISC, Paul-Vixie's-license, Paul-Vixie's-license and GPL-2+ and ISC |
| cron-daemon-common | 3.0pl1-197 | cron | Artistic, GPL-1+, GPL-1+ or Artistic, GPL-2+, ISC, Paul-Vixie's-license, Paul-Vixie's-license and GPL-2+ and ISC |
| curl | 8.14.1-2+deb13u7 | curl | BSD-3-Clause, BSD-3-clause, BSD-4-Clause-UC, FSFULLR, GPL-2+ with Autoconf-data exception, GPL-2+ with Libtool exception |
| dash | 0.5.12-12 | dash | BSD-3-Clause, BSD-3-clause, GPL-2+, public-domain |
| dbus | 1.16.2-2 | dbus | AFL-2.1, BSD-3-clause, BSD-3-clause and BSD-3-clause-generic, BSD-3-clause-generic, Expat, GPL-2+, GPL-2+ or AFL-2.1, an |
| dbus-bin | 1.16.2-2 | dbus | AFL-2.1, BSD-3-clause, BSD-3-clause and BSD-3-clause-generic, BSD-3-clause-generic, Expat, GPL-2+, GPL-2+ or AFL-2.1, an |
| dbus-daemon | 1.16.2-2 | dbus | AFL-2.1, BSD-3-clause, BSD-3-clause and BSD-3-clause-generic, BSD-3-clause-generic, Expat, GPL-2+, GPL-2+ or AFL-2.1, an |
| dbus-session-bus-common | 1.16.2-2 | dbus | AFL-2.1, BSD-3-clause, BSD-3-clause and BSD-3-clause-generic, BSD-3-clause-generic, Expat, GPL-2+, GPL-2+ or AFL-2.1, an |
| dbus-system-bus-common | 1.16.2-2 | dbus | AFL-2.1, BSD-3-clause, BSD-3-clause and BSD-3-clause-generic, BSD-3-clause-generic, Expat, GPL-2+, GPL-2+ or AFL-2.1, an |
| dbus-user-session | 1.16.2-2 | dbus | AFL-2.1, BSD-3-clause, BSD-3-clause and BSD-3-clause-generic, BSD-3-clause-generic, Expat, GPL-2+, GPL-2+ or AFL-2.1, an |
| dconf-gsettings-backend | 0.40.0-5 | dconf | GPL-3, LGPL-2+ |
| dconf-service | 0.40.0-5 | dconf | GPL-3, LGPL-2+ |
| debconf | 1.5.91 | debconf | BSD-2-clause |
| debconf-i18n | 1.5.91 | debconf | siehe /usr/share/doc/debconf-i18n/copyright |
| debian-archive-keyring | 2025.1 | debian-archive-keyring | siehe /usr/share/doc/debian-archive-keyring/copyright |
| debianutils | 5.23.2 | debianutils | GPL-2+, SMAIL-GPL, public-domain |
| desktop-file-utils | 0.28-1 | desktop-file-utils | GPL-2+ |
| dhcpcd-base | 1:10.1.0-11+deb13u4 | dhcpcd | BSD-2-Clause-NetBSD, BSD-2-clause, BSD-3-clause, Expat, GPL-3+, ISC, public-domain |
| dictionaries-common | 1.30.10 | dictionaries-common | GPL-2+, GPL-3+ |
| diffutils | 1:3.10-4 | diffutils | FSFAP, FSFULLR, GFDL-NIV-1.3, GPL-2+, GPL-3+, GPL-3+ and FSFULLR, GPL-3+ with autoconf exception, GPL-3+ with texinfo ex |
| dirmngr | 2.4.7-21+deb13u1+b5 | gnupg2 | BSD-3-clause, CC0-1.0, Expat, GPL-2+, GPL-3+, GPL-3+ or BSD-3-clause, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2+, RFC-Referen |
| dmeventd | 2:1.02.205-2 | lvm2 | BSD-2-Clause, GPL-2.0, GPL-2.0+, LGPL-2.1 |
| dmidecode | 3.6-2 | dmidecode | GPL-2+ |
| dmsetup | 2:1.02.205-2 | lvm2 | BSD-2-Clause, GPL-2.0, GPL-2.0+, LGPL-2.1 |
| dosfstools | 4.2-1.2 | dosfstools | GPL-3+, public-domain |
| dpkg | 1.22.22 | dpkg | GPL-2+, public-domain-s-s-d |
| dracut-install | 106-6 | dracut | BSD-3-clause, GPL-2+, LGPL-2.1+ |
| e2fsprogs | 1.47.2-3+b12 | e2fsprogs | 0BSD, Apache-2, BSD-3-Clause, BSD-3-Clause-Variant, BSD-4-Clause-CMU, Expat, GPL or MIT-US-export, GPL-2, GPL-2+, GPL-2+ |
| edac-utils | 0.18+git16-g8fdc1d4-2 | edac-utils | This package is free software; you can redistribute it and/or modify |
| emacsen-common | 3.0.8 | emacsen-common | GPL-2+ |
| ethtool | 1:6.14.2-1 | ethtool | GPL-2, GPL-3+ with autoconf exception |
| fastfetch | 2.40.4+dfsg-1 | fastfetch | CDDL-1.0, Expat, MIT |
| fdisk | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| feh | 3.10.3-1 | feh | GPL-2+, MIT |
| findutils | 4.10.0-3 | findutils | BSD-3-clause, BSD-3-clause or GPL-3+, BSD-3-clause or LGPL-2.1+, BSD-3-clause or LGPL-3+, FSFAP, FSFULLR, FSFULLR or GPL |
| fio | 3.39-1 | fio | BSD-0-clause, BSD-2-clause, GPL-2, GPL-2+, public-domain |
| firmware-bnx2 | 20250410-2 | firmware-nonfree | Apache-2.0, BSD-2-clause, BSD-2-clause-Myricom, BSD-2-clause-OpenIB.org, BSD-3-clause-3Com, BSD-3-clause-Agere, BSD-3-cl |
| firmware-bnx2x | 20250410-2 | firmware-nonfree | Apache-2.0, BSD-2-clause, BSD-2-clause-Myricom, BSD-2-clause-OpenIB.org, BSD-3-clause-3Com, BSD-3-clause-Agere, BSD-3-cl |
| firmware-intel-misc | 20250410-2 | firmware-nonfree | Apache-2.0, BSD-2-clause, BSD-2-clause-Myricom, BSD-2-clause-OpenIB.org, BSD-3-clause-3Com, BSD-3-clause-Agere, BSD-3-cl |
| firmware-misc-nonfree | 20250410-2 | firmware-nonfree | Apache-2.0, BSD-2-clause, BSD-2-clause-Myricom, BSD-2-clause-OpenIB.org, BSD-3-clause-3Com, BSD-3-clause-Agere, BSD-3-cl |
| firmware-netxen | 20250410-2 | firmware-nonfree | Apache-2.0, BSD-2-clause, BSD-2-clause-Myricom, BSD-2-clause-OpenIB.org, BSD-3-clause-3Com, BSD-3-clause-Agere, BSD-3-cl |
| firmware-nvidia-gsp | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| firmware-qlogic | 20250410-2 | firmware-nonfree | Apache-2.0, BSD-2-clause, BSD-2-clause-Myricom, BSD-2-clause-OpenIB.org, BSD-3-clause-3Com, BSD-3-clause-Agere, BSD-3-cl |
| fontconfig | 2.15.0-2.3 | fontconfig | siehe /usr/share/doc/fontconfig/copyright |
| fontconfig-config | 2.15.0-2.3 | fontconfig | siehe /usr/share/doc/fontconfig-config/copyright |
| fonts-dejavu-core | 2.37-8 | fonts-dejavu | GPL-2+, bitstream-vera |
| fonts-dejavu-mono | 2.37-8 | fonts-dejavu | GPL-2+, bitstream-vera |
| fonts-urw-base35 | 20200910-8 | fonts-urw-base35 | AGPL-3, AGPL-3 with Font exception, CC-BY-4.0, GPL-2+ |
| freeipmi-common | 1.6.15-1 | freeipmi | FSFULLR, GPL-2+, GPL-3+, LGPL-2+, LGPL-3+ |
| gcc-14-base | 14.2.0-19 | gcc-14 | siehe /usr/share/doc/gcc-14-base/copyright |
| gettext-base | 0.23.1-2 | gettext | FDL-1.2+, FDL-1.2+ or GPL-2+, GPL-2+, GPL-3+, LGPL-2.1+ |
| glib-networking | 2.80.1-1 | glib-networking | LGPL-2+, LGPL-2+ and LGPL-2.1+, LGPL-2.1+ |
| glib-networking-common | 2.80.1-1 | glib-networking | LGPL-2+, LGPL-2+ and LGPL-2.1+, LGPL-2.1+ |
| glib-networking-services | 2.80.1-1 | glib-networking | LGPL-2+, LGPL-2+ and LGPL-2.1+, LGPL-2.1+ |
| gnupg | 2.4.7-21+deb13u1 | gnupg2 | BSD-3-clause, CC0-1.0, Expat, GPL-2+, GPL-3+, GPL-3+ or BSD-3-clause, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2+, RFC-Referen |
| gnupg-l10n | 2.4.7-21+deb13u1 | gnupg2 | BSD-3-clause, CC0-1.0, Expat, GPL-2+, GPL-3+, GPL-3+ or BSD-3-clause, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2+, RFC-Referen |
| gpg | 2.4.7-21+deb13u1+b5 | gnupg2 | BSD-3-clause, CC0-1.0, Expat, GPL-2+, GPL-3+, GPL-3+ or BSD-3-clause, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2+, RFC-Referen |
| gpg-agent | 2.4.7-21+deb13u1+b5 | gnupg2 | BSD-3-clause, CC0-1.0, Expat, GPL-2+, GPL-3+, GPL-3+ or BSD-3-clause, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2+, RFC-Referen |
| gpgconf | 2.4.7-21+deb13u1+b5 | gnupg2 | BSD-3-clause, CC0-1.0, Expat, GPL-2+, GPL-3+, GPL-3+ or BSD-3-clause, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2+, RFC-Referen |
| gpgsm | 2.4.7-21+deb13u1+b5 | gnupg2 | BSD-3-clause, CC0-1.0, Expat, GPL-2+, GPL-3+, GPL-3+ or BSD-3-clause, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2+, RFC-Referen |
| grep | 3.11-4 | grep | GPL-3+ |
| grub-common | 2.12-9+deb13u2 | grub2 | CC-BY-SA-3.0, Expat, GPL-3+ |
| gsettings-desktop-schemas | 48.0-1 | gsettings-desktop-schemas | LGPL-2.1+ |
| gstreamer1.0-plugins-base | 1.26.2-1+deb13u2 | gst-plugins-base1.0 | BSD (2 clause), BSD (3 clause), BSD-3-clause, CC-BY-SA-4.0, GPL-2+, LGPL, LGPL-2+, LGPL-2.1+, MIT/X11 (BSD like) LGPL-2+ |
| gstreamer1.0-plugins-good | 1.26.2-1+deb13u2 | gst-plugins-good1.0 | BSD-3-clause, GPL-2+, LGPL-2, LGPL-2+, LGPL-2.1+, MIT/X11 (BSD like) LGPL-2+ |
| gtk-update-icon-cache | 4.18.6+ds-2 | gtk4 | Apache-2.0, Apache-2.0 with LLVM exception, BSD-3-clause-Google, CC0-1.0, Expat, GPL-3+, LGPL-2+, LGPL-2+ and LGPL-2.1+  |
| gvfs | 1.57.2-2+deb13u1 | gvfs | GPL-2+, GPL-3+, LGPL-2+ |
| gvfs-common | 1.57.2-2+deb13u1 | gvfs | GPL-2+, GPL-3+, LGPL-2+ |
| gvfs-daemons | 1.57.2-2+deb13u1 | gvfs | GPL-2+, GPL-3+, LGPL-2+ |
| gvfs-libs | 1.57.2-2+deb13u1 | gvfs | GPL-2+, GPL-3+, LGPL-2+ |
| gzip | 1.13-1+deb13u1 | gzip | FSF-manpages, GFDL-1.3+-no-invariant, GPL-3+ |
| hardwaretest | 0.2.48 | hardwaretest | MIT (freie Variante ohne DCGM) |
| hdparm | 9.65+ds-1.1 | hdparm | BSD-2-clause, GPL-2+, GPL-2+ or BSD-2-clause, hdparm |
| hicolor-icon-theme | 0.18-2 | hicolor-icon-theme | GPL-2+ |
| hostname | 3.25 | hostname | GPL-2 |
| hponcfg | 6.1.0-0 | hponcfg | siehe /usr/share/doc/hponcfg/copyright |
| htop | 3.4.1-5 | htop | GPL-2+ |
| hunspell-en-us | 1:2020.12.07-4 | scowl | siehe /usr/share/doc/hunspell-en-us/copyright |
| ifupdown | 0.8.44+deb13u1 | ifupdown | GPL-2+ |
| ilorest | 7.4.0.0 | ilorest | BSD-3-Clause (HPE iLOrest) |
| init | 1.69~deb13u1 | init-system-helpers | BSD-3-clause, GPL-2+ |
| init-system-helpers | 1.69~deb13u1 | init-system-helpers | BSD-3-clause, GPL-2+ |
| initramfs-tools | 0.148.4 | initramfs-tools | GPL-2+ |
| initramfs-tools-bin | 0.148.4 | initramfs-tools | GPL-2+ |
| initramfs-tools-core | 0.148.4 | initramfs-tools | GPL-2+ |
| iperf3 | 3.18-2+deb13u2 | iperf3 | BSD-2-clause, BSD-3-clause, BSD-3-clause-iperf, BSD-3-clause-iperf+MIT/X11+BSD-3-clause, FSF-permissive1, FSF-permissive |
| ipmitool | 1.8.19-9 | ipmitool | BSD-3-Clause-No-Nuclear-Warranty, BSD-3-clause, FSFAP, LGPL-2.1+, Zlib |
| iproute2 | 6.15.0-1 | iproute2 | GPL-2 |
| iputils-ping | 3:20240905-3 | iputils | BSD-3-clause, GPL-2+, public-domain |
| iso-codes | 4.18.0-1 | iso-codes | LGPL-2.1+ |
| jq | 1.7.1-6+deb13u4 | jq | CC-BY-3.0, Expat, GPL-2.0+, MIT |
| json-viewer | 1.5.4 | json-viewer | MIT |
| kbd | 2.7.1-2 | kbd | GPL-2+, GPL-2-with-exceptions, GPL-any |
| keyboard-configuration | 1.242~deb13u1 | console-setup | siehe /usr/share/doc/keyboard-configuration/copyright |
| klibc-utils | 2.0.14-1 | klibc | siehe /usr/share/doc/klibc-utils/copyright |
| kmod | 34.2-2 | kmod | siehe /usr/share/doc/kmod/copyright |
| less | 668-1 | less | GPL-3+, GPL-3+ or Less, GPL-3+ or Less, and X11, Less, Spencer-86, X11, public-domain |
| libaa1 | 1.4p5-51.1+b1 | aalib | Abstyles, Custom, LGPL-2.0+ |
| libabsl20240722 | 20240722.0-4 | abseil | Apache-2.0 |
| libacl1 | 2.3.2-2+b1 | acl | GPL-2+, LGPL-2+ |
| libaio1t64 | 0.3.113-8+b1 | libaio | LGPL-2.1+ |
| libaom3 | 3.12.1-1+deb13u1 | aom | BSD-2-Clause, BSD-2-clause, BSD-3-clause, Expat, ISC, public-domain-md5 |
| libapparmor1 | 4.1.0-1 | apparmor | BSD-3-clause, BSD-3-clause or GPL-2+, GPL-2, GPL-2+, LGPL-2.1+ |
| libapt-pkg7.0 | 3.0.3 | apt | BSD-3-clause, Expat, GPL-2, GPL-2+, GPL-2+ and curl, curl |
| libasound2-data | 1.2.14-1+deb13u1 | alsa-lib | LGPL-2.1+ |
| libasound2t64 | 1.2.14-1+deb13u1 | alsa-lib | LGPL-2.1+ |
| libaspell15 | 0.60.8.1-4 | aspell | GFDL-1.2+, LGPL-2.1+ |
| libassuan9 | 3.0.2-2 | libassuan | FSFULLR, FSFULLRWD, GPL-2+ with Autoconf-data exception, GPL-2+ with Libtool exception, GPL-2.with.nonstandard.Autoconf- |
| libasyncns0 | 0.8-6+b5 | libasyncns | LGPL-2.1+ |
| libatasmart4 | 0.19-5+b2 | libatasmart | This package is free software; you can redistribute it and/or |
| libatk-bridge2.0-0t64 | 2.56.2-1+deb13u2 | at-spi2-core | AFL-2.1, AFL-2.1 or GPL-2+, GPL-2, GPL-2+, LGPL-2+, LGPL-2.1+, public-domain |
| libatk1.0-0t64 | 2.56.2-1+deb13u2 | at-spi2-core | AFL-2.1, AFL-2.1 or GPL-2+, GPL-2, GPL-2+, LGPL-2+, LGPL-2.1+, public-domain |
| libatomic1 | 14.2.0-19 | gcc-14 | siehe /usr/share/doc/libatomic1/copyright |
| libatspi2.0-0t64 | 2.56.2-1+deb13u2 | at-spi2-core | AFL-2.1, AFL-2.1 or GPL-2+, GPL-2, GPL-2+, LGPL-2+, LGPL-2.1+, public-domain |
| libattr1 | 1:2.5.2-3 | attr | GPL-2+, LGPL-2+ |
| libaudit-common | 1:4.0.2-2+deb13u1 | audit | GPL-2, LGPL-2.1 |
| libaudit1 | 1:4.0.2-2+deb13u1 | audit | GPL-2, LGPL-2.1 |
| libavahi-client3 | 0.8-16 | avahi | siehe /usr/share/doc/libavahi-client3/copyright |
| libavahi-common-data | 0.8-16 | avahi | siehe /usr/share/doc/libavahi-common-data/copyright |
| libavahi-common3 | 0.8-16 | avahi | siehe /usr/share/doc/libavahi-common3/copyright |
| libavc1394-0 | 0.5.4-5+b2 | libavc1394 | GPL-2+, LGPL-2.1+ |
| libavif16 | 1.2.1-1.2 | libavif | Apache-2.0, BSD-2-Clause, BSD-3-Clause, CC0-1.0, MIT, custom-1 |
| libayatana-appindicator3-1 | 0.5.94-1 | libayatana-appindicator | BSD-2-clause, BSD-3-clause, GPL-3, GPL-3 or LGPL-2.1 or LGPL-3, LGPL-2.1, LGPL-2.1 or LGPL-3, LGPL-2.1 or LGPL-3 or GPL- |
| libayatana-ido3-0.4-0 | 0.10.4-1 | ayatana-ido | BSD-2-clause, BSD-3-clause, GPL-3, GPL-3 or LGPL-2.1 or LGPL-3, GPL-3 or LGPL-3 or LGPL-2.1, LGPL-2+, LGPL-2.1, LGPL-2.1 |
| libayatana-indicator3-7 | 0.9.4-1+b1 | libayatana-indicator | GPL-3 |
| libbinutils | 2.44-3 | binutils | siehe /usr/share/doc/libbinutils/copyright |
| libblkid1 | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| libblockdev-crypto3 | 3.3.0-2.1 | libblockdev | GPL-2+, LGPL-2.1+ |
| libblockdev-fs3 | 3.3.0-2.1 | libblockdev | GPL-2+, LGPL-2.1+ |
| libblockdev-loop3 | 3.3.0-2.1 | libblockdev | GPL-2+, LGPL-2.1+ |
| libblockdev-mdraid3 | 3.3.0-2.1 | libblockdev | GPL-2+, LGPL-2.1+ |
| libblockdev-nvme3 | 3.3.0-2.1 | libblockdev | GPL-2+, LGPL-2.1+ |
| libblockdev-part3 | 3.3.0-2.1 | libblockdev | GPL-2+, LGPL-2.1+ |
| libblockdev-swap3 | 3.3.0-2.1 | libblockdev | GPL-2+, LGPL-2.1+ |
| libblockdev-utils3 | 3.3.0-2.1 | libblockdev | GPL-2+, LGPL-2.1+ |
| libblockdev3 | 3.3.0-2.1 | libblockdev | GPL-2+, LGPL-2.1+ |
| libbluetooth3 | 5.82-1.1 | bluez | Apache-2.0, BSD-2-clause, GPL-2+, LGPL-2.1+ |
| libbluray2 | 1:1.3.4-1+b2 | libbluray | BSD-3-clause, GPL-2+, LGPL-2.1+, MPL-1.0, MPL-1.0 or GPL-2+ or LGPL-2.1+, custom |
| libboost-iostreams1.83.0 | 1.83.0-4.2 | boost1.83 | Apache-2.0, Apache-2.0 and BSL-1.0, BSD2, BSD2 and BSL-1.0, BSD3_DEShaw, BSD3_DEShaw and BSL-1.0, BSD3_Google, BSL-1.0,  |
| libboost-thread1.83.0 | 1.83.0-4.2 | boost1.83 | Apache-2.0, Apache-2.0 and BSL-1.0, BSD2, BSD2 and BSL-1.0, BSD3_DEShaw, BSD3_DEShaw and BSL-1.0, BSD3_Google, BSL-1.0,  |
| libbpf1 | 1:1.5.0-3 | libbpf | BSD-2-Clause, BSD-3-Clause, GPL-2 with Linux-syscall-note exception, GPL-2 with Linux-syscall-note exception OR BSD-3-Cl |
| libbrotli1 | 1.1.0-2+b7 | brotli | MIT |
| libbsd0 | 0.12.2-2 | libbsd | BSD-2-clause, BSD-2-clause-NetBSD, BSD-2-clause-author, BSD-2-clause-verbatim, BSD-3-clause, BSD-3-clause-John-Birrell,  |
| libbytesize-common | 2.11-2 | libbytesize | LGPL-2.1+ |
| libbytesize1 | 2.11-2 | libbytesize | LGPL-2.1+ |
| libbz2-1.0 | 1.0.8-6 | bzip2 | BSD-variant, GPL-2 |
| libc-bin | 2.41-12+deb13u4 | glibc | BSD-2-clause, BSD-2-clause or GPL-2, BSD-3-clause-Berkeley, BSD-3-clause-Berkeley and BSD-3-clause-WIDE, BSD-3-clause-Be |
| libc6 | 2.41-12+deb13u4 | glibc | BSD-2-clause, BSD-2-clause or GPL-2, BSD-3-clause-Berkeley, BSD-3-clause-Berkeley and BSD-3-clause-WIDE, BSD-3-clause-Be |
| libcaca0 | 0.99.beta20-5+deb13u1 | libcaca | GPL, GPL-2+, ISC, LGPL-2+, WTFPL-2 |
| libcairo-gobject2 | 1.18.4-1+b1 | cairo | siehe /usr/share/doc/libcairo-gobject2/copyright |
| libcairo2 | 1.18.4-1+b1 | cairo | siehe /usr/share/doc/libcairo2/copyright |
| libcap-ng0 | 0.8.5-4+b1 | libcap-ng | GPL-2+, GPL-3, LGPL-2.1+ |
| libcap2 | 1:2.75-10+deb13u1+b3 | libcap2 | BSD-3-clause, BSD-3-clause or GPL-2, BSD-3-clause or GPL-2+, GPL-2, GPL-2+ |
| libcap2-bin | 1:2.75-10+deb13u1+b3 | libcap2 | BSD-3-clause, BSD-3-clause or GPL-2, BSD-3-clause or GPL-2+, GPL-2, GPL-2+ |
| libcbor0.10 | 0.10.2-2 | libcbor | Expat |
| libcdparanoia0 | 3.10.2+debian-14+b1 | cdparanoia | GPL-2+, LGPL-2.1+ |
| libcloudproviders0 | 0.3.6-2 | libcloudproviders | LGPL-3+ |
| libcolord2 | 1.4.7-3 | colord | CC0-1.0, CC0-1.0 and NPES, GFDL-NIV, GPL-2+, LGPL-2.1+, NPES |
| libcom-err2 | 1.47.2-3+b12 | e2fsprogs | 0BSD, Apache-2, BSD-3-Clause, BSD-3-Clause-Variant, BSD-4-Clause-CMU, Expat, GPL or MIT-US-export, GPL-2, GPL-2+, GPL-2+ |
| libcrypt1 | 1:4.4.38-1 | libxcrypt | siehe /usr/share/doc/libcrypt1/copyright |
| libcryptsetup12 | 2:2.7.5-2 | cryptsetup | Apache-2.0, CC-BY-SA-4.0, CC0, CC0 or Apache-2.0, GPL-2+, GPL-2+ with OpenSSL exception, GPL-3+, LGPL-2.1+, LGPL-2.1+ wi |
| libctf-nobfd0 | 2.44-3 | binutils | siehe /usr/share/doc/libctf-nobfd0/copyright |
| libctf0 | 2.44-3 | binutils | siehe /usr/share/doc/libctf0/copyright |
| libcuda1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libcudadebugger1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libcups2t64 | 2.4.10-3+deb13u2 | cups | Apache-2.0, Apache-2.0-with-GPL2-LGPL2-Exception, Apache-2.0-with-GPL2-LGPL2-Exception or BSD-2-clause, BSD-2-Clause, FS |
| libcurl3t64-gnutls | 8.14.1-2+deb13u7 | curl | BSD-3-Clause, BSD-3-clause, BSD-4-Clause-UC, FSFULLR, GPL-2+ with Autoconf-data exception, GPL-2+ with Libtool exception |
| libcurl4t64 | 8.14.1-2+deb13u7 | curl | BSD-3-Clause, BSD-3-clause, BSD-4-Clause-UC, FSFULLR, GPL-2+ with Autoconf-data exception, GPL-2+ with Libtool exception |
| libdatrie1 | 0.2.13-3+b1 | libdatrie | GPL-2+, LGPL-2.1+ |
| libdav1d7 | 1.5.1-1 | dav1d | BSD-2-clause, ISC, ISC and BSD-2-clause, public-domain |
| libdaxctl1 | 81-1 | ndctl | CC0-1.0, Expat, GPL-2, LGPL-2.1 |
| libdb5.3t64 | 5.3.28+dfsg2-9 | db5.3 | Artistic or BSD-3-clause, BSD-3-clause, BSD-3-clause-fjord, GPL, GPL or Artistic, GPL-3, MIT-old, Ms-PL, Sleepycat, Slee |
| libdbd-sqlite3-perl | 1.76-1 | libdbd-sqlite3-perl | Apache-2.0, Artistic, Artistic or GPL-1+, GPL-1+, public-domain |
| libdbi-perl | 1.652-2~deb13u1 | libdbi-perl | Artistic, Artistic or GPL-1+, GPL-1+ |
| libdbus-1-3 | 1.16.2-2 | dbus | AFL-2.1, BSD-3-clause, BSD-3-clause and BSD-3-clause-generic, BSD-3-clause-generic, Expat, GPL-2+, GPL-2+ or AFL-2.1, an |
| libdbus-glib-1-2 | 0.114-1 | dbus-glib | AFL-2.1, Expat, GPL-2+, GPL-2+ or AFL-2.1, GPL-2+ or AFL-2.1 or Expat |
| libdbusmenu-glib4 | 18.10.20180917~bzr492+repack1-4 | libdbusmenu | GPL-3, LGPL-2.1, LGPL-2.1 or LGPL-3, LGPL-3 |
| libdbusmenu-gtk3-4 | 18.10.20180917~bzr492+repack1-4 | libdbusmenu | GPL-3, LGPL-2.1, LGPL-2.1 or LGPL-3, LGPL-3 |
| libdconf1 | 0.40.0-5 | dconf | GPL-3, LGPL-2+ |
| libde265-0 | 1.0.15-1+deb13u2 | libde265 | BSD-4-clause, GPL-3+, LGPL-3+, other-1, public-domain-1 |
| libdebconfclient0 | 0.280 | cdebconf | BSD-2-Clause, BSD-2-clause, GPL-2+ |
| libdeflate0 | 1.23-2 | libdeflate | Expat |
| libdevmapper-event1.02.1 | 2:1.02.205-2 | lvm2 | BSD-2-Clause, GPL-2.0, GPL-2.0+, LGPL-2.1 |
| libdevmapper1.02.1 | 2:1.02.205-2 | lvm2 | BSD-2-Clause, GPL-2.0, GPL-2.0+, LGPL-2.1 |
| libdrm-amdgpu1 | 2.4.124-2 | libdrm | siehe /usr/share/doc/libdrm-amdgpu1/copyright |
| libdrm-common | 2.4.124-2 | libdrm | siehe /usr/share/doc/libdrm-common/copyright |
| libdrm-intel1 | 2.4.124-2 | libdrm | siehe /usr/share/doc/libdrm-intel1/copyright |
| libdrm2 | 2.4.124-2 | libdrm | siehe /usr/share/doc/libdrm2/copyright |
| libduktape207 | 2.7.0-2+b2 | duktape | CC0, expat, unicode |
| libdv4t64 | 1.0.0-17.1+b1 | libdv | GPL-2+, LGPL-2.1+ |
| libdw1t64 | 0.192-4 | elfutils | BSD-2-clause, GFDL-NIV-1.3, GPL-3+, GPL-3+ with Bison exception, LGPL-2.1+, LGPL-3+ or GPL-2+ |
| libedac1 | 0.18+git16-g8fdc1d4-2 | edac-utils | This package is free software; you can redistribute it and/or modify |
| libedit2 | 3.1-20250104-1 | libedit | BSD-3-clause |
| libefiboot1t64 | 38-3.1+b1 | efivar | GPL-2.0+, LGPL-2.0+ |
| libefivar1t64 | 38-3.1+b1 | efivar | GPL-2.0+, LGPL-2.0+ |
| libegl-mesa0 | 25.0.7-2+deb13u1 | mesa | Apache-2.0, BSD-2-clause, BSD-3-google, BSL, GPL, GPL-1+, GPL-2, GPL-2 or MIT, Khronos, MIT, MLAA, SGI |
| libegl1 | 1.7.0-1+b2 | libglvnd | Apache-2.0, BSD-1-clause, GPL, GPL-3+, MIT, public-domain |
| libelf1t64 | 0.192-4 | elfutils | BSD-2-clause, GFDL-NIV-1.3, GPL-3+, GPL-3+ with Bison exception, LGPL-2.1+, LGPL-3+ or GPL-2+ |
| libenchant-2-2 | 2.8.2+dfsg1-3 | enchant-2 | Expat, FSFAP, GPL-2.0+, GPL-3.0+, LGPL-2.0+, LGPL-2.1+, LGPL-3.0+ |
| libepoxy0 | 1.5.10-2 | libepoxy | Expat |
| libevdev2 | 1.13.4+dfsg-1 | libevdev | Apache-2.0, BSD-3, GPL-2, GPL-2+, MIT |
| libexif12 | 0.6.25-1+deb13u1 | libexif | BSD-3-Clause, CC0-1.0, GPL-2.0, LGPL-2.1-or-later, LicenseRef-Wrobel, MIT |
| libexpat1 | 2.9.0-1~deb13u1 | expat | MIT |
| libext2fs2t64 | 1.47.2-3+b12 | e2fsprogs | 0BSD, Apache-2, BSD-3-Clause, BSD-3-Clause-Variant, BSD-4-Clause-CMU, Expat, GPL or MIT-US-export, GPL-2, GPL-2+, GPL-2+ |
| libfdisk1 | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| libffi8 | 3.4.8-2 | libffi | Expat, GPL, GPL-2+, GPL-3+, MPL-1.1 or GPL-2+ or LGPL-2.1+, X11, public-domain |
| libfido2-1 | 1.15.0-1+b1 | libfido2 | BSD-2-clause, ISC, ISC and BSD-2-clause, public-domain |
| libflac14 | 1.5.0+ds-2 | flac | BSD-3-clause, GFDL-1.1+, GPL-2+, GPL-2+ or LGPL-2.1+, ISC, LGPL-2+, LGPL-2.1+, Public-domain |
| libflite1 | 2.2-7 | flite | Permission is granted to anyone to use this software for any, Permission is granted to make and distribute verbatim copi |
| libfm-data | 1.4.0-2 | libfm | GPL-2+, GPL-3+, LGPL-2+, LGPL-2.1+ |
| libfm-extra4t64 | 1.4.0-2 | libfm | GPL-2+, GPL-3+, LGPL-2+, LGPL-2.1+ |
| libfm-gtk-data | 1.4.0-2 | libfm | GPL-2+, GPL-3+, LGPL-2+, LGPL-2.1+ |
| libfm-gtk3-4t64 | 1.4.0-2 | libfm | GPL-2+, GPL-3+, LGPL-2+, LGPL-2.1+ |
| libfm4t64 | 1.4.0-2 | libfm | GPL-2+, GPL-3+, LGPL-2+, LGPL-2.1+ |
| libfmt10 | 10.1.1+ds1-4 | fmtlib | BSD-2-Clause, CC0-1.0, Expat, Expat or CC0-1.0, Expat with embedded exception, Python |
| libfontconfig1 | 2.15.0-2.3 | fontconfig | siehe /usr/share/doc/libfontconfig1/copyright |
| libfontenc1 | 1:1.1.8-1+b2 | libfontenc | siehe /usr/share/doc/libfontenc1/copyright |
| libfreeipmi17 | 1.6.15-1 | freeipmi | FSFULLR, GPL-2+, GPL-3+, LGPL-2+, LGPL-3+ |
| libfreetype6 | 2.13.3+dfsg-1+deb13u1 | freetype | BSD-3-Clause, BSL-1.0, Expat, FSFAP, FTL, FTL and Expat, GPL-2+, GPL-3+, MIT-Modern-Variant, MIT-SMC, OpenGroup-MIT, Pub |
| libfribidi0 | 1.0.16-1 | fribidi | LGPL-2.1+ |
| libfuse3-4 | 3.17.2-3 | fuse3 | GPL-2, GPL-2+, LGPL-2.1 |
| libgav1-1 | 0.19.0-3+b1 | libgav1 | Apache-2.0, BSD-3-clause |
| libgbm1 | 25.0.7-2+deb13u1 | mesa | Apache-2.0, BSD-2-clause, BSD-3-google, BSL, GPL, GPL-1+, GPL-2, GPL-2 or MIT, Khronos, MIT, MLAA, SGI |
| libgcc-s1 | 14.2.0-19 | gcc-14 | siehe /usr/share/doc/libgcc-s1/copyright |
| libgck-1-0 | 3.41.2-3 | gcr | LGPL-2.1+, bzip2-1.0.5 |
| libgck-2-2 | 4.4.0.1-3 | gcr4 | LGPL-2.1+, bzip2-1.0.5 |
| libgcr-4-4 | 4.4.0.1-3 | gcr4 | LGPL-2.1+, bzip2-1.0.5 |
| libgcr-base-3-1 | 3.41.2-3 | gcr | LGPL-2.1+, bzip2-1.0.5 |
| libgcr-ui-3-1 | 3.41.2-3 | gcr | LGPL-2.1+, bzip2-1.0.5 |
| libgcrypt20 | 1.11.0-7+deb13u1 | libgcrypt20 | Most of the package is licensed under the GNU Lesser General Public |
| libgdbm-compat4t64 | 1.24-2 | gdbm | GFDL-NIV-1.3+, GPL-2+, GPL-3+ |
| libgdbm6t64 | 1.24-2 | gdbm | GFDL-NIV-1.3+, GPL-2+, GPL-3+ |
| libgdk-pixbuf-2.0-0 | 2.42.12+dfsg-4+deb13u1 | gdk-pixbuf | CC0-1.0, GPL-2+, LGPL-2+, LGPL-2+ and LGPL-2.1+ and CC0-1.0, LGPL-2.1+ |
| libgdk-pixbuf2.0-common | 2.42.12+dfsg-4+deb13u1 | gdk-pixbuf | CC0-1.0, GPL-2+, LGPL-2+, LGPL-2+ and LGPL-2.1+ and CC0-1.0, LGPL-2.1+ |
| libgfapi0 | 11.1-6 | glusterfs | BSD-2-clause, BSD-4-clause, GPL-2, GPL-2+, GPL-3+, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2 |
| libgfrpc0 | 11.1-6 | glusterfs | BSD-2-clause, BSD-4-clause, GPL-2, GPL-2+, GPL-3+, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2 |
| libgfxdr0 | 11.1-6 | glusterfs | BSD-2-clause, BSD-4-clause, GPL-2, GPL-2+, GPL-3+, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2 |
| libgif7 | 5.2.2-1+deb13u1 | giflib | ISC, MIT |
| libgl1 | 1.7.0-1+b2 | libglvnd | Apache-2.0, BSD-1-clause, GPL, GPL-3+, MIT, public-domain |
| libgl1-mesa-dri | 25.0.7-2+deb13u1 | mesa | Apache-2.0, BSD-2-clause, BSD-3-google, BSL, GPL, GPL-1+, GPL-2, GPL-2 or MIT, Khronos, MIT, MLAA, SGI |
| libgles2 | 1.7.0-1+b2 | libglvnd | Apache-2.0, BSD-1-clause, GPL, GPL-3+, MIT, public-domain |
| libglib2.0-0t64 | 2.84.4-3~deb13u5 | glib2.0 | AFL-2.0, AFL-2.0 or LGPL-2.1+, Apache-2.0 with LLVM exception, CC-BY-SA-3.0, CC0-1.0, CC0-1.0 or Mingw-PD, Expat, FSFULL |
| libglusterfs0 | 11.1-6 | glusterfs | BSD-2-clause, BSD-4-clause, GPL-2, GPL-2+, GPL-3+, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2 |
| libglvnd0 | 1.7.0-1+b2 | libglvnd | Apache-2.0, BSD-1-clause, GPL, GPL-3+, MIT, public-domain |
| libglx-mesa0 | 25.0.7-2+deb13u1 | mesa | Apache-2.0, BSD-2-clause, BSD-3-google, BSL, GPL, GPL-1+, GPL-2, GPL-2 or MIT, Khronos, MIT, MLAA, SGI |
| libglx0 | 1.7.0-1+b2 | libglvnd | Apache-2.0, BSD-1-clause, GPL, GPL-3+, MIT, public-domain |
| libgmp10 | 2:6.3.0+dfsg-3 | gmp | GPL-2+, GPL-2+ or LGPL-3+, GPL-3+, GPL-3+ with Bison exception, LGPL-3+ |
| libgnutls30t64 | 3.8.9-3+deb13u4 | gnutls28 | # Licensed under the Apache License, Version 2.0 (the "License");, * Redistribution and use in source and binary forms,  |
| libgpg-error0 | 1.51-4 | libgpg-error | BSD-3-clause, GPL-3+, LGPL-2.1+, LGPL-2.1+ or BSD-3-clause, g10-permissive |
| libgpgme11t64 | 1.24.2-3 | gpgme1.0 | GPL-2+, GPL-3+, LGPL-2+, LGPL-2.1+, LGPL-3+, LGPL-3+ or GPL-2+ |
| libgpm2 | 1.20.7-11+b2 | gpm | GPL-2.0+, GPL-3.0+ |
| libgprofng0 | 2.44-3 | binutils | siehe /usr/share/doc/libgprofng0/copyright |
| libgraphite2-3 | 1.3.14-2+deb13u1 | graphite2 | Artistic, Artistic or GPL-1+, GPL-1+, GPL-2+, LGPL-2.1+, LGPL-2.1+ or GPL-2+ or MPL-1.1, LGPL-2.1+ or MPL-1.1 or GPL-2+, |
| libgs-common | 10.05.1~dfsg-1+deb13u3 | ghostscript | AGPL-3, AGPL-3+, AGPL-3+ and FTL, AGPL-3+ with font exception, Apache-2.0, BSD-3-Clause, BSD-3-Clause~Adobe, Expat, Expa |
| libgs10 | 10.05.1~dfsg-1+deb13u3 | ghostscript | AGPL-3, AGPL-3+, AGPL-3+ and FTL, AGPL-3+ with font exception, Apache-2.0, BSD-3-Clause, BSD-3-Clause~Adobe, Expat, Expa |
| libgs10-common | 10.05.1~dfsg-1+deb13u3 | ghostscript | AGPL-3, AGPL-3+, AGPL-3+ and FTL, AGPL-3+ with font exception, Apache-2.0, BSD-3-Clause, BSD-3-Clause~Adobe, Expat, Expa |
| libgssapi-krb5-2 | 1.21.3-5+deb13u1 | krb5 | siehe /usr/share/doc/libgssapi-krb5-2/copyright |
| libgstreamer-gl1.0-0 | 1.26.2-1+deb13u2 | gst-plugins-base1.0 | BSD (2 clause), BSD (3 clause), BSD-3-clause, CC-BY-SA-4.0, GPL-2+, LGPL, LGPL-2+, LGPL-2.1+, MIT/X11 (BSD like) LGPL-2+ |
| libgstreamer-plugins-base1.0-0 | 1.26.2-1+deb13u2 | gst-plugins-base1.0 | BSD (2 clause), BSD (3 clause), BSD-3-clause, CC-BY-SA-4.0, GPL-2+, LGPL, LGPL-2+, LGPL-2.1+, MIT/X11 (BSD like) LGPL-2+ |
| libgstreamer1.0-0 | 1.26.2-2 | gstreamer1.0 | CC-BY-SA-4.0, GFDL, GPL-2+, GPL-3+, LGPL, LGPL-2+, LGPL-2.1+, MPL-2.0, public-domain |
| libgtk-3-0t64 | 3.24.49-3 | gtk+3.0 | Apache-2.0, CC-BY-SA-4.0, Expat, GPL-3+, LGPL-2+, LGPL-2+ and LGPL-2.1+ and Expat, LGPL-2+ and ZPL-2.1, LGPL-2+ or SWL,  |
| libgtk-3-common | 3.24.49-3 | gtk+3.0 | Apache-2.0, CC-BY-SA-4.0, Expat, GPL-3+, LGPL-2+, LGPL-2+ and LGPL-2.1+ and Expat, LGPL-2+ and ZPL-2.1, LGPL-2+ or SWL,  |
| libgudev-1.0-0 | 238-6 | libgudev | LGPL-2+ |
| libharfbuzz-icu0 | 10.2.0-1+deb13u1 | harfbuzz | Apache-2.0, CC0-1.0, Expat, FSFAP, FSFUL, FSFULLR, GPL-2+ with AutoConf exception, GPL-2+ with Font exception, GPL-2+ wi |
| libharfbuzz0b | 10.2.0-1+deb13u1 | harfbuzz | Apache-2.0, CC0-1.0, Expat, FSFAP, FSFUL, FSFULLR, GPL-2+ with AutoConf exception, GPL-2+ with Font exception, GPL-2+ wi |
| libheif-plugin-dav1d | 1.23.4-1~deb13u1 | libheif | BSD-2-clause, BSD-3-clause, BSD-4-Clause-UC, BSL-1.0, Expat, GPL-3+, LGPL-3+, LGPL-3+ and BSD-2-clause |
| libheif-plugin-libde265 | 1.23.4-1~deb13u1 | libheif | BSD-2-clause, BSD-3-clause, BSD-4-Clause-UC, BSL-1.0, Expat, GPL-3+, LGPL-3+, LGPL-3+ and BSD-2-clause |
| libheif1 | 1.23.4-1~deb13u1 | libheif | BSD-2-clause, BSD-3-clause, BSD-4-Clause-UC, BSL-1.0, Expat, GPL-3+, LGPL-3+, LGPL-3+ and BSD-2-clause |
| libhidapi-hidraw0 | 0.14.0-1+b2 | hidapi | BSD-3-clause, GPL-2+, GPL-3+ with Autoconf exception, GPL-3.0, GPL-3.0 or BSD-3-clause or HIDAPI, HIDAPI |
| libhogweed6t64 | 3.10.1-1 | nettle | Expat, GAP, GPL-2, GPL-2+, GPL-3+ with Autoconf exception, LGPL-2+, LGPL-3+, LGPL-3+ or GPL-2+, public-domain |
| libhunspell-1.7-0 | 1.7.2+really1.7.2-10+b4 | hunspell | MPL 1.1/GPL 2.0/LGPL 2.1 |
| libhwy1t64 | 1.2.0-2+b2 | highway | Apache-2.0 |
| libhyphen0 | 2.8.8-7+b2 | hyphen | GPL-2+, GPL-2+ or LGPL-2.1+ or MPL-1.1+, LGPL-2.1+, MPL-1.1+ |
| libibverbs1 | 56.1-1 | rdma-core | BSD-2-clause, BSD-2-clause or GPL-2, BSD-3-clause, BSD-3-clause or GPL-2, BSD-MIT, BSD-MIT or GPL-2, CC0, CPL-1.0, CPL-1 |
| libice6 | 2:1.1.1-1 | libice | siehe /usr/share/doc/libice6/copyright |
| libicu76 | 76.1-4 | icu | GPL-3, MIT |
| libid3tag0 | 0.16.3-1 | libid3tag | GPL-2+ |
| libidn12 | 1.43-1 | libidn | Expat, FSFAP, FSFAP-no-warranty, GFDL-NIV-1.3+, GPL-2+, GPL-2+-Autoconf, GPL-2+-Autoconf-Archive, GPL-3+, LGPL-3+, LGPL- |
| libidn2-0 | 2.3.8-2 | libidn2 | Expat, GPL-2+, GPL-3+, LGPL-3+, LGPL-3+ or GPL-2+, Unicode |
| libiec61883-0 | 1.2.0-7 | libiec61883 | GPL-2+, LGPL-2+, LGPL-2.1+ |
| libijs-0.35 | 0.35-15.2 | ijs | Expat, Expat~X, Expat~X with X exception, GAP, GAP~Makefile.in, GAP~configure, GPL-2+, GPL-2+ with Autoconf exception |
| libimlib2t64 | 1.12.4-2 | imlib2 | imlib2-license |
| libinih1 | 59-1 | libinih | BSD-3-Clause |
| libinput-bin | 1.28.1-1+deb13u1 | libinput | Expat, GPL-2 |
| libinput10 | 1.28.1-1+deb13u1 | libinput | Expat, GPL-2 |
| libiperf0 | 3.18-2+deb13u2 | iperf3 | BSD-2-clause, BSD-3-clause, BSD-3-clause-iperf, BSD-3-clause-iperf+MIT/X11+BSD-3-clause, FSF-permissive1, FSF-permissive |
| libipsec-mb2 | 2.0-1+b1 | intel-ipsec-mb | BSD-3-clause, GPL-2+ |
| libjansson4 | 2.14-2+b3 | jansson | Expat |
| libjavascriptcoregtk-4.1-0 | 2.54.0-1~deb13u3 | webkit2gtk | AFL-2.0, AFL-2.0 or LGPL-2+, Apache-2.0, BSD-2-Clause-Patent, BSD-2-clause, BSD-2-clause or BSL-1.0, BSD-2-clause or Exp |
| libjbig0 | 2.1-6.1+b2 | jbigkit | GPL-2+ |
| libjbig2dec0 | 0.20-1+deb13u1 | jbig2dec | AGPL-3+, BSD-2-clause, GPL-3+, LGPL-2.1+, pubic-domain, public-domain |
| libjpeg62-turbo | 1:2.1.5-4 | libjpeg-turbo | BSD-3-clause, BSD-BY-LC-NE, Expat, NTP, Zlib, zlib |
| libjq1 | 1.7.1-6+deb13u4 | jq | CC-BY-3.0, Expat, GPL-2.0+, MIT |
| libjson-c5 | 0.18+ds-1 | json-c | Expat |
| libjudydebian1 | 1.0.5-5.1 | judy | siehe /usr/share/doc/libjudydebian1/copyright |
| libjxl0.11 | 0.11.2-0.1~deb13u3 | jpeg-xl | BSD-3-clause-Google, ISC-License |
| libk5crypto3 | 1.21.3-5+deb13u1 | krb5 | siehe /usr/share/doc/libk5crypto3/copyright |
| libkeyutils1 | 1.6.3-6 | keyutils | GPL-2+, LGPL-2+ |
| libklibc | 2.0.14-1 | klibc | BSD/GPL |
| libkmod2 | 34.2-2 | kmod | GPL-2+, LGPL-2.1+ |
| libkrb5-3 | 1.21.3-5+deb13u1 | krb5 | siehe /usr/share/doc/libkrb5-3/copyright |
| libkrb5support0 | 1.21.3-5+deb13u1 | krb5 | siehe /usr/share/doc/libkrb5support0/copyright |
| libksba8 | 1.6.7-2+b1 | libksba | FSFUL, LGPL-2.1-or-later |
| liblastlog2-2 | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| liblcms2-2 | 2.16-2+deb13u2 | lcms2 | GPL-2+, GPL-3, IJG, MIT |
| libldap2 | 2.6.10+dfsg-1 | openldap | BSD-3-clause, BSD-3-clause-California, BSD-3-clause-variant, BSD-4-clause-California, Beerware, Expat, Expat-ISC, Expat- |
| liblerc4 | 4.0.0+ds-5 | lerc | Apache-2.0 |
| libllvm19 | 1:19.1.7-3+b1 | llvm-toolchain-19 | APACHE-2-LLVM-EXCEPTIONS, BSD-3-Clause, BSD-3-clause, MIT, Python, solar-public-domain |
| liblocale-gettext-perl | 1.07-7+b1 | liblocale-gettext-perl | Artistic, Artistic or GPL-1+, GPL-1+ |
| liblsof0 | 4.99.4+dfsg-2 | lsof | BSD-4-clause, FSFAP, GPL-2+, PD, Purdue |
| liblvm2cmd2.03 | 2.03.31-2 | lvm2 | BSD-2-Clause, GPL-2.0, GPL-2.0+, LGPL-2.1 |
| liblz4-1 | 1.10.0-4 | lz4 | BSD-2-clause, BSD-2-clause or GPL-2+, GPL-2+ |
| liblzma5 | 5.8.1-1+deb13u2 | xz-utils | 0BSD, Different licenses apply to different files in this package. Here, FSFUL, FSFULLR, GPL-2+, GPL-3.0-or-later-WITH-A |
| liblzo2-2 | 2.10-3+b1 | lzo2 | GPL-2+ |
| libmanette-0.2-0 | 0.2.12-1 | libmanette | LGPL-2.1+ |
| libmd0 | 1.1.0-2+b1 | libmd | BSD-2-clause, BSD-2-clause-NetBSD, BSD-3-clause, BSD-3-clause-Aaron-D-Gifford, Beerware, ISC, public-domain-md4, public- |
| libmenu-cache-bin | 1.1.1-1 | menu-cache | GPL-3+, LGPL-2.1+ |
| libmenu-cache3 | 1.1.1-1 | menu-cache | GPL-3+, LGPL-2.1+ |
| libmm-glib0 | 1.24.0-1+deb13u1 | modemmanager | GPL-2.0, GPL-2.0+, GPL-3.0+, LGPL-2.0+ |
| libmnl0 | 1.0.5-3 | libmnl | GPL-2+, LGPL-2.1 |
| libmount1 | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| libmp3lame0 | 3.100-6+b3 | lame | BSD-3-clause, GPL-1+, LGPL-2+, LGPL-2.1+, zlib/libpng |
| libmpfr6 | 4.2.2-1 | mpfr4 | siehe /usr/share/doc/libmpfr6/copyright |
| libmpg123-0t64 | 1.32.10-1+deb13u1 | mpg123 | LGPL-2.1 |
| libmtdev1t64 | 1.1.7-1 | mtdev | Expat |
| libnbd0 | 1.22.2-1+b1 | libnbd | BSD-3-Clause, LGPL-2.0+ |
| libncurses6 | 6.5+20250216-2 | ncurses | siehe /usr/share/doc/libncurses6/copyright |
| libncursesw6 | 6.5+20250216-2 | ncurses | siehe /usr/share/doc/libncursesw6/copyright |
| libndctl6 | 81-1 | ndctl | CC0-1.0, Expat, GPL-2, LGPL-2.1 |
| libndp0 | 1.9-1+b1 | libndp | LGPL-2.1+ |
| libnettle8t64 | 3.10.1-1 | nettle | Expat, GAP, GPL-2, GPL-2+, GPL-3+ with Autoconf exception, LGPL-2+, LGPL-3+, LGPL-3+ or GPL-2+, public-domain |
| libnewt0.52 | 0.52.25-1 | newt | GPL-2+, LGPL-2 |
| libnfs14 | 5.0.2-1+deb13u1 | libnfs | BSD-2-clause, BSD-3-Clause, GPL-3+, LGPL-2.1+ |
| libnftables1 | 1.1.3-1 | nftables | CC-BY-SA-4.0, GPL-2, GPL-2+ |
| libnftnl11 | 1.2.9-1 | libnftnl | GPL-2, GPL-2+ |
| libnghttp2-14 | 1.64.0-1.1+deb13u1 | nghttp2 | BSD-2-clause, Expat, GPL-3+ with autoconf exception, MIT, all-permissive |
| libnghttp3-9 | 1.8.0-1 | nghttp3 | FSFAP, FSFUL, FSFULLR, FSFULLR and MIT, GPL-2+ with Autoconf generic exception, GPL-2+ with Libtool Exception, GPL-3+, G |
| libngtcp2-16 | 1.11.0-1+deb13u1 | ngtcp2 | FSFAP, FSFUL, FSFULLR, FSFULLR and MIT, GPL-2+ with Autoconf generic exception, GPL-2+ with Libtool Exception, GPL-3+, G |
| libngtcp2-crypto-gnutls8 | 1.11.0-1+deb13u1 | ngtcp2 | FSFAP, FSFUL, FSFULLR, FSFULLR and MIT, GPL-2+ with Autoconf generic exception, GPL-2+ with Libtool Exception, GPL-3+, G |
| libnl-3-200 | 3.7.0-2 | libnl3 | src/nl-addr-add.c |
| libnl-route-3-200 | 3.7.0-2 | libnl3 | src/nl-addr-add.c |
| libnm0 | 1.52.1-1 | network-manager | GFDL-NIV-1.1+, GPL-2+, LGPL-2.1+ |
| libnma-common | 1.10.6-5 | libnma | GPL-2+, LGPL-2+, LGPL-2.1+ |
| libnma0 | 1.10.6-5 | libnma | GPL-2+, LGPL-2+, LGPL-2.1+ |
| libnpth0t64 | 1.8-3 | npth | LGPL-2.1+ |
| libnspr4 | 2:4.36-1 | nspr | MPL-2.0 |
| libnss3 | 2:3.110-1+deb13u4 | nss | BSD-3, MPL-2.0, Zlib, public-domain |
| libnuma1 | 2.0.19-1 | numactl | siehe /usr/share/doc/libnuma1/copyright |
| libnvcuvid1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-cfg1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-encode1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-fbc1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-gpucomp | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-ml1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-nvvm4 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-nvvm704 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-opticalflow1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-pkcs11-openssl3 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-present | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-ptxjitcompiler1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-sandboxutils | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvidia-tileiras | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvme1t64 | 1.13-2 | libnvme | Apache-2.0, CC0, GPL-2, LGPL-2.1+, MIT |
| libnvoptix1 | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| libnvpair3linux | 2.3.9-0+deb13u1 | zfs-linux | Apache-2.0, BSD-2-clause, BSD-3-clause, CDDL-1.0, Expat, Expat~Unicode, GPL-2+, GPL-2+ with autoconf exception, PERMISSI |
| libobrender32v5 | 3.6.1-12+b2 | openbox | BSD-3-clause, GPL-2+, GPL-3+ |
| libobt2v5 | 3.6.1-12+b2 | openbox | BSD-3-clause, GPL-2+, GPL-3+ |
| libogg0 | 1.3.5-3+b2 | libogg | BSD-3-clause, rfc3533-license, rfc5334-license |
| libonig5 | 6.9.9-1+b1 | libonig | BSD-2-clause, GPL-2+ |
| libopencore-amrnb0 | 0.1.6-1+b2 | opencore-amr | siehe /usr/share/doc/libopencore-amrnb0/copyright |
| libopencore-amrwb0 | 0.1.6-1+b2 | opencore-amr | siehe /usr/share/doc/libopencore-amrwb0/copyright |
| libopenjp2-7 | 2.5.3-2.1~deb13u2 | openjpeg2 | BSD-2, BSD-3, LIBPNG, LIBTIFF, LIBTIFF-GLARSON, LIBTIFF-PIXAR, MIT, ZLIB |
| libopus0 | 1.5.2-2 | opus | BSD-2-clause, BSD-3-clause |
| liborc-0.4-0t64 | 1:0.4.41-1 | orc | siehe /usr/share/doc/liborc-0.4-0t64/copyright |
| libp11-kit0 | 0.25.5-3 | p11-kit | Apache-2.0, BSD-3-clause, FSFAP, FSFULLR, GPL-2+ with Autoconf-data exception, GPL-3+ with Autoconf-data exception, ISC, |
| libpam-modules | 1.7.0-5 | pam | BSD-3-clause or GPL, BSD-tcp_wrappers, Beerware, GPL-2, GPL-2+, GPL-3, GPL-3+ with Bison exception, LGPL-2+, public-doma |
| libpam-modules-bin | 1.7.0-5 | pam | BSD-3-clause or GPL, BSD-tcp_wrappers, Beerware, GPL-2, GPL-2+, GPL-3, GPL-3+ with Bison exception, LGPL-2+, public-doma |
| libpam-runtime | 1.7.0-5 | pam | BSD-3-clause or GPL, BSD-tcp_wrappers, Beerware, GPL-2, GPL-2+, GPL-3, GPL-3+ with Bison exception, LGPL-2+, public-doma |
| libpam-systemd | 257.13-1~deb13u1 | systemd | CC0-1.0, Expat, GPL-2 with Linux-syscall-note exception, GPL-2+, LGPL-2.1+, public-domain |
| libpam0g | 1.7.0-5 | pam | BSD-3-clause or GPL, BSD-tcp_wrappers, Beerware, GPL-2, GPL-2+, GPL-3, GPL-3+ with Bison exception, LGPL-2+, public-doma |
| libpango-1.0-0 | 1.56.3-1 | pango1.0 | Apache-2, Apache-2 and Bitstream-Vera and OFL-1.1, Bitstream-Vera, Chromium-BSD-style, Example, ICU, LGPL-2+, LGPL-2+ an |
| libpangocairo-1.0-0 | 1.56.3-1 | pango1.0 | Apache-2, Apache-2 and Bitstream-Vera and OFL-1.1, Bitstream-Vera, Chromium-BSD-style, Example, ICU, LGPL-2+, LGPL-2+ an |
| libpangoft2-1.0-0 | 1.56.3-1 | pango1.0 | Apache-2, Apache-2 and Bitstream-Vera and OFL-1.1, Bitstream-Vera, Chromium-BSD-style, Example, ICU, LGPL-2+, LGPL-2+ an |
| libpangoxft-1.0-0 | 1.56.3-1 | pango1.0 | Apache-2, Apache-2 and Bitstream-Vera and OFL-1.1, Bitstream-Vera, Chromium-BSD-style, Example, ICU, LGPL-2+, LGPL-2+ an |
| libpaper2 | 2.2.5-0.3+b2 | libpaper | Expat, Expat or GPL-2+, GPL-2, GPL-3+, X11, public-domain |
| libparted2t64 | 3.6-5 | parted | siehe /usr/share/doc/libparted2t64/copyright |
| libpci3 | 1:3.13.0-2 | pciutils | GPL-2+ |
| libpciaccess0 | 0.17-3+b3 | libpciaccess | siehe /usr/share/doc/libpciaccess0/copyright |
| libpcre2-8-0 | 10.46-1~deb13u3 | pcre2 | BSD-2-clause, BSD-3-clause, BSD-3-clause-Cambridge with BINARY LIBRARY-LIKE PACKAGES exception, X11, public-domain |
| libperl5.40 | 5.40.1-6+deb13u1 | perl | Artistic, Artistic or GPL-1+, Artistic or GPL-1+ or Artistic-dist, Artistic-2, Artistic-dist, BSD-3-clause, BSD-3-clause |
| libpixman-1-0 | 0.44.0-3 | pixman | siehe /usr/share/doc/libpixman-1-0/copyright |
| libpmem1 | 1.13.1-1.1+b1 | pmdk | BSD-3-clause, CDDL |
| libpng16-16t64 | 1.6.48-1+deb13u6 | libpng1.6 | Apache-2.0, BSD-3-clause, BSD-like-with-advertising-clause, GPL-2+, GPL-2+ or BSD-like-with-advertising-clause, expat, l |
| libpolkit-agent-1-0 | 126-2 | policykit-1 | Expat, LGPL-2.0+, LGPL-2.0+ and Expat |
| libpolkit-gobject-1-0 | 126-2 | policykit-1 | Expat, LGPL-2.0+, LGPL-2.0+ and Expat |
| libpopt0 | 1.19+dfsg-2 | popt | GPL-2+, expat, public-domain |
| libproc2-0 | 2:4.0.4-9 | procps | GPL-2.0+, LGPL-2.0+, LGPL-2.1+ |
| libproxy1v5 | 0.5.9-1 | libproxy | GPL-2+, GPL-3+, LGPL-2.1+, LGPL-2.1+ or GPL-2+ or NPL-1.1, MPL-1.1, NPL-1.1 |
| libpsl5t64 | 0.21.2-1.1+b1 | libpsl | Chromium, MIT, gnulib |
| libpulse0 | 17.0+dfsg1-2+b1 | pulseaudio | GPL-2+, LGPL-2+, LGPL-2.1+, other |
| libpython3-stdlib | 3.13.5-1 | python3-defaults | siehe /usr/share/doc/libpython3-stdlib/copyright |
| libpython3.13-minimal | 3.13.5-2+deb13u5 | python3.13 | * Permission to use this software in any way is granted without, * Permission to use, copy, modify, and distribute this  |
| libpython3.13-stdlib | 3.13.5-2+deb13u5 | python3.13 | siehe /usr/share/doc/libpython3.13-stdlib/copyright |
| librados2 | 18.2.7+ds-1+deb13u1 | ceph | APSL-2.0, Apache-2.0, BSD 3 clause, BSD 3-clause, BSD-2-clause, BSD-3-clause, BSL-1.0, CC-BY-SA-3.0, Creative Commons At |
| librav1e0.7 | 0.7.1-9+b2 | rust-rav1e | BSD-2-Clause, BSD-2-clause, ISC |
| libraw1394-11 | 2.1.2-2+b2 | libraw1394 | This package is free software; you can redistribute it and/or |
| librbd1 | 18.2.7+ds-1+deb13u1 | ceph | APSL-2.0, Apache-2.0, BSD 3 clause, BSD 3-clause, BSD-2-clause, BSD-3-clause, BSL-1.0, CC-BY-SA-3.0, Creative Commons At |
| librdmacm1t64 | 56.1-1 | rdma-core | BSD-2-clause, BSD-2-clause or GPL-2, BSD-3-clause, BSD-3-clause or GPL-2, BSD-MIT, BSD-MIT or GPL-2, CC0, CPL-1.0, CPL-1 |
| libreadline8t64 | 8.2-6 | readline | GFDL-NIV-1.3+, GPL-2+, GPL-3, GPL-3+, ISC-no-attribution |
| librsvg2-2 | 2.60.0+dfsg-1+deb13u1 | librsvg | 0BSD, Apache-2.0, Apache-2.0, and BSD-2-clause, and BSD-3-clause, and Expat, and Apache-2.0 or Expat or 0BSD, and Apache |
| librtmp1 | 2.4+20151223.gitfa8646d.1-2+b5 | rtmpdump | siehe /usr/share/doc/librtmp1/copyright |
| libsasl2-2 | 2.1.28+dfsg1-9 | cyrus-sasl2 | BSD-2-clause, BSD-2-clause and MIT-CMU, BSD-2.2-clause, BSD-3-Clause-Attribution, BSD-3-Clause-Attribution and IBM-as-is |
| libsasl2-modules-db | 2.1.28+dfsg1-9 | cyrus-sasl2 | BSD-2-clause, BSD-2-clause and MIT-CMU, BSD-2.2-clause, BSD-3-Clause-Attribution, BSD-3-Clause-Attribution and IBM-as-is |
| libsctp1 | 1.0.21+dfsg-1 | lksctp-tools | BSD-3-clause, GPL-2.0+, LGPL-2.1+ |
| libseccomp2 | 2.6.0-2 | libseccomp | LGPL-2.1 |
| libsecret-1-0 | 0.21.7-1 | libsecret | Apache-2.0, BSD-3-clause, GPL-2+, LGPL-2.1+ |
| libsecret-common | 0.21.7-1 | libsecret | Apache-2.0, BSD-3-clause, GPL-2+, LGPL-2.1+ |
| libselinux1 | 3.8.1-1 | libselinux | GPL-2, public-domain |
| libsemanage-common | 3.8.1-1 | libsemanage | GPL-2, LGPL-2.1+ |
| libsemanage2 | 3.8.1-1 | libsemanage | GPL-2, LGPL-2.1+ |
| libsensors-config | 1:3.6.2-2 | lm-sensors | GPL-2, GPL-2+, LGPL-2.1+, Linux-man-pages-copyleft |
| libsensors5 | 1:3.6.2-2 | lm-sensors | GPL-2, GPL-2+, LGPL-2.1+, Linux-man-pages-copyleft |
| libsepol2 | 3.8.1-1 | libsepol | GPL-2, GPL-2+, LGPL-2.1+, Zlib |
| libsframe1 | 2.44-3 | binutils | siehe /usr/share/doc/libsframe1/copyright |
| libsgutils2-1.48 | 1.48-3~deb13u1 | sg3-utils | siehe /usr/share/doc/libsgutils2-1.48/copyright |
| libsharpyuv0 | 1.5.0-0.1 | libwebp | Apache-2.0, BSD-3-Clause |
| libshout3 | 2.4.6-1+b3 | libshout | FSFUL, FSFULLR, FSFULLR and GPL-2+ with Libtool exception, FSFULLR~Makefile.in, GPL-2+, GPL-2+ with Autoconf exception,  |
| libslang2 | 2.3.3-5+b2 | slang2 | GPL-2+ |
| libsm6 | 2:1.2.6-1 | libsm | siehe /usr/share/doc/libsm6/copyright |
| libsmartcols1 | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| libsndfile1 | 1.2.2-2+deb13u1 | libsndfile | Apache-2.0, BSD-2-clause, BSD-3-clause, BSD-3-clause and LGPL-2.1+, FSFAP, GPL-2+, GPL-3+, LGPL-2+, LGPL-2.1+, NTP, gsm, |
| libsoup-3.0-0 | 3.6.5-3 | libsoup3 | Expat, LGPL-2+, LGPL-2.1+, MPL-2.0, MPL-2.0 or RSA-Other, RSA-Other |
| libsoup-3.0-common | 3.6.5-3 | libsoup3 | Expat, LGPL-2+, LGPL-2.1+, MPL-2.0, MPL-2.0 or RSA-Other, RSA-Other |
| libspectre1 | 0.2.12-1+b2 | libspectre | GPL-2+ |
| libspeex1 | 1.2.1-3 | speex | BSD-3-Clause, BSD-3-Clause and custom-1, GFDL-1.1-or-later, LGPL-2.0-or-later, custom-1 |
| libsqlite3-0 | 3.46.1-7+deb13u2 | sqlite3 | GPL-2+, public-domain |
| libss2 | 1.47.2-3+b12 | e2fsprogs | 0BSD, Apache-2, BSD-3-Clause, BSD-3-Clause-Variant, BSD-4-Clause-CMU, Expat, GPL or MIT-US-export, GPL-2, GPL-2+, GPL-2+ |
| libssh2-1t64 | 1.11.1-1+deb13u2 | libssh2 | BSD3, ISC |
| libssl3t64 | 3.5.7-1~deb13u3 | openssl | Apache-2.0, Artistic, Artistic or GPL-1+, GPL-1+ |
| libstartup-notification0 | 0.12-8 | startup-notification | part MIT, part LGPL, see below. |
| libstdc++6 | 14.2.0-19 | gcc-14 | siehe /usr/share/doc/libstdc++6/copyright |
| libsvtav1enc2 | 2.3.0+dfsg-1 | svt-av1 | BSD-2-clause, BSD-3-Clause-Clear, BSD-3-clause, Expat, ISC, LGPL-2.1+ |
| libsysfs2 | 2.1.1-7 | sysfsutils | GPL-2+, LGPL-2.1+ |
| libsystemd-shared | 257.13-1~deb13u1 | systemd | CC0-1.0, Expat, GPL-2 with Linux-syscall-note exception, GPL-2+, LGPL-2.1+, public-domain |
| libsystemd0 | 257.13-1~deb13u1 | systemd | CC0-1.0, Expat, GPL-2 with Linux-syscall-note exception, GPL-2+, LGPL-2.1+, public-domain |
| libtag2 | 2.0.2-2 | taglib | BSD-2-clause, LGPL-2.1, LGPL-2.1 or MPL-1.1, MPL-1.1 |
| libtasn1-6 | 4.20.0-2+deb13u1 | libtasn1-6 | siehe /usr/share/doc/libtasn1-6/copyright |
| libteamdctl0 | 1.31-1+b2 | libteam | BSD-3-clause, BSD-3-clause or GPL-2, GPL-2, LGPL-2.1+ |
| libtext-charwidth-perl | 0.04-11+b4 | libtext-charwidth-perl | Artistic, Artistic or GPL-1+, GPL-1+ |
| libtext-iconv-perl | 1.7-8+b4 | libtext-iconv-perl | Artistic, Artistic or GPL-1+, GPL-1+ |
| libtext-wrapi18n-perl | 0.06-10 | libtext-wrapi18n-perl | Artistic, Artistic or GPL-1+, GPL-1+ |
| libthai-data | 0.1.29-2 | libthai | GPL-2+, LGPL-2.1+ |
| libthai0 | 0.1.29-2+b1 | libthai | GPL-2+, LGPL-2.1+ |
| libtheora0 | 1.2.0~alpha1+dfsg-6 | libtheora | BSD-3-Clause, BSD-4-Clause, GPL-2+, LGPL-2+ |
| libtheoradec1 | 1.2.0~alpha1+dfsg-6 | libtheora | BSD-3-Clause, BSD-4-Clause, GPL-2+, LGPL-2+ |
| libtheoraenc1 | 1.2.0~alpha1+dfsg-6 | libtheora | BSD-3-Clause, BSD-4-Clause, GPL-2+, LGPL-2+ |
| libtiff6 | 4.7.0-3+deb13u3 | tiff | Hylafax |
| libtinfo6 | 6.5+20250216-2 | ncurses | BSD-3-clause, MIT/X11, X11 |
| libtirpc-common | 1.3.6+ds-1 | libtirpc | BSD-2-Clause, BSD-3-Clause, BSD-4-Clause, GPL-2, LGPL-2.1+, PERMISSIVE, __AUTO_PERMISSIVE__ |
| libtirpc3t64 | 1.3.6+ds-1 | libtirpc | BSD-2-Clause, BSD-3-Clause, BSD-4-Clause, GPL-2, LGPL-2.1+, PERMISSIVE, __AUTO_PERMISSIVE__ |
| libtraceevent1 | 1:1.8.4-2 | libtraceevent | GPL-2.0, LGPL-2.1 |
| libtwolame0 | 0.4.0-2+b2 | twolame | LGPL-2+ |
| libudev1 | 257.13-1~deb13u1 | systemd | CC0-1.0, Expat, GPL-2 with Linux-syscall-note exception, GPL-2+, LGPL-2.1+, public-domain |
| libudfread0 | 1.1.2-1+b2 | libudfread | GPL-2+ with autoconf-macro exception, LGPL-2.1+ |
| libudisks2-0 | 2.10.1-12.1+deb13u2 | udisks2 | GPL-2+, LGPL-2+ |
| libunistring5 | 1.3-2 | libunistring | BSD-3-clause or LGPL-2.1+, BSD-3-clause or LGPL-3+, FreeSoftware, GFDL-1.2+ or GPL-3+ or LGPL-3, GFDL-1.3+, GPL-2+, GPL- |
| libunwind8 | 1.8.1-0.1 | libunwind | Expat, GPL-2+ |
| liburcu8t64 | 0.15.2-2 | liburcu | BSD-2-Clause, CC-BY-4.0, CC-BY-4.0 or Expat or GPL-2 or LGPL-2.1, CC0-1.0, Expat, Expat~Boehm, FSFAP, GPL-2, GPL-2 with  |
| libusb-1.0-0 | 2:1.0.28-1 | libusb-1.0 | FSFAP, GPL-2+, LGPL-2.1+, MIT |
| libutempter0 | 1.2.1-4 | libutempter | BSD-2-Clause, LGPL-2.1 |
| libuuid1 | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| libuutil3linux | 2.3.9-0+deb13u1 | zfs-linux | Apache-2.0, BSD-2-clause, BSD-3-clause, CDDL-1.0, Expat, Expat~Unicode, GPL-2+, GPL-2+ with autoconf exception, PERMISSI |
| libv4l-0t64 | 1.30.1-1 | v4l-utils | BSD-2-clause, BSD-3-clause, BSD-3-clause or GPL-2, BSD-3-clause or GPL-2+, BSD-3-clause or LGPL-2.1, Expat, FSFULLR, GPL |
| libv4lconvert0t64 | 1.30.1-1 | v4l-utils | BSD-2-clause, BSD-3-clause, BSD-3-clause or GPL-2, BSD-3-clause or GPL-2+, BSD-3-clause or LGPL-2.1, Expat, FSFULLR, GPL |
| libvisual-0.4-0 | 0.4.2-2+b2 | libvisual | GPL-2+, LGPL-2+, LGPL-2.1+ |
| libvolume-key1 | 0.3.12-9 | volume-key | GPL-2, GPL-2+, MPL-1.1 or GPL-2+ or LGPL-2.1+ |
| libvorbis0a | 1.3.7-3 | libvorbis | BSD-3-Clause, RFC-special |
| libvorbisenc2 | 1.3.7-3 | libvorbis | BSD-3-Clause, RFC-special |
| libvpx9 | 1.15.0-2.1+deb13u1 | libvpx | BSD-3-Clause, ISC, public-domain |
| libvulkan1 | 1.4.309.0-1 | vulkan-loader | Apache-2.0, MIT, MIT or Apache-2.0 |
| libwacom-common | 2.14.0-1 | libwacom | MIT, permissive |
| libwacom9 | 2.14.0-1 | libwacom | MIT, permissive |
| libwavpack1 | 5.8.1-1 | wavpack | BSD-2-clause, BSD-3-clause, public-domain |
| libwayland-client0 | 1.23.1-3 | wayland | X11 |
| libwayland-cursor0 | 1.23.1-3 | wayland | X11 |
| libwayland-egl1 | 1.23.1-3 | wayland | X11 |
| libwayland-server0 | 1.23.1-3 | wayland | X11 |
| libwebkit2gtk-4.1-0 | 2.54.0-1~deb13u3 | webkit2gtk | AFL-2.0, AFL-2.0 or LGPL-2+, Apache-2.0, BSD-2-Clause-Patent, BSD-2-clause, BSD-2-clause or BSL-1.0, BSD-2-clause or Exp |
| libwebp7 | 1.5.0-0.1 | libwebp | Apache-2.0, BSD-3-Clause |
| libwebpdemux2 | 1.5.0-0.1 | libwebp | Apache-2.0, BSD-3-Clause |
| libwebpmux3 | 1.5.0-0.1 | libwebp | Apache-2.0, BSD-3-Clause |
| libwrap0 | 7.6.q-36 | tcp-wrappers | BSD-3-clause, SSH, TCP-wrappers |
| libwtmpdb0 | 0.73.0-3+deb13u1 | wtmpdb | BSD-2-Clause, GPL-2+ |
| libx11-6 | 2:1.8.12-1 | libx11 | siehe /usr/share/doc/libx11-6/copyright |
| libx11-data | 2:1.8.12-1 | libx11 | siehe /usr/share/doc/libx11-data/copyright |
| libx11-xcb1 | 2:1.8.12-1 | libx11 | siehe /usr/share/doc/libx11-xcb1/copyright |
| libxau6 | 1:1.0.11-1 | libxau | siehe /usr/share/doc/libxau6/copyright |
| libxaw7 | 2:1.0.16-1 | libxaw | siehe /usr/share/doc/libxaw7/copyright |
| libxcb-cursor0 | 0.1.5-1 | xcb-util-cursor | MIT/X |
| libxcb-dri3-0 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-dri3-0/copyright |
| libxcb-glx0 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-glx0/copyright |
| libxcb-icccm4 | 0.4.2-1 | xcb-util-wm | GPL-2+, MIT/X Consortium License |
| libxcb-image0 | 0.4.0-2+b2 | xcb-util-image | GPL-2+, MIT/X11 |
| libxcb-keysyms1 | 0.4.1-1 | xcb-util-keysyms | GPL-2+, MIT/X11 |
| libxcb-present0 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-present0/copyright |
| libxcb-randr0 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-randr0/copyright |
| libxcb-render-util0 | 0.3.10-1 | xcb-util-renderutil | Expat, GPL-2+ |
| libxcb-render0 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-render0/copyright |
| libxcb-shape0 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-shape0/copyright |
| libxcb-shm0 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-shm0/copyright |
| libxcb-sync1 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-sync1/copyright |
| libxcb-util1 | 0.4.1-1 | xcb-util | GPL-2+, MIT |
| libxcb-xfixes0 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-xfixes0/copyright |
| libxcb-xkb1 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb-xkb1/copyright |
| libxcb1 | 1.17.0-2+b1 | libxcb | siehe /usr/share/doc/libxcb1/copyright |
| libxcomposite1 | 1:0.4.6-1 | libxcomposite | siehe /usr/share/doc/libxcomposite1/copyright |
| libxcursor1 | 1:1.2.3-1 | libxcursor | siehe /usr/share/doc/libxcursor1/copyright |
| libxcvt0 | 0.1.3-1 | libxcvt | MIT, NTP |
| libxdamage1 | 1:1.1.6-1+b2 | libxdamage | siehe /usr/share/doc/libxdamage1/copyright |
| libxdmcp6 | 1:1.1.5-1 | libxdmcp | siehe /usr/share/doc/libxdmcp6/copyright |
| libxext6 | 2:1.3.4-1+b3 | libxext | siehe /usr/share/doc/libxext6/copyright |
| libxfixes3 | 1:6.0.0-2+b4 | libxfixes | siehe /usr/share/doc/libxfixes3/copyright |
| libxfont2 | 1:2.0.6-1+deb13u1 | libxfont | siehe /usr/share/doc/libxfont2/copyright |
| libxft2 | 2.3.6-1+b4 | xft | siehe /usr/share/doc/libxft2/copyright |
| libxi6 | 2:1.8.2-1 | libxi | siehe /usr/share/doc/libxi6/copyright |
| libxinerama1 | 2:1.1.4-3+b4 | libxinerama | siehe /usr/share/doc/libxinerama1/copyright |
| libxkbcommon-x11-0 | 1.7.0-2 | libxkbcommon | siehe /usr/share/doc/libxkbcommon-x11-0/copyright |
| libxkbcommon0 | 1.7.0-2 | libxkbcommon | siehe /usr/share/doc/libxkbcommon0/copyright |
| libxkbfile1 | 1:1.1.0-1+b4 | libxkbfile | siehe /usr/share/doc/libxkbfile1/copyright |
| libxml2 | 2.12.7+dfsg+really2.9.14-2.1+deb13u3 | libxml2 | ISC, MIT-1 |
| libxmu6 | 2:1.1.3-3+b4 | libxmu | siehe /usr/share/doc/libxmu6/copyright |
| libxmuu1 | 2:1.1.3-3+b4 | libxmu | siehe /usr/share/doc/libxmuu1/copyright |
| libxpm4 | 1:3.5.17-1+deb13u1 | libxpm | siehe /usr/share/doc/libxpm4/copyright |
| libxrandr2 | 2:1.5.4-1+b3 | libxrandr | siehe /usr/share/doc/libxrandr2/copyright |
| libxrender1 | 1:0.9.12-1 | libxrender | siehe /usr/share/doc/libxrender1/copyright |
| libxshmfence1 | 1.3.3-1 | libxshmfence | siehe /usr/share/doc/libxshmfence1/copyright |
| libxslt1.1 | 1.1.35-1.2+deb13u3 | libxslt | siehe /usr/share/doc/libxslt1.1/copyright |
| libxt6t64 | 1:1.2.1-1.2+b2 | libxt | siehe /usr/share/doc/libxt6t64/copyright |
| libxtables12 | 1.8.11-2 | iptables | Artistic, GPL-2, GPL-2+, custom |
| libxtst6 | 2:1.2.5-1 | libxtst | siehe /usr/share/doc/libxtst6/copyright |
| libxxf86vm1 | 1:1.1.4-1+b4 | libxxf86vm | siehe /usr/share/doc/libxxf86vm1/copyright |
| libxxhash0 | 0.8.3-2 | xxhash | BSD-2-clause, BSD-2-clause or GPL-2+, GPL-2+ |
| libyuv0 | 0.0.1904.20250204-1 | libyuv | BSD-3-Clause, public-domain |
| libyyjson0 | 0.10.0+ds-1+b1 | yyjson | Apache-2.0, BSD-3-clause, Expat |
| libz3-4 | 4.13.3-1 | z3 | Expat, GPL-2+ |
| libzfs6linux | 2.3.9-0+deb13u1 | zfs-linux | Apache-2.0, BSD-2-clause, BSD-3-clause, CDDL-1.0, Expat, Expat~Unicode, GPL-2+, GPL-2+ with autoconf exception, PERMISSI |
| libzpool6linux | 2.3.9-0+deb13u1 | zfs-linux | Apache-2.0, BSD-2-clause, BSD-3-clause, CDDL-1.0, Expat, Expat~Unicode, GPL-2+, GPL-2+ with autoconf exception, PERMISSI |
| libzstd1 | 1.5.7+dfsg-1 | libzstd | BSD-3-clause, BSD-3-clause or GPL-2, Expat, GPL-2, zlib |
| linux-base | 4.12.1 | linux-base | GPL-2, LGPL-2.1+ |
| linux-image-6.12.113+deb13-amd64 | 6.12.113-1 | linux-signed-amd64 | BSD-2-clause, GPL-2, GPL-2 or BSD-2-clause, GPL-2+-or-X11, LGPL-2.1, LGPL-2.1 or BSD-2-clause, Unicode-data, Xen-interfa |
| linux-image-amd64 | 6.12.113-1 | linux-signed-amd64 | siehe /usr/share/doc/linux-image-amd64/copyright |
| linux-sysctl-defaults | 4.12.1 | linux-base | GPL-2, LGPL-2.1+ |
| live-boot | 1:20250815~deb13u1 | live-boot | GPL-3+ |
| live-boot-initramfs-tools | 1:20250815~deb13u1 | live-boot | GPL-3+ |
| live-config | 11.0.5 | live-config | GPL-3+ |
| live-config-systemd | 11.0.5 | live-config | GPL-3+ |
| lm-sensors | 1:3.6.2-2 | lm-sensors | GPL-2, GPL-2+, LGPL-2.1+, Linux-man-pages-copyleft |
| login | 1:4.16.0-2+really2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| login.defs | 1:4.17.4-2 | shadow | BSD-3-clause, GPL-1, GPL-2+ |
| logrotate | 3.22.0-1 | logrotate | BSD-3-Clause, GPL-2, GPL-3+ |
| logsave | 1.47.2-3+b12 | e2fsprogs | 0BSD, Apache-2, BSD-3-Clause, BSD-3-Clause-Variant, BSD-4-Clause-CMU, Expat, GPL or MIT-US-export, GPL-2, GPL-2+, GPL-2+ |
| lshw | 02.19.git.2021.06.19.996aaad9c7-2.1 | lshw | siehe /usr/share/doc/lshw/copyright |
| lsof | 4.99.4+dfsg-2 | lsof | BSD-4-clause, FSFAP, GPL-2+, PD, Purdue |
| lvm2 | 2.03.31-2 | lvm2 | BSD-2-Clause, GPL-2.0, GPL-2.0+, LGPL-2.1 |
| lxmenu-data | 0.1.6-3 | lxmenu-data | GPL-2+, GPL-3+ |
| lxpolkit | 0.5.6-2 | lxsession | GPL-2+, LGPL-3+, MIT |
| lxsession-data | 0.5.6-2 | lxsession | GPL-2+, LGPL-3+, MIT |
| mawk | 1.3.4.20250131-1 | mawk | CC-BY-3.0, GPL-2.0-only, X11 |
| mdadm | 4.4-11 | mdadm | GPL-2+ |
| media-types | 13.0.0 | media-types | ad-hoc |
| memtest86+ | 7.20-1 | memtest86+ | GPL-2 |
| mesa-libgallium | 25.0.7-2+deb13u1 | mesa | Apache-2.0, BSD-2-clause, BSD-3-google, BSL, GPL, GPL-1+, GPL-2, GPL-2 or MIT, Khronos, MIT, MLAA, SGI |
| mount | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| nano | 8.4-1+deb13u1 | nano | GFDL-NIV+, GFDL-NIV+ or GPL-3+, GPL-3+ |
| ncurses-base | 6.5+20250216-2 | ncurses | BSD-3-clause, MIT/X11, X11 |
| ncurses-bin | 6.5+20250216-2 | ncurses | BSD-3-clause, MIT/X11, X11 |
| netbase | 6.5 | netbase | GPL-2 |
| network-manager | 1.52.1-1 | network-manager | GFDL-NIV-1.1+, GPL-2+, LGPL-2.1+ |
| network-manager-applet | 1.36.0-3+b1 | network-manager-applet | GPL-2+, LGPL-2+ |
| nftables | 1.1.3-1 | nftables | CC-BY-SA-4.0, GPL-2, GPL-2+ |
| nm-connection-editor | 1.36.0-3+b1 | network-manager-applet | GPL-2+, LGPL-2+ |
| nvidia-driver-cuda | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| nvidia-kernel-support | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| nvidia-modprobe | 595.91.07-1 | nvidia-modprobe | Expat |
| nvidia-opencl-icd | 595.91.07-1 | nvidia-graphics-drivers | Expat, GPL-2.0+, NVIDIA-graphics-drivers, zlib/libpng |
| nvidia-persistenced | 595.91.07-1 | nvidia-persistenced | Expat |
| nvme-cli | 2.13-2 | nvme-cli | GPL-2, GPL-2+, LGPL-2.1+ |
| ocl-icd-libopencl1 | 2.3.3-1 | ocl-icd | Apache-2.0, BSD-2-Clause |
| openbox | 3.6.1-12+b2 | openbox | BSD-3-clause, GPL-2+, GPL-3+ |
| openssh-client | 1:10.0p1-7+deb13u4 | openssh | BSD-2-clause, BSD-3-clause, Expat-with-advertising-restriction, Mazieres-BSD-style, OpenSSH, Powell-BSD-style, public-do |
| openssh-server | 1:10.0p1-7+deb13u4 | openssh | siehe /usr/share/doc/openssh-server/copyright |
| openssh-sftp-server | 1:10.0p1-7+deb13u4 | openssh | siehe /usr/share/doc/openssh-sftp-server/copyright |
| openssl | 3.5.7-1~deb13u3 | openssl | Apache-2.0, Artistic, Artistic or GPL-1+, GPL-1+ |
| openssl-provider-legacy | 3.5.7-1~deb13u3 | openssl | Apache-2.0, Artistic, Artistic or GPL-1+, GPL-1+ |
| parted | 3.6-5 | parted | siehe /usr/share/doc/parted/copyright |
| passwd | 1:4.17.4-2 | shadow | BSD-3-clause, GPL-1, GPL-2+ |
| pci.ids | 0.0~2025.06.09-1 | pci.ids | BSD-3-clause, GPL-2+, GPL-2+ or BSD-3-clause |
| pciutils | 1:3.13.0-2 | pciutils | GPL-2+ |
| pcmanfm | 1.4.0-1 | pcmanfm | GPL-2+, LGPL-2.1+ |
| perl | 5.40.1-6+deb13u1 | perl | Artistic, Artistic or GPL-1+, Artistic or GPL-1+ or Artistic-dist, Artistic-2, Artistic-dist, BSD-3-clause, BSD-3-clause |
| perl-base | 5.40.1-6+deb13u1 | perl | Artistic, Artistic or GPL-1+, Artistic or GPL-1+ or Artistic-dist, Artistic-2, Artistic-dist, BSD-3-clause, BSD-3-clause |
| perl-modules-5.40 | 5.40.1-6+deb13u1 | perl | Artistic, Artistic or GPL-1+, Artistic or GPL-1+ or Artistic-dist, Artistic-2, Artistic-dist, BSD-3-clause, BSD-3-clause |
| pinentry-curses | 1.3.1-2 | pinentry | GPL-2, GPL-2+, LGPL-3+, LGPL-3+ or GPL-2+, X11 |
| pkexec | 126-2 | policykit-1 | Expat, LGPL-2.0+, LGPL-2.0+ and Expat |
| polkitd | 126-2 | policykit-1 | Expat, LGPL-2.0+, LGPL-2.0+ and Expat |
| poppler-data | 0.4.12-1 | poppler-data | AGPL-3+, BSD-3-cluase, GPL-2, MIT |
| procps | 2:4.0.4-9 | procps | GPL-2.0+, LGPL-2.0+, LGPL-2.1+ |
| python3 | 3.13.5-1 | python3-defaults | siehe /usr/share/doc/python3/copyright |
| python3-dbus | 1.4.0-1 | dbus-python | AFL-2.1, Expat, GPL-2+, GPL-2+ or AFL-2.1, and Expat |
| python3-minimal | 3.13.5-1 | python3-defaults | siehe /usr/share/doc/python3-minimal/copyright |
| python3.13 | 3.13.5-2+deb13u5 | python3.13 | * Permission to use this software in any way is granted without, * Permission to use, copy, modify, and distribute this  |
| python3.13-minimal | 3.13.5-2+deb13u5 | python3.13 | * Permission to use this software in any way is granted without, * Permission to use, copy, modify, and distribute this  |
| rasdaemon | 0.8.3-1 | rasdaemon | GPL-2, GPL-2+ |
| readline-common | 8.2-6 | readline | GFDL-NIV-1.3+, GPL-2+, GPL-3, GPL-3+, ISC-no-attribution |
| runit-helper | 2.16.4 | dh-runit | GPL-3+ |
| sed | 4.9-2+deb13u1 | sed | BSD-4-clause-UC, BSL-1, GFDL-NIV-1.3+, GPL-3+, GPL-3+ and ISC, ISC, X11, pcre |
| sensible-utils | 0.0.25 | sensible-utils | All-permissive, GPL-2+, configure, installsh |
| sg3-utils | 1.48-3~deb13u1 | sg3-utils | siehe /usr/share/doc/sg3-utils/copyright |
| sgml-base | 1.31+nmu1 | sgml-base | GPL-2+ |
| shared-mime-info | 2.4-5+b2 | shared-mime-info | This package is free software; you can redistribute it and/or modify |
| smartmontools | 7.4-3 | smartmontools | BSD-2-Clause, BSD-2-Clause and GPL-2+, Expat-like, GPL-2, GPL-2+, LGPL-2.1+ |
| sqlite3 | 3.46.1-7+deb13u2 | sqlite3 | GPL-2+, public-domain |
| squashfs-tools | 1:4.6.1-1 | squashfs-tools | GPL-2+ |
| sqv | 1.3.0-3+b2 | rust-sequoia-sqv | LGPL-2.0-or-later |
| ssacli | 6.60-8.0 | ssacli | siehe /usr/share/doc/ssacli/copyright |
| ssaducli | 6.60-8.0 | ssaducli | siehe /usr/share/doc/ssaducli/copyright |
| storcli | 007.3604.0000.0000-1 | storcli | siehe /usr/share/doc/storcli/copyright |
| storcli2 | 008.0016.0000.0011-1 | storcli2 | siehe /usr/share/doc/storcli2/copyright |
| stress-ng | 0.19.02-1 | stress-ng | GPL-2+ |
| sudo | 1.9.16p2-3+deb13u2 | sudo | BSD-2-Clause, BSD-3-Clause, GPL-2+, ISC, Zlib, other, public-domain |
| surf | 2.1+git20250419-1 | surf | MIT |
| systemd | 257.13-1~deb13u1 | systemd | CC0-1.0, Expat, GPL-2 with Linux-syscall-note exception, GPL-2+, LGPL-2.1+, public-domain |
| systemd-sysv | 257.13-1~deb13u1 | systemd | CC0-1.0, Expat, GPL-2 with Linux-syscall-note exception, GPL-2+, LGPL-2.1+, public-domain |
| systemd-timesyncd | 257.13-1~deb13u1 | systemd | CC0-1.0, Expat, GPL-2 with Linux-syscall-note exception, GPL-2+, LGPL-2.1+, public-domain |
| sysvinit-utils | 3.14-4 | sysvinit | GPL-2.0, GPL-2.0+, GPL-3.0, LGPL-2.1+ |
| tar | 1.35+dfsg-3.1 | tar | GPL-2+, GPL-3+, GPL-3+ with Bison exception, LGPL-2.1+, LGPL-3+ |
| tint2 | 17.0.1-1.2 | tint2 | GPL-2, GPL-2+, ISC |
| tzdata | 2026e-0+deb13u1 | tzdata | public-domain |
| ucf | 3.0052 | ucf | GPL-2 |
| udev | 257.13-1~deb13u1 | systemd | CC0-1.0, Expat, GPL-2 with Linux-syscall-note exception, GPL-2+, LGPL-2.1+, public-domain |
| udisks2 | 2.10.1-12.1+deb13u2 | udisks2 | GPL-2+, LGPL-2+ |
| usbutils | 1:018-2 | usbutils | CC0-1.0, GPL-2.0, GPL-2.0 or GPL-3.0, GPL-2.0+, GPL-3.0, LGPL-2.1+, MIT |
| user-setup | 1.107 | user-setup | siehe /usr/share/doc/user-setup/copyright |
| util-linux | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| uuid-runtime | 2.41.5-0+deb13u1 | util-linux | BSD-2-clause, BSD-3-clause, BSD-4-clause, BSLA, Expat, GPL-2, GPL-2+, GPL-3+, ISC, LGPL, LGPL-2+, LGPL-2.1+, LGPL-3+, pu |
| vim-common | 2:9.1.1230-2 | vim | Apache, Apache or Expat, Artistic-1, BSD-2-clause, BSD-3-clause, Compaq, EDL-1, Expat, Expat or GPL-2, Expat or Vim, GPL |
| vim-tiny | 2:9.1.1230-2 | vim | Apache, Apache or Expat, Artistic-1, BSD-2-clause, BSD-3-clause, Compaq, EDL-1, Expat, Expat or GPL-2, Expat or Vim, GPL |
| whiptail | 0.52.25-1 | newt | GPL-2+, LGPL-2 |
| x11-common | 1:7.7+24+deb13u1 | xorg | siehe /usr/share/doc/x11-common/copyright |
| x11-xkb-utils | 7.7+9 | x11-xkb-utils | siehe /usr/share/doc/x11-xkb-utils/copyright |
| xauth | 1:1.1.2-1.1 | xauth | siehe /usr/share/doc/xauth/copyright |
| xbitmaps | 1.1.1-2.2 | xbitmaps | siehe /usr/share/doc/xbitmaps/copyright |
| xdg-dbus-proxy | 0.1.6-1+deb13u3 | xdg-dbus-proxy | LGPL-2+, LGPL-2.1+ |
| xfonts-encodings | 1:1.0.4-2.2 | xfonts-encodings | siehe /usr/share/doc/xfonts-encodings/copyright |
| xfonts-utils | 1:7.7+7 | xfonts-utils | siehe /usr/share/doc/xfonts-utils/copyright |
| xfsprogs | 6.13.0-2+deb13u1 | xfsprogs | GPL-2, GPL-3+ with autoconf exception, LGPL-2.1 |
| xinit | 1.4.2-1 | xinit | siehe /usr/share/doc/xinit/copyright |
| xkb-data | 2.42-1 | xkeyboard-config | siehe /usr/share/doc/xkb-data/copyright |
| xml-core | 0.19 | xml-core | GPL-2+ |
| xserver-common | 2:21.1.16-1.3+deb13u4 | xorg-server | siehe /usr/share/doc/xserver-common/copyright |
| xserver-xorg-core | 2:21.1.16-1.3+deb13u4 | xorg-server | siehe /usr/share/doc/xserver-xorg-core/copyright |
| xserver-xorg-input-libinput | 1.5.0-1 | xserver-xorg-input-libinput | MIT, xorg |
| xserver-xorg-legacy | 2:21.1.16-1.3+deb13u4 | xorg-server | siehe /usr/share/doc/xserver-xorg-legacy/copyright |
| xserver-xorg-video-fbdev | 1:0.5.0-2 | xserver-xorg-video-fbdev | siehe /usr/share/doc/xserver-xorg-video-fbdev/copyright |
| xserver-xorg-video-vesa | 1:2.6.0-2 | xserver-xorg-video-vesa | X11 |
| xsltproc | 1.1.35-1.2+deb13u3 | libxslt | siehe /usr/share/doc/xsltproc/copyright |
| xterm | 398-1 | xterm | siehe /usr/share/doc/xterm/copyright |
| xz-utils | 5.8.1-1+deb13u2 | xz-utils | 0BSD, Different licenses apply to different files in this package. Here, FSFUL, FSFULLR, GPL-2+, GPL-3.0-or-later-WITH-A |
| yudit-common | 3.1.0-1 | yudit | CC-BY-SA-3.0, GPL-2+ |
| zfsutils-linux | 2.3.9-0+deb13u1 | zfs-linux | Apache-2.0, BSD-2-clause, BSD-3-clause, CDDL-1.0, Expat, Expat~Unicode, GPL-2+, GPL-2+ with autoconf exception, PERMISSI |
| zlib1g | 1:1.3.dfsg+really1.3.1-1+b1 | zlib | Zlib |
