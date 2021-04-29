# NPLN-Protocols
This repo contains protobuf files for Nintendo's [NPLN services](https://github.com/kinnay/NintendoClients/wiki/NPLN-Servers).

The IPS patches disable SSL certificate verification in Monster Hunter Rise.

| Ver. | IPS Patch |
| --- | --- |
| Demo `v0` | `D95BAAADDE3908EF79B5DC2353D3680E24D4A692` |
| Demo `v2` | `2D10BE721F63E81366779B6BFE544A03DB9F443B` |
| Full game `v0` | `5CAC0323CCBC04BFA6A8E26F2BA349854C027812` |
| Full game `v2` | `6CDEC176EA1D12C5C4F85BF17213377C22D1EEEF` |
| Full game `v4` | `2EEFBDB9786E1652308BF32B298727F77FBCFC77` |

`generate_patch.py` generates an IPS patch automatically, given the filename of the main NSO.
