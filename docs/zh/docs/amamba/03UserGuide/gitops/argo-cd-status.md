# Argo CD 应用状态说明

本页面介绍了 Argo CD 应用的健康状态、同步状态说明。

**健康状态**

| 健康状态 | 描述                                                         |
| -------- | ------------------------------------------------------------ |
| 健康     | 资源健康                                                     |
| 已降级   | 资源已经被降级                                               |
| 进行中   | 资源还不健康，但仍在进行中，可能很快就会健康                 |
| 暂停     | 资源被暂停并等待一些外部事件恢复（例如暂停的 CronJob 或暂停的部署） |
| 未知     | 无法判断当前健康状态                                         |
| 丢失     | 资源已缺失                                                   |
|          |                                                              |

**同步状态**

| 同步状态 | 描述                                     |
| -------- | ---------------------------------------- |
| 已同步   | 集群中部署的资源与仓库中期望的状态一致   |
| 未同步   | 集群中部署的资源与仓库中期望的状态不一致 |
| 未知     | 无法判断当前同步状态                     |