# heic-to-jpg-dolphin-service
Context menu to convert HEIC images to JPG for KDE Dolphin file manager 

KDE Store Page: https://store.kde.org/p/2299018

## Installation

1. Ensure that libheif is installed and makes the `heif-convert` command available and visible to your system path or `/home/linuxbrew/.linuxbrew/bin`. You will likely also want to ensure it has HEVC support, which is needed to convert images created with HEVC with devices like iPhones.

    - Bazzite and other Fedora Universal Blue variants, or other immutable Linux: Use Homebrew to install: `brew install libheif`
    - Fedora: Install `libheif-tools` and `libheif-openworld`
    - Arch: Install `libheif`
    - Ubuntu: Looks kind of complicated, it might be `libheif1`, I don't know.

1. Configure Dolphin > Context Menu > Download New Services
1. Search for this service "Convert HEIC to JPG" and install it.

## Usage

Select one or more HEIC image files, right click and choose "Convert HEIC to JPG." A new JPG file will be created accordingly, e.g. IMG_0000.heic will generate IMG_0000.jpg

Please note that if the output file name already exists, the file will be overwritten.

The original HEIC file will be retained.

## Support

Please feel free to open an issue or a PR to get help or improve this repository! My hope is for this image conversion tool to work out of the box with minimal effort to users.
