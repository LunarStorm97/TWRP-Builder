## Automated TWRP compilation based on Github Action

## Parameter Description

| Name                 | Description                                       | Example                                                                  |
| -------------------- | ------------------------------------------------- | ------------------------------------------------------------------------ |
| `MANIFEST_URL`       | Source address                                    | https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git |
| `MANIFEST_BRANCH`    | Source branch                                     | twrp-12.1                                                                |
| `DEVICE_TREE_URL`    | Device address                                    | https://github.com/TeamWin/android_device_asus_I003D                     |
| `DEVICE_TREE_BRANCH` | Device branch                                     | android-12.1                                                             |
| `DEVICE_PATH`        | Device location                                   | device/asus/I003D                                                        |
| `DEVICE_NAME`        | Model name                                        | I003D                                                                    |
| `MAKEFILE_NAME`      | Makefile name                                     | twrp_I003D                                                               |
| `BUILD_TARGET`       | Build Target Partition (boot/recovery/vendorboot) | recovery                                                                 |

---

## How to use

```
For example, your username is: JohnSmith
```

#### 1. If you want to commit code, click 'Fork' in the upper right corner of this repository

![image](https://user-images.githubusercontent.com/37921907/177914706-c92476c5-7e14-4fb3-be94-0c8a11dae874.png)

#### 2. If you just want to use it simply, click 'Use this template' in the upper right corner of this repository

![image](https://github.com/azwhikaru/Action-TWRP-Builder/assets/37921907/fae6ce3c-bd4c-4bbe-8050-5dd29dff2522)

#### 3. After waiting for the automatic redirection, you will see your own username

![image](https://user-images.githubusercontent.com/37921907/177915106-5bde6fc9-303c-479e-b290-22b48efd1e4e.png)

#### 4. Change the [username and email](https://github.com/CaptainThrowback/Action-Recovery-Builder/blob/main/.github/workflows/Recovery%20Build.yml#L100-L101) in the workflow to reflect your Github credentials (optional)

## Building the Recovery

#### 5. Click 'Actions-Recovery Build'

![image](https://user-images.githubusercontent.com/37921907/177915304-8731ed80-1d49-48c9-9848-70d0ac8f2720.png)

#### 6. Click 'Run workflow' and fill in according to the above 'parameter description'

![image](https://user-images.githubusercontent.com/37921907/177915346-71c29149-78fb-4a00-996f-5d84ffc9eb8c.png)

#### 7. After filling in, click 'Run workflow' to start running

---

## Compilation results

Can be downloaded at [Release](../../releases)

---
