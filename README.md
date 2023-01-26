# Grubvox Themes (for Home Assistant)

Inspired by the popular [gruvbox](https://github.com/morhetz/gruvbox) editor themes.

### Screenshots

|**Light**|**Dark**|
|--|--|
|![Development – Home Assistant](https://user-images.githubusercontent.com/1088717/214848951-eed17568-bd33-426b-ba67-94510d35f5f5.png)|![Development – Home Assistant](https://user-images.githubusercontent.com/1088717/214849106-421f96c0-c13c-4990-bb2b-d43d90faee8f.png)
|![Settings – Home Assistant](https://user-images.githubusercontent.com/1088717/214849293-c59228d7-9491-40ac-a456-208a87c5f41a.png)|![Settings – Home Assistant](https://user-images.githubusercontent.com/1088717/214849330-3ed28b3c-2609-4d08-8741-345974e725b1.png)

## Installation

Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

### Manual (pending HACS)

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
