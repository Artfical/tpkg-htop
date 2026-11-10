# htop

htop 3.5.3: an interactive process viewer

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install htop
```

| | |
|---|---|
| Version | 3.5.3 |
| Licence | GPL-2.0+ |
| Upstream | https://htop.dev |
| Needs | [`terminfo`](https://github.com/Artfical/tpkg-terminfo) |
| Needs tOS build | 616 or newer |
| Size | 320222 bytes (717463 unpacked) |
| SHA-256 of the `.tpkg` | `8bae20279f57c85e35c929e157d121826bd5b75ce8a074ee5bf10226a3ebb5eb` |

## Commands it adds

| Command | Runs |
|---|---|
| `htop` | `bin/htop` |

## Download

The package file (`htop-3.5.3.tpkg`) and the sources it was built from are the assets of the
[v3.5.3 release](https://github.com/Artfical/tpkg-htop/releases/tag/v3.5.3).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `htop-3.5.3.tar.xz`
- `ncurses-6.5.tar.gz`

Check a download: `sha256sum htop-3.5.3.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-2.0+. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
