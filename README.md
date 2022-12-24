# My NixOS Config

Currently experimenting with using NixOS as a daily driver. To setup a new
machine, make sure that the machine that you want to configure has a
configuration file in `./machines`. Then you can symlink the config that
you want to `./machine-specific.nix` in `/etc/nixos` like follows:

```bash
ln -s ./machines/<config name>.nix ./machine-specific.nix
```
