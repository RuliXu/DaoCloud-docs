# 创建边缘节点组

在边缘计算场景中，边缘节点通常分布在不同的地理区域，这些区域中的节点计算资源、网络结构和硬件平台存在诸多差异。
根据边缘节点的地理分布特点，可以把同一区域的边缘节点分为一组，将边缘节点以节点组的形式组织起来，同一节点同时只能属于一个节点组。

将边缘应用部署到节点组，提升跨地域应用部署的运维效率。

下文说明创建边缘节点组的步骤。

1. 进入边缘单元详情页，选择左侧菜单`边缘资源` -> `边缘节点组`。

2. 点击节点组列表右上角`创建边缘节点组`按钮。

    ![创建边缘节点组](../../images/create-group-01.png)

3. 填写相关参数。

    - 节点组名称：小写字母、数字、中划线(-)、点(.)的组合，且不能有连续符号；以字母或数字为开头、结尾。
    - 描述：节点组描述信息。
    - 节点选择方式：边缘节点组中的节点可以指定多个节点或通过标签选择器匹配，两种方式可以同时使用并生效。

    ![创建边缘节点组](../../images/create-group-02.png)

4. 点击`确定`按钮，即创建边缘节点组成功，返回到边缘节点组列表。

下一步：[管理边缘节点组](manage-group.md)