oneSIS files. based on oneSIS 2.0.2
-----------------------------------

**init**
   oneSIS /init file from the glibc busybox which has logic added for multi-cluster module loading, root on lustre booting, rsync boot etc.

**distro-patches**
   custom distro-patches for the various OS images
  
**sysimage_files**
   /etc/sysimage.conf files for various compute node, oss or mds servers, and management server OS images

**x86_64-glibc-rjh.tar.gz**
   busybox initramfs tarball. includes mount.lustre, dev/infiniband/ etc.
   just add kernel modules and go.
