## TWRP Builder

This repository provides a GitHub Actions workflow to automatically build a custom TWRP recovery image. By using this workflow, you can generate a recovery image without the need to set up a local build environment.

### Description

The TWRP Builder workflow allows you to build a custom TWRP recovery image for a specific device. This process automates the downloading of necessary device trees and manifests, setting up the build environment, and generating the recovery image.

### Requirements

Before running the workflow, make sure to configure the following parameters:

| PARAMETER            | DEFAULT VALUE                                                        |
| -------------------- | -------------------------------------------------------------------- |
| `MANIFEST_URL`       | https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp |
| `MANIFEST_BRANCH`    | twrp-12.1                                                            |
| `DEVICE_TREE_URL`    | https://github.com/TeamWin/android_device_samsung_a23xq              |
| `DEVICE_TREE_BRANCH` | android-12.1                                                         |
| `DEVICE_PATH`        | device/samsung/a23xq                                                 |
| `DEVICE_CODENAME`    | a23xq                                                                |
| `MAKEFILE_NAME`      | twrp_a23xq                                                           |
| `PARTITION_TARGET`   | recovery                                                             |

### Usage

1. Fork this repository
2. Navigate to the Actions tab in your forked repository
3. Select the `TWRP Builder` workflow and click on `Run workflow`
4. Provide the necessary values for each parameter based on your device
5. Click on `Run workflow` to start the build process

### Credits

This workflow is based on the work of several contributors and open-source projects.
