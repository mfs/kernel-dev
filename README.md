## kernel-dev

Scripts related to kernel development. Not much here at the moment except for a
couple of thin wrapper scripts inspired by a [blog post][1] by Stefan Hajnoczi.

### build\_initramfs

Thin wrapper around gen\_init\_cpio. There is an example file list in
initramfs/filelist that builds a simple busybox based initramfs.

### boot\_kernel

Execute from the root of a Linux git repo to boot the kernel in the current
terminal. Useful for quickly testing a newly built kernel.

[1]: http://blog.vmsplice.net/2011/02/near-instant-kernel-development-cycle.html
