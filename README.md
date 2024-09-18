# ImmortalWrt Mediatek Filogic Packages

This repository contains packages for the Mediatek Filogic target in the ImmortalWrt firmware. These packages are available for download from the ImmortalWrt snapshots repository.

## Overview

The Mediatek Filogic target in ImmortalWrt provides a variety of packages tailored for devices utilizing Mediatek Filogic chipsets. The snapshots include both core packages and additional software that enhances the functionality and performance of your device.

## Directory Structure

The packages are organized into directories based on their categories. Here is an overview of the directory structure:

- `base`: Core packages required for the basic operation of ImmortalWrt on Mediatek Filogic devices.
- `luci`: Web interface packages for configuring and managing ImmortalWrt.
- `packages`: Additional software packages that can be installed to extend the capabilities of your device.
- `routing`: Routing-related packages that provide advanced networking features.
- `telephony`: Packages related to telephony and communication features.

## Getting Started

To use these packages, follow these steps:

1. **Download Packages**: Navigate to the desired directory (e.g., `base`, `luci`, etc.) and download the required package files.

2. **Install Packages**: Use the ImmortalWrt package management system to install the downloaded packages. Typically, this can be done using `opkg`, the package manager for ImmortalWrt. For example:
   ```sh
   opkg install /path/to/package.ipk
   ```

3. **Configuration**: After installation, configure the packages as needed. Configuration files and instructions are typically provided with each package.

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