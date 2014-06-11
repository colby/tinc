# Tinc VPN
Configurations for a Tinc VPN setup. This is a working rough draft.

## Dependencies
### Debian
```bash
$ sudo apt-get install tinc
```

### OSX
```bash
$ brew install tinc lzo tuntap
```
Follow the directions of the `brew` caveats for each formula.
You may need to reboot your mac for the tap/tun devices to show up.

## Installation
Move the contents of this repo to the tinc directory on your system.
Edit as needed.

```bash
$ sudo cp /home
```

## Issues
Don't forget to allow `655/tcp` through the firewall.
