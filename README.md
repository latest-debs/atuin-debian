# atuin for Debian

[atuin](https://github.com/atuinsh/atuin) — Magical shell history — packaged for
Debian as part of [latest-debs](https://github.com/latest-debs).

## Install

Via the latest-debs apt repository:

```sh
sudo extrepo enable latest-debs
sudo apt update
sudo apt install atuin
```

Or download a `.deb` from the [Releases](https://github.com/latest-debs/atuin-debian/releases) page:

```sh
sudo dpkg -i atuin_*.deb
```

## Supported distributions & architectures

- Debian Bookworm (12), Trixie (13), Forky (14/testing), Sid (unstable)
- amd64, arm64

## Building

Run the [Build atuin for Debian](../../actions) workflow on GitHub with the
desired upstream version. Packaging is driven by
[debian-multiarch-builder](https://github.com/ranjithrajv/debian-multiarch-builder).

## Disclaimer

Unofficial packaging only. For issues with atuin itself, see
[atuinsh/atuin](https://github.com/atuinsh/atuin).
