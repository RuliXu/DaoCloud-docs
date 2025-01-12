# MySQL

本页可下载 MySQL 各版本的离线安装包。

[返回下载首页](../../index.md){ .md-button }

## 下载

| 版本                                                         | 架构 | 文件大小 | 安装包                                                                                                                             |  校验文件 | 更新日期       |
|------------------------------------------------------------| ----- |-------- |---------------------------------------------------------------------------------------------------------------------------------| ---------- |------------|
| [v0.11.1](../../../middleware/mysql/release-notes.md)         | AMD 64 | 296.23MB | [:arrow_down: mysql_0.11.1_amd64.tar](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mysql_0.11.1_amd64.tar) | [:arrow_down: mysql_0.11.1_amd64_checksum.sha512sum](https://qiniu-download-public.daocloud.io/DaoCloud_Enterprise/mysql_0.11.1_amd64_checksum.sha512sum) | 2023-10-10 |

## 校验

在下载离线安装包和校验文件的目录，执行以下命令校验完整性：

```sh
echo "$(cat mysql_0.11.1_amd64_checksum.sha512sum)" | sha512sum -c
```

校验成功后打印结果类似于：

```none
mysql_0.11.1_amd64.tar: OK
```

## 安装

如果是初次安装，请[申请免费体验](../../../dce/license0.md)或联系我们授权：电邮 info@daocloud.io 或致电 400 002 6898。
如果有任何许可密钥相关的问题，请联系 DaoCloud 交付团队。