# linux-5.3.1-config
a kernel configuration for linux 5.x includes wireless support
change the name of the configuration file  to .config
move it into the folder that contains the kernel source code
re-compile the kernel with "make all ; make install_modules"
execute the following commands "mv arch/x86/boot/bzImage /boot/EFI/"
"mv System.map /boot/"
install your bootloader
