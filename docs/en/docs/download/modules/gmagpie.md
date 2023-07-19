# Operations Management

This page allows you to download the offline installation packages for different versions of the Operations Management module.

## Download

| Version                                              | Architecture | File Size | Installation Package                                                                                          | Checksum File                                                                                                | Last Updated |
| ---------------------------------------------------- | ------------ | --------- | ------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | ------------ |
| [v0.3.0](../../gmagpie/intro/release-notes.md)       | AMD64        | 56.90MB   | [:arrow_down: gmagpie_v0.3.0_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/gmagpie_v0.3.0_amd64.tar)         | [:arrow_down: gmagpie_v0.3.0_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/gmagpie_v0.3.0_amd64_checksum.sha512sum)           | 2023-06-28   |
| [v0.2.2](../../ghippo/user-guide/report-billing/index.md) | AMD64        | 37.1MB    | [:arrow_down: gmagpie_v0.2.2_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/gmagpie_v0.2.2_amd64.tar)           | [:arrow_down: gmagpie_v0.2.2_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/gmagpie_v0.2.2_amd64_checksum.sha512sum)          | 2023-5-30    |

## Verification

Navigate to the directory where the offline installation package and checksum file are downloaded, and run the following command to verify the integrity:

```sh
echo "$(cat gmagpie_v0.2.2_amd64_checksum.sha512sum)" | sha512sum -c
```

If the verification is successful, the result will be similar to:

```none
gmagpie_v0.2.2_amd64.tar: ok
```

## Installation

Refer to the [Global Management](../../ghippo/install/offline-install.md) installation process for installation instructions.

If this is your first-time installation, please apply for a free trial: [Free Community License](../../dce/license0.md) or contact us for authorization at info@daocloud.io or call 400 002 6898.
For any license-related issues, please contact the DaoCloud delivery team.