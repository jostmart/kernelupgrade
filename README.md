Kernelupgrade
=========

Don't everyone want the latest kernel?

http://elrepo.org/tiki/kernel-ml

# Edit /boot/grub2/grub.cfg if problems
# Run grub2-mkconfig -o /boot/grub2/grub.cfg
# reboot
# package-cleanup --oldkernels --count=1
# rpm -q kernel kernel-ml


License
-------

BSD

Author Information
------------------

Jostein Martinsen
