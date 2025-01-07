# Automated TWRP Compilation Using GitHub Actions

## Parameter Description

| Name                 | Description            | Example                                                                  |
| -------------------- | ---------------------- | ------------------------------------------------------------------------ |
| `MANIFEST_URL`       | Source address         | https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git |
| `MANIFEST_BRANCH`    | Source branch          | twrp-12.1                                                                |
| `DEVICE_TREE_URL`    | Device address         | https://github.com/TeamWin/android_device_samsung_a23xq                  |
| `DEVICE_TREE_BRANCH` | Device branch          | android-12.1                                                             |
| `DEVICE_PATH`        | Device location        | device/samsung/a23xq                                                     |
| `DEVICE_TARGET`        | Model name             | a23xq                                                                    |
| `MAKEFILE_NAME`      | Makefile name          | twrp_a23xq                                                               |
| `PARTITION_TARGET`       | Partition Target | recovery                                                                 |

---

## How to Use

1. **If you want to commit code**, click **'Fork'** in the upper-right corner of this repository:

   ![Fork Example](https://user-images.githubusercontent.com/37921907/177914706-c92476c5-7e14-4fb3-be94-0c8a11dae874.png)

2. **If you just want to use it**, click **'Use this template'** in the upper-right corner of this repository:

   ![Use Template Example](https://github.com/azwhikaru/Action-TWRP-Builder/assets/37921907/fae6ce3c-bd4c-4bbe-8050-5dd29dff2522)

3. After redirection, you will see your own username:

   ![Username Example](https://user-images.githubusercontent.com/37921907/177915106-5bde6fc9-303c-479e-b290-22b48efd1e4e.png)

4. Change the [username and email](https://github.com/CaptainThrowback/Action-Recovery-Builder/blob/main/.github/workflows/Recovery%20Build.yml#L100-L101) in the workflow to reflect your GitHub credentials (optional).

---

## Building the Recovery

5. Click **'Recovery Build'**:

   ![Actions Example](https://user-images.githubusercontent.com/37921907/177915304-8731ed80-1d49-48c9-9848-70d0ac8f2720.png)

6. Click **'Run workflow'** and fill in the required parameters as described in the **Parameter Description** table above:

   ![Run Workflow Example](https://user-images.githubusercontent.com/37921907/177915346-71c29149-78fb-4a00-996f-5d84ffc9eb8c.png)

7. After filling in the parameters, click **'Run workflow'** to start the process.

---

## Compilation Results

The compiled recovery can be downloaded from the [Release](../../releases) section.
