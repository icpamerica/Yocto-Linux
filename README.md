# Yocto-Linux
Linux OS images built with Yocto Project

File list:
core-image-minimal-intel-corei7-64.hddimg
        This is the disk image of the Yocto Linux distro:
        - Yocto poky version 2.5.1
        - Linux kernel: 4.14.68
        - Intel PREEMPT-RT
        - Machine type: x86_64 (see conf/local.conf)
        - Machine name: intel-corei7-64 (see meta-intel)
        The image was tested on a 64-bit computer with Intel core i5

vmlinux
        This is the Linux kernel version 4.9.90:
        - Configure with Xenomai-3 (cobalt)
        The kernel has not been tested.  Please feel free to feedback with any suggestion or question.
