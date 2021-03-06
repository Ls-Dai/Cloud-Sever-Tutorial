# 云服务器使用规则

这里介绍云服务器使用的相关规则和管理流程。如果需要具体了解云服务器的使用说明和技巧，请看[云服务器使用说明](Tutorial.md)。
## 基本信息

基本信息包括：
1. Outlook邮箱账户和密码
2. 用这个邮箱申请开通的云服务器账号和密码

具体信息见操作文档，请勿外传。<br>
云服务器网站为：[AI智算云](https://ai.blsc.cn/)。

## 使用流程
1. **确保您的程序已经在*A534*机器上运行正常，并且已经利用pip或者conda生成环境配置文件。** 等待在云服务器上使用。
2. 在操作文档中填写下列信息：
> 姓名，开始时间，预计结束时间，简要的任务说明

| 姓名 | ip地址（外网ip） | 开始时间| 预计结束时间 | 简要的任务说明 | 实际结束时间 | 是否已删除主机 |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| abc | 192.168.0.0 | 10/01 9:00AM | 10/01 9:00PM | 联邦学习代码 | --- | --- |
<br>

3. 通过ip名找到上一次工作的机器，开机，进行运算（或者按需创建新机器）
4. 结束运算，关机，在操作文档中填写下列信息:
> 实际结束时间

|    姓名    | ip地址（外网ip） | 开始时间| 预计结束时间 | 简要的任务说明 | 实际结束时间 | 是否已删除主机 |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| abc | 192.168.0.0 | 10/01 9:00AM  | 10/01 9:00PM | 联邦学习代码 | 10/01 8:00PM | --- |
5. 如果此次使用之后，删除主机，在操作文档中填写下列信息:
> 是否已删除主机

|    姓名    | ip地址（外网ip） | 开始时间| 预计结束时间 | 简要的任务说明 | 实际结束时间 | 是否已删除主机 |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| abc | 192.168.0.0 | 10/01 9:00AM  | 10/01 9:00PM | 联邦学习代码 | 10/01 8:00PM |  |

大多数情况下，不用删除主机，此处不写。<br>
如果碰上需要删除的情况，需要在这个地方写上*是*

|    姓名    | ip地址（外网ip） | 开始时间| 预计结束时间 | 简要的任务说明 | 实际结束时间 | 是否已删除主机 |
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| abc | 192.168.0.0 | 10/01 9:00AM  | 10/01 9:00PM | 联邦学习代码 | 10/01 8:00PM | 是 |

6. 当日安排值班的人于晚上登录账户，按照**预计结束时间**检查各台机器。*关机*在**预计结束时间**之后仍然运行的机器。

<br>
<br>
<br>

***

正文部分结束，如果需要具体了解云服务器的使用说明和技巧，请移步至[云服务器使用说明](Tutorial.md)。
