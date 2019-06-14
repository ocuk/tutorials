### Ubuntu installation guide

Step 1. Windows preparation 

* save a backup copy 
* disable fast startup
* disable windows updates

```
run services.msc
```

Step 2. Create a bootable usb

Step 3. Change boot options

Step 4. Install ubuntu

Dont forget to change the boot options back or remove the flash drive before rebooting!

When expiriencing problems due to nvidia drivers: 
Disable graphics drivers by adding nomodeset to the kernel

* on the grub screen, press e, add 'nomodeset' at the end of linux line, or

* change the grub file at /etc/default/grub after the GRUB_CMDLINE_LINUX_DEFAULT

