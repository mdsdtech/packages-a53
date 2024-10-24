# ImmortalWrt A53 Packages

This repository contains packages for the A53 target in the ImmortalWrt firmware. These packages are available for download from the ImmortalWrt snapshots repository.

## Overview

The A53 target in ImmortalWrt provides a variety of packages tailored for devices utilizing A53 chipsets. The snapshots include both core packages and additional software that enhances the functionality and performance of your device.

## Getting Started

To use these packages, follow these steps:

A. Option 1:
1. **Download Packages**: Navigate to the desired directory and download the required package files.

2. **Install Packages**: Use the ImmortalWrt package management system to install the downloaded packages. Typically, this can be done using `opkg`, the package manager for ImmortalWrt. For example:
   ```sh
   opkg install /path/to/package.ipk
   ```

3. **Configuration**: After installation, configure the packages as needed. Configuration files and instructions are typically provided with each package.

B. Option 2:
1. Remove the line immortalwrt_core "src/gz immortalwrt_core https://downloads.immortalwrt.org/snapshots/targets/mediatek/filogic/packages" in repositories.conf.
2 Replace the immortalwrt_core line with
```
src/gz immortalwrt_core https://raw.githubusercontent.com/mdsdtech/packages-a53/main/6.6.56
```
3. Save than run the update packages.

## Contributing

If you would like to contribute to the repository or have suggestions for new packages, please follow these guidelines:

1. **Fork the Repository**: Create a fork of this repository to make changes.

2. **Make Changes**: Add or modify packages in your fork.

3. **Submit a Pull Request**: Once your changes are complete, submit a pull request for review.

## Support

For support and issues related to ImmortalWrt or Mediatek Filogic packages, please refer to the [ImmortalWrt community forums](https://forum.immortalwrt.org/) or the [ImmortalWrt documentation](https://immortalwrt.org/docs/).

## License

The packages in this repository are licensed under the [GPLv2 License](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html). Please refer to the individual package licenses for specific terms.

---

Feel free to customize this README file based on additional details or specific requirements related to your repository.
