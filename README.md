netbsd-userspace-src
====================

This repository contains a collection of NetBSD userspace sources
that are useful for for use in conjunction with rump kernels.
This usefulness falls under two general categories:

* NetBSD libraries that allow off-the-shelf applications to run on top of
  rump kernels without requiring an underlying OS (e.g. libc, libm,
  libutil, libipsec)
* NetBSD utilities that are used to configure a rump kernel or otherwise
  useful (e.g. ifconfig, newfs, ping, sysctl, ktrace)
