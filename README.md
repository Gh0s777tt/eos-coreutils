# eos-coreutils

**E-OS fork of [`redox-os/coreutils`](https://gitlab.redox-os.org/redox-os/coreutils).** Part of the [**E-OS**](https://github.com/Gh0s777tt/E-OS) ecosystem — a hardened, Crimson-branded downstream of [Redox OS](https://www.redox-os.org).

This repository is Redox **coreutils** (`ls`, `cp`, `cat`, …).

## E-OS changes vs upstream

_None yet_ — pinned to a clean upstream commit. E-OS branding and config for this component are applied via **recipe patches in the [main repo](https://github.com/Gh0s777tt/E-OS)**, not fork commits.

## How it's pinned

The E-OS build pins this fork in [`recipes/core/coreutils/recipe.toml`](https://github.com/Gh0s777tt/E-OS/blob/main/recipes/core/coreutils/recipe.toml):

- branch **`master`** · rev **`575a46d3b624`**
- up to date with upstream

## Build standalone

This fork is normally built by the E-OS cookbook (`make CI=1 …` in the [main repo](https://github.com/Gh0s777tt/E-OS)). To build it on its own you need the Redox toolchain; see the main repo's [build guide](https://github.com/Gh0s777tt/E-OS/blob/main/docs/building.md).

## Hosting

**GitLab (source of truth):** https://gitlab.com/e-os/eos-coreutils  
**GitHub (read-only mirror):** https://github.com/Gh0s777tt/eos-coreutils

## License

MIT (inherited from upstream Redox). The E-OS project as a whole is AGPL-3.0; see the [main repo](https://github.com/Gh0s777tt/E-OS/blob/main/LICENSE).

---
[E-OS main repo](https://github.com/Gh0s777tt/E-OS) · [Docs](https://github.com/Gh0s777tt/E-OS/tree/main/docs) · [Upstream](https://gitlab.redox-os.org/redox-os/coreutils)
