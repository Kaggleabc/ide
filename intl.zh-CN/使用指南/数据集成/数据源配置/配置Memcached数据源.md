# 配置Memcached数据源 {#concept_ijs_vq1_p2b .concept}

Memcache（原名OCS）数据源提供了其它数据源将数据写入Memcache的能力，目前只能通过脚本模式配置同步任务。

## 操作步骤 {#section_jy4_q4v_42b .section}

1.  以项目管理员身份进入[DataWorks管理控制台](https://workbench.data.aliyun.com/console)，单击对应项目操作栏中的**进入数据集成**。
2.  单击**数据源** \> **新增数据源**，弹出支持的数据源。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16205/15469259117544_zh-CN.png)

3.  在新建数据源弹出框中，选择数据源类型为**Memcached**。
4.  配置Memcached数据源的各个信息项。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/16205/15469259117545_zh-CN.png)

    |配置|说明|
    |:-|:-|
    |**数据源名称**|数据源名称必须以字母、数字、下划线组合，且不能以数字和下划线开头。|
    |**数据源描述**|对数据源进行简单描述，不得超过80个字符。|
    |**数据源类型**|当前选择的数据源类型Memcache。|
    |**Proxy Host**|相应的Memcache Proxy。|
    |**Port**|相应的Memcache端口，默认为11211。|
    |**用户名/密码**|对应的用户名和密码。|

5.  单击**测试连通性**。
6.  测试连通性通过后，单击**确定**。

    提供测试连通性能力，可以判断输入的各项信息是否正确 。


## 后续步骤 {#section_dqv_5d1_p2b .section}

现在，您已经学习了如何配置Memcache数据源，您可以继续学习下一个教程。在该教程中您将学习如何通过配置Memcache Writer插件。详情请参见[配置Memcache（OCS） Writer](intl.zh-CN/使用指南/数据集成/作业配置/配置Writer插件/配置Memcache（OCS） Writer.md#)。

