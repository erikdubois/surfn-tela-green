# CLAUDE.md — surfn-tela-green

## Project overview

Standalone repo for the **Surfn-Tela-Green** folder-icon theme, a colour variant of the base
`erikdubois/surfn` icon set. Folder (places) icons sourced from `vinceliuice/Tela-icon-theme`.

## Current state

Ships one theme: `usr/share/icons/Surfn-Tela-Green/` — **places only**. Packaged as `surfn-tela-green-icons-git`
(recipe in `~/KIRO-PKG-BUILD-ICONS/surfn-tela-green/`), `depends=('surfn-icons-git')`.

## Patterns & decisions

- Folders only; everything else inherits Surfn. Size-first layout (`<size>/places`) with
  @2x/@3x dir symlinks. `icon-theme.cache` gitignored. Bash scripts follow the Kiro template.
