# Grubvox Themes (for Home Assistant)

Inspired by the popular [gruvbox](https://github.com/morhetz/gruvbox) editor themes.

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### Manual

Clone this repository in your existing (or create it) `themes/` folder.

```bash
cd themes/
git clone https://github.com/kizza/lovelace-gruvbox.git
```

Or using submodules:

```bash
cd themes/
git submodule add https://github.com/kizza/lovelace-gruvbox.git
```
