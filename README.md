# Shared modules for Flatpak

This repository contains some useful modules for Flatpak manifests which are not
present in the official [shared modules](https://github.com/flathub/shared-modules)
repository.

You can use them the same way you would use modules from the official repo.

First you'll need to add this repository as a submodule to your repository.

```sh
git submodule add https://github.com/dusansimic/flatpak-shared-submodules dusans-shared-modules
```

Then modules from this repository could be specified by adding a path to the to the manifest file.

```yaml
modules:
  - dusans-shared-modules/ImageMagick/ImageMagick.yaml
```
