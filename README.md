oneSIS files
------------

note that the files here are not a complete [oneSIS](http://onesis.org/) package,
they are the important differences between these production versions and original oneSIS.
they are based on oneSIS 2.0.2

**init**
   oneSIS /init file from the glibc busybox which has logic added for multi-cluster module loading, root on lustre booting, rsync boot etc.

**distro-patches**
   custom distro-patches for the various OS images
  
**sysimage_files**
   example /etc/sysimage.conf files for various OS images: read-only ~diskless root-on-lustre compute node, ramdisk oss or mds server, read-write stateful management server

**x86_64-glibc-rjh.tar.gz**
   busybox initramfs tarball. includes mount.lustre, dev/infiniband/ etc.
   just add kernel modules and go.
