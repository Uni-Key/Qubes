# FAD
- https://www.qubes-os.org/faq/#can-i-install-qubes-os-together-with-other-operating-system-dual-bootmulti-boot

# Guide:
## Multibooting Qubes - Community Guides
https://forum.qubes-os.org/t/multibooting-qubes/18988
  - old: https://github.com/Qubes-Community/Contents/blob/master/docs/configuration/multiboot.md

>Qubes by default does not include other systems in the generated grub menu, because handling of other systems has been disabled. This means that you will have to manually add grub entries for any other OS.
>
>The general approach is:
>
>- Enable legacy boot mode
>- Ensure current OS boots in legacy mode
>- Install Qubes
>- Manually add boot stanzas to /etc/grub.d/40_custom
>- Update grub


## Blog:
https://micahflee.com/2014/04/dual-booting-qubes-and-ubuntu-with-encrypted-disks/
