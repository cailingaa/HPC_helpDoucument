分区管理
======================
&emsp;

+ **此处的分区为一个相对广义的概念。正常情况下，分区是指 Slurm 集群的实际可用的计算节点合集，此处将含义扩大，包括节点外接的存储。**

## 新增分区 ##
* 点击【**<font color=blue>计费</font>**】菜单，再次点击[**<font color=blue>分区管理</font>**]，进入'分区管理'列表页面，点击<**<font color=blue>新增</font>**>按钮，填入分区信息，点击<**<font color=blue>保存</font>**>，可成功添加分区。


![新增分区](../_static/img/charging/partition/addPartition.png)


+ **注意事项：** 
    + *新增分区时，注意分区名称需与 slurm 平台中的分区名称一致。*
    + *计费方式：独占、共享；当为“独占”时，需要设置分区可用节点数。*
    + *分区类型：CPU、GPU、存储；当选择 GPU 时，需要设置分区可用 GPU 卡数。*
    + *特别注意：<font color=red>分区名必须是小写。</font>*

&emsp;

----------------------------------------------------------------------------------------------------------------------------------
## 查看分区详情 ##

* 点击【**<font color=blue>计费</font>**】菜单，再次点击[**<font color=blue>分区管理</font>**]，进入'分区管理'列表页面，点击需要查看的分区管理项中的[**<font color=blue>操作</font>**]列的<**<font color=blue>查看</font>**>按钮，可成功查看分区项详情信息。

![查看分区详情](../_static/img/charging/partition/partitionDetail.png)


&emsp;

----------------------------------------------------------------------------------------------------------------------------------

## 编辑分区 ##

* 点击【**<font color=blue>计费</font>**】菜单，再次点击[**<font color=blue>分区管理</font>**]，进入'分区管理'列表页面，点击需要编辑的分区管理项中的[**<font color=blue>操作</font>**]列的<**<font color=blue>编辑</font>**>按钮，填入新的分区信息，点击<**<font color=blue>修改</font>**>，可成功编辑计费模板。


![编辑分区](../_static/img/charging/partition/editPartition.png)


&emsp;

----------------------------------------------------------------------------------------------------------------------------------

## 删除分区管理 ##

* 点击【**<font color=blue>计费</font>**】菜单，再次点击[**<font color=blue>分区管理</font>**]，进入'分区管理'列表页面，点击需要删除的分区管理项中的[**<font color=blue>操作</font>**]列的<**<font color=blue>删除</font>**>按钮进行删除操作；也可以勾选需要删除的分区管理项，再点击<**<font color=blue>删除</font>**>按钮，进行批量删除的操作。


![删除分区](../_static/img/charging/partition/deletePartition.png)


&emsp;