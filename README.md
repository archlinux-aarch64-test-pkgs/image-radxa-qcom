# Arch Linux images for Radxa Qualcomm devices

This repository publishes Arch Linux test images for Radxa Qualcomm devices built with the `arch-ports-radxa-qcom-kde` preset from [`arch-image-builder`](https://github.com/archlinux-aarch64-test-pkgs/arch-image-builder).

The images are built manually through GitHub Actions and published as GitHub Release assets. Each release includes:

- A compressed `.7z` image.
- A `.pkglist.txt` file listing every installed package and version in the image.
- Release notes with package additions, removals, and version changes compared with the previous non-draft release when a previous package list is available.

## Notes

- This image is not officially supported by Radxa.
- This image is not suitable for production environments.
- Packages in this image come from Arch Linux Ports, not Arch Linux ARM.
