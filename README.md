# heic-to-jpg-dolphin-service
Context menu to convert HEIC images to JPG for KDE Dolphin file manager 

KDE Store Page: [https://www.example.com](example.com)

## Installation

1. Ensure that libheif is installed and makes the `heif-convert` command available. You will likely also want to ensure it has HEVC support, which is needed to convert images created with HEVC with devices like iPhones.

    - Fedora: Install `libheif-tools` and `libheif-openworld`
    - Arch: Install `libheif`
    - Ubuntu: Looks kind of complicated, it might be `libheif1`, I don't know.

1. Configure Dolphin > Context Menu > Download New Services
1. Search for this service "Convert HEIC to JPG" and install it.

## Usage

Select one or more HEIC image files, right click and choose "Convert HEIC to JPG." A new JPG file will be created accordingly, e.g. IMG_0000.heic will generate IMG_0000.jpg

Please note that if the output file name already exists, the file will be overwritten.

The original HEIC file will be retained.