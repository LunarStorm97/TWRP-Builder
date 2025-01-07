## TWRP Builder

This repository provides a GitHub Actions workflow to automatically build a custom TWRP recovery image for Android devices. By using this workflow, you can generate a recovery image for your specific device without the need to set up a local build environment.

### Description

The TWRP Builder workflow allows you to build a custom TWRP recovery image for a specific Android device. This process automates the downloading of necessary device trees and manifests, setting up the build environment, and generating the recovery image.

### Requirements

Before running the workflow, make sure to configure the following parameters:

| PARAMETERS           | DESCRIPTION           | DEFAULT VALUE                                                          |
| -------------------- | --------------------- | ---------------------------------------------------------------------- |
| `MANIFEST_URL`       | Source adress         | `https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp` |
| `MANIFEST_BRANCH`    | Source branch         | `twrp-12.1`                                                            |
| `DEVICE_TREE_URL`    | Device address        | `https://github.com/TeamWin/android_device_samsung_a23xq`              |
| `DEVICE_TREE_BRANCH` | Device branch         | `android-12.1`                                                         |
| `DEVICE_PATH`        | Device location       | `device/samsung/a23xq`                                                 |
| `DEVICE_TARGET`      | Device codename       | `a23xq`                                                                |
| `MAKEFILE_NAME`      | Makefile name         | `twrp_a23xq`                                                           |
| `PARTITION_TARGET`   | Partition target      | `recovery`                                                             |

### Usage

1. Fork this repository to your GitHub account.
2. Navigate to the Actions tab in your forked repository.
3. Select the TWRP Builder workflow and click on Run workflow.
4. Provide the necessary values for each parameter based on your device.
5. Click on Run workflow to start the build process.

### Credits

This workflow is based on the work of several contributors and open-source projects.
