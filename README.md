_DEPRECATED: use src-netbsd.  This repository is scheduled for removal in 6/2015_

netbsd-userspace-src
====================

_Most likely you will not use the contents of this repository directly,_
_but rather as a submodule for something interacting with rump kernels._

This repository contains a collection of NetBSD userspace sources
that are useful for for use in conjunction with rump kernels.
This usefulness falls under two general categories:

* NetBSD libraries that allow off-the-shelf applications to run on top of
  rump kernels without requiring an underlying OS (e.g. libc, libm,
  libutil, libipsec)
* NetBSD utilities that are used to configure a rump kernel or otherwise
  useful (e.g. ifconfig, newfs, ping, sysctl, ktrace)
