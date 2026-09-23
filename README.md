# Hyprtalia

[![bluebuild build badge](https://github.com/cvsickle/hyprtalia/actions/workflows/build.yml/badge.svg)](https://github.com/cvsickle/hyprtalia/actions/workflows/build.yml) &nbsp; [![Dependabot Updates](https://github.com/cvsickle/hyprtalia/actions/workflows/dependabot/dependabot-updates/badge.svg)](https://github.com/cvsickle/hyprtalia/actions/workflows/dependabot/dependabot-updates) &nbsp; [![renovate](https://github.com/cvsickle/hyprtalia/actions/workflows/renovate.yml/badge.svg)](https://github.com/cvsickle/hyprtalia/actions/workflows/renovate.yml) &nbsp; [![Repo sync (GitHub -> Codeberg)](https://github.com/cvsickle/hyprtalia/actions/workflows/sync_codeberg.yaml/badge.svg)](https://github.com/cvsickle/hyprtalia/actions/workflows/sync_codeberg.yaml)

---

This repository is a custom [bootc](https://github.com/bootc-dev/bootc) image built on [Universal Blue](https://github.com/ublue-os/main).

It was created using the [BlueBuild Workshop](https://workshop.blue-build.org/).

## Changes made

### Desktop

- [Hyprland](https://github.com/hyprwm/hyprland)
- [Noctalia](https://github.com/noctalia-dev/noctalia)
- [Quickshell](https://git.outfoxxed.me/quickshell/quickshell)

### System tools

- [Kitty Terminal](https://github.com/kovidgoyal/kitty)
- [Dolphin File Manager](https://github.com/kde/dolphin)
- [Tailscale](https://tailscale.com/)
- Everything needed for [LazyVim](https://github.com/lazyvim/lazyvim)
  - [Neovim](https://github.com/neovim/neovim)
  - [LazyGit](https://github.com/jesseduffield/lazygit)
  - Nerd Fonts from [ryanoasis/nerd-fonts](https://github.com/ryanoasis/nerd-fonts)
  - Etc.
- [starship](https://github.com/starship/starship)
- [btop](https://github.com/aristocratos/btop)
- [Helium Browser](https://github.com/imputnet/helium)
- Swapped `tuned-ppd` for `power-profiles-daemon` for optimization on Framework 13 Pro. See the [Phoronix writeup](https://www.phoronix.com/review/fedora-pantherlake-thermald-tuned).
- Docker CLI
- Podman Compose
- VS Code
- file-roller
- gwenview
- mpv
- okular

### Brew

- [Bold Brew](https://github.com/Valkyrie00/bold-brew)
- [Dev Container CLI](https://github.com/devcontainers/cli)
- [LazyDocker](https://github.com/jesseduffield/lazydocker)

### Flatpak

- [Dev Toolbox](https://flathub.org/en/apps/me.iepure.devtoolbox)
- [Easy Effects](https://flathub.org/en/apps/com.github.wwmm.easyeffects)
- [Flatseal](https://flathub.org/en/apps/com.github.tchx84.Flatseal)
- [Gear Lever](https://flathub.org/en/apps/it.mijorus.gearlever)
- [LocalSend](https://flathub.org/en/apps/org.localsend.localsend_app)
- [Podman Desktop](https://flathub.org/en/apps/io.podman_desktop.PodmanDesktop)
- [qView](https://flathub.org/en/apps/com.interversehq.qView)
- [SiriKali](https://flathub.org/en/apps/io.github.mhogomchungu.sirikali)
- [Web Apps](https://flathub.org/en/apps/net.codelogistics.webapps)

## Installation

TODO

## Verification

These images are signed with [Sigstore](https://www.sigstore.dev/)'s [cosign](https://github.com/sigstore/cosign). You can verify the signature by downloading the `cosign.pub` file from this repo and running the following command:

```bash
cosign verify --key cosign.pub ghcr.io/cvsickle/hyprtalia
```

## Repository Mirrors

TODO

## Other custom OS images

- [Bazzite DX](https://github.com/cvsickle/bazzite-dx)
- [Bluefin DX](https://github.com/cvsickle/bluefin-dx)
- [Zirconium](https://github.com/cvsickle/zirconium)
