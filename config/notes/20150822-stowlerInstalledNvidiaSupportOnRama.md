# stdout from rama nvidia install

_...for future troubleshooting..._

```bash
[03:40:38]-[stowler-local]-at-[rama]-in-[~]
$ sudo apt-get install nvidia-common nvidia-settings nvidia-current-updates
Reading package lists... Done
Building dependency tree
Reading state information... Done
The following extra packages will be installed:
  dkms lib32gcc1 libc6-i386 libcuda1-304-updates libvdpau1 nvidia-304-updates
  nvidia-opencl-icd-304-updates screen-resolution-extra
Suggested packages:
  nvidia-vdpau-driver vdpau-driver
The following NEW packages will be installed:
  dkms lib32gcc1 libc6-i386 libcuda1-304-updates libvdpau1 nvidia-304-updates
  nvidia-common nvidia-current-updates nvidia-opencl-icd-304-updates
  nvidia-settings screen-resolution-extra
0 upgraded, 11 newly installed, 0 to remove and 0 not upgraded.
Need to get 50.9 MB of archives.
After this operation, 223 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://us.archive.ubuntu.com/ubuntu/ trusty/main libvdpau1 amd64 0.7-1 [30.3 kB]
Get:2 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main dkms all 2.2.0.3-1.1ubuntu5.14.04.1 [64.6 kB]
Get:3 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main libc6-i386 amd64 2.19-0ubuntu6.6 [2,206 kB]
Get:4 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/restricted libcuda1-304-updates amd64 304.125-0ubuntu0.0.2 [6,418 kB]
Get:5 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/main lib32gcc1 amd64 1:4.9.1-0ubuntu1 [47.6 kB]
Get:6 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/restricted nvidia-304-updates amd64 304.125-0ubuntu0.0.2 [35.5 MB]
Get:7 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/universe nvidia-common amd64 1:0.2.91.11 [1,298 B]
Get:8 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/restricted nvidia-current-updates amd64 304.125-0ubuntu0.0.2 [4,420 B]
Get:9 http://us.archive.ubuntu.com/ubuntu/ trusty-updates/restricted nvidia-opencl-icd-304-updates amd64 304.125-0ubuntu0.0.2 [5,807 kB]
Get:10 http://us.archive.ubuntu.com/ubuntu/ trusty/main screen-resolution-extra all 0.17.1 [11.4 kB]
Get:11 http://us.archive.ubuntu.com/ubuntu/ trusty/main nvidia-settings amd64 331.20-0ubuntu8 [774 kB]
Fetched 50.9 MB in 27s (1,865 kB/s)
Selecting previously unselected package libvdpau1:amd64.
(Reading database ... 212431 files and directories currently installed.)
Preparing to unpack .../libvdpau1_0.7-1_amd64.deb ...
Unpacking libvdpau1:amd64 (0.7-1) ...
Selecting previously unselected package dkms.
Preparing to unpack .../dkms_2.2.0.3-1.1ubuntu5.14.04.1_all.deb ...
Unpacking dkms (2.2.0.3-1.1ubuntu5.14.04.1) ...
Selecting previously unselected package libc6-i386.
Preparing to unpack .../libc6-i386_2.19-0ubuntu6.6_amd64.deb ...
Unpacking libc6-i386 (2.19-0ubuntu6.6) ...
Selecting previously unselected package libcuda1-304-updates.
Preparing to unpack .../libcuda1-304-updates_304.125-0ubuntu0.0.2_amd64.deb ...
Unpacking libcuda1-304-updates (304.125-0ubuntu0.0.2) ...
Selecting previously unselected package lib32gcc1.
Preparing to unpack .../lib32gcc1_1%3a4.9.1-0ubuntu1_amd64.deb ...
Unpacking lib32gcc1 (1:4.9.1-0ubuntu1) ...
Selecting previously unselected package nvidia-304-updates.
Preparing to unpack .../nvidia-304-updates_304.125-0ubuntu0.0.2_amd64.deb ...
Unpacking nvidia-304-updates (304.125-0ubuntu0.0.2) ...
Selecting previously unselected package nvidia-common.
Preparing to unpack .../nvidia-common_1%3a0.2.91.11_amd64.deb ...
Unpacking nvidia-common (1:0.2.91.11) ...
Selecting previously unselected package nvidia-current-updates.
Preparing to unpack .../nvidia-current-updates_304.125-0ubuntu0.0.2_amd64.deb ...
Unpacking nvidia-current-updates (304.125-0ubuntu0.0.2) ...
Selecting previously unselected package nvidia-opencl-icd-304-updates.
Preparing to unpack .../nvidia-opencl-icd-304-updates_304.125-0ubuntu0.0.2_amd64.deb ...
Unpacking nvidia-opencl-icd-304-updates (304.125-0ubuntu0.0.2) ...
Selecting previously unselected package screen-resolution-extra.
Preparing to unpack .../screen-resolution-extra_0.17.1_all.deb ...
Unpacking screen-resolution-extra (0.17.1) ...
Selecting previously unselected package nvidia-settings.
Preparing to unpack .../nvidia-settings_331.20-0ubuntu8_amd64.deb ...
Unpacking nvidia-settings (331.20-0ubuntu8) ...
Processing triggers for man-db (2.6.7.1-1ubuntu1) ...
Processing triggers for gnome-menus (3.10.1-0ubuntu2) ...
Processing triggers for desktop-file-utils (0.22-1ubuntu1) ...
Processing triggers for mime-support (3.54ubuntu1.1) ...
Setting up libvdpau1:amd64 (0.7-1) ...
Setting up dkms (2.2.0.3-1.1ubuntu5.14.04.1) ...
Setting up libc6-i386 (2.19-0ubuntu6.6) ...
Setting up libcuda1-304-updates (304.125-0ubuntu0.0.2) ...
Setting up lib32gcc1 (1:4.9.1-0ubuntu1) ...
Setting up nvidia-304-updates (304.125-0ubuntu0.0.2) ...
update-alternatives: using /usr/lib/nvidia-304-updates/ld.so.conf to provide /etc/ld.so.conf.d/x86_64-linux-gnu_GL.conf (x86_64-linux-gnu_gl_conf) in auto mode
update-alternatives: using /usr/lib/nvidia-304-updates/alt_ld.so.conf to provide /etc/ld.so.conf.d/i386-linux-gnu_GL.conf (i386-linux-gnu_gl_conf) in auto mode
update-alternatives: using /usr/share/nvidia-304-updates/glamor.conf to provide /usr/share/X11/xorg.conf.d/glamoregl.conf (glamor_conf) in auto mode
update-initramfs: deferring update (trigger activated)
INFO:Enable nvidia-304-updates
DEBUG:Parsing /usr/share/ubuntu-drivers-common/quirks/lenovo_thinkpad
DEBUG:Parsing /usr/share/ubuntu-drivers-common/quirks/put_your_quirks_here
DEBUG:Parsing /usr/share/ubuntu-drivers-common/quirks/dell_latitude
Loading new nvidia-304-updates-304.125 DKMS files...
First Installation: checking all kernels...
Building only for 3.19.0-26-generic
Building for architecture x86_64
Building initial module for 3.19.0-26-generic
Done.

nvidia_304_updates:
Running module version sanity check.
 - Original module
   - No original module exists within this kernel
 - Installation
   - Installing to /lib/modules/3.19.0-26-generic/updates/dkms/

depmod........

DKMS: install completed.
Setting up nvidia-common (1:0.2.91.11) ...
Setting up nvidia-current-updates (304.125-0ubuntu0.0.2) ...
Setting up nvidia-opencl-icd-304-updates (304.125-0ubuntu0.0.2) ...
Setting up screen-resolution-extra (0.17.1) ...
Setting up nvidia-settings (331.20-0ubuntu8) ...
Processing triggers for libc-bin (2.19-0ubuntu6.6) ...
Processing triggers for initramfs-tools (0.103ubuntu4.2) ...
update-initramfs: Generating /boot/initrd.img-3.19.0-26-generic

[03:43:16]-[stowler-local]-at-[rama]-in-[~]
$ uname -a
Linux rama 3.19.0-26-generic #28~14.04.1-Ubuntu SMP Wed Aug 12 14:09:17 UTC 2015 x86_64 x86_64 x86_64 GNU/Linux

[03:44:44]-[stowler-local]-at-[rama]-in-[~]
$ sudo shutdown -r now
```
