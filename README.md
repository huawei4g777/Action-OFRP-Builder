# Build Recovery using Github Actions

- Support OrangeFox Only

---

## Thanks to
- All contributors

---

## Release Notes
```
= 2023/04/20
- The first available version is submitted.
```

-----

## Parameter Description

| Name | Description | Example |
| ------------ | -------------------- | ------------ |
| `SYNC_URL` | Script specified by OrangeFox | https://gitlab.com/OrangeFox/sync.git |
| `MANIFEST_BRANCH` | Source branch | 12.1                                                         |
| `DEVICE_TREE_URL` | Device address | https://github.com/huawei4g777/android_device_samsung_kyleprods |
| `DEVICE_TREE_BRANCH` | Device branch | fox_12.1 |
| `DEVICE_PATH` | Device location | device/samsung/kyleprods |
| `COMMON_TREE_URL` | Common tree address |  |
| `COMMON_PATH` | Common tree location |  |
| `DEVICE_NAME` | Model name | kyleprods |
| `MAKEFILE_NAME` | Makefile name | ofrp[your device name] |
| `BUILD_TARGET` | Build Target Partition (boot/recovery/vendorboot) | recovery |

-----

## Compilation results
Can be downloaded at [Release](../../releases)

File not being uploaded to Release? Please check the step 'Check the output directory before uploading' and check the file name
