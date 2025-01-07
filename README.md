## TWRP Builder

This repository provides a GitHub Actions workflow to automatically build a custom TWRP recovery image for Android devices. By using this workflow, you can generate a recovery image for your specific device without the need to set up a local build environment.

### Description

The `TWRP Builder` workflow allows you to build a custom TWRP recovery image for a specific Android device. This process automates the downloading of necessary device trees and manifests, setting up the build environment, and generating the recovery image.

### Requirements

Before running the workflow, make sure to configure the following parameters:

- **MANIFEST_URL**: The URL of the AOSP or TWRP manifest.
- **MANIFEST_BRANCH**: The branch of the manifest you want to use.
- **DEVICE_TREE_URL**: The URL of the device tree for your specific model.
- **DEVICE_TREE_BRANCH**: The branch of the device tree.
- **DEVICE_PATH**: The path within the device tree where your device configuration is located.
- **DEVICE_TARGET**: The codename of your device.
- **MAKEFILE_NAME**: The build configuration file name for your device.
- **PARTITION_TARGET**: The partition you want to build (e.g., `recovery`).

### Usage

1. **Fork the Repository**: Fork this repository to your GitHub account.
2. **Access GitHub Actions**: Navigate to the "Actions" tab in your forked repository.
3. **Run the Workflow**: Select the `TWRP Builder` workflow and click on "Run workflow".
4. **Configure Parameters**: Provide the necessary values for each parameter based on your device and needs.
5. **Start the Build**: Click on "Run workflow" to start the build process.

The workflow will download the required device trees and manifests, set up the build environment, and generate the TWRP recovery image for your device.

### Notes

- This workflow is designed to build TWRP recovery images.
- Make sure the device trees and manifests are compatible with the Android version you wish to use.
- The build may take several minutes to complete, depending on the load of GitHub Actions servers.

### Credits

This workflow is based on the work of several contributors and open-source projects. We appreciate all contributors for their efforts and dedication.
