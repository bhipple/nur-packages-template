# Talon Beta Nix User Package

This NixPkgs User Repository contains an expression for building the beta
version of `talonvoice`. This requires a subscription on Patreon:

https://www.patreon.com/lunixbochs

For details on setting up the Nixpkgs User Repository, see

https://github.com/nix-community/NUR/blob/master/README.md

## beta-src.nix

The encrypted `./beta-src.nix` file is generated by running `talon-src <url>`,
where URL is provided on the beta slack channel.

After computing the release information, this script will install talon.

## Systemd Unit

This provides a basic `systemd --user` service file for running `talon` with
reduced privileges.

## Contributions

Pull requests improving the nix expressions are welcome!