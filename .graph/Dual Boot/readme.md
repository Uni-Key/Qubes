- https://www.qubes-os.org/faq/#:~:text=Can%20I%20install%20Qubes%20OS,risks%20with%20such%20a%20setup.
- https://github.com/Qubes-Community/Contents/blob/master/docs/configuration/multiboot.md
  - https://forum.qubes-os.org/t/qubes-other-linux-dual-boot/21271

# Guide:
## Multibooting Qubes - Community Guides
- https://forum.qubes-os.org/t/multibooting-qubes/18988

>Qubes by default does not include other systems in the generated grub menu, because handling of other systems has been disabled. This means that you will have to manually add grub entries for any other OS.
>
>The general approach is:
>
>- Enable legacy boot mode
>- Ensure current OS boots in legacy mode
>- Install Qubes
>- Manually add boot stanzas to /etc/grub.d/40_custom
>- Update grub
