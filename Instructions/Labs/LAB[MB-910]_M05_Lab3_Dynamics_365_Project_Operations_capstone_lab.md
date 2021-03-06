---
lab:
    title: '实验室 5.3： Dynamics 365 项目操作巅峰课程实验室'
    module: '模块 5： 学习 Dynamics 365 Project Operations 的基础知识'
---

模块 5：学习 Dynamics 365 Project Operations 的基础知识
========================

## 实践实验室 5.3 - Dynamics 365 项目操作巅峰课程实验室

## 实验室场景

ABC 公司专注于安全设备的制造、销售、安装和维修。该公司的产品包括室内和室外安全摄像头、湿度和火灾传感器、监视服务等。 

ABC 公司使用 Dynamics 365 应用程序跨组织的各个领域（从销售到服务）与所有客户互动。 

**销售和营销**

ABC 公司直接通过针对性的营销活动对住宅客户展开营销。基于客户所在城市和其他因素将客户设置为目标。营销材料通过电子邮件发送，并基于客户与电子邮件的互动相应地进行引导。 

虽然一些小型产品是通过零售商销售的，但大多数产品通过内部销售人员直接销售给消费者。

从内部看，他们侧重于两个关键领域： 

- **住宅客户：** 住宅客户通常需要单独的部件或希望购买整个家庭解决方案。此类销售周期通常较短，且来自于社交媒体、网站、推荐者或意向客户的直接联系人。由于住宅客户通常较关注特定产品或较小的安装，因此其销售周期通常持续几天或几周。 

- **企业客户：** 企业销售人员侧重于需要较专业化的定制业务解决方案的客户。企业销售人员通常覆盖多个地点，具有关联的通信，通常需要使用多种资源才能完成项目。此类销售周期通常较长且具有更多的灵活部分。 

ABC 公司的销售人员需要具有必要的工具、资源和指导（无论他们在对客户进行推销时侧重于什么方面），这一点非常重要。 

**系统安装：**

已购买的安全设备的安装过程因购买设备的客户的类型而异。 

- **住宅客户：** 由于住宅安装所需时间通常不超过一天，因此由内部员工完成。完成销售后，系统会创建工作订单、确定一名合格的技师并安排安装。 

- **企业客户：** 企业部署可能需要几个月，并需要一名项目经理监督日常操作。这包括创建项目计划、定义项目团队和计划资源。 

**服务和支持：**

系统安装后，ABC 公司提供售后支持。如果客户有问题，可以联系客户支持。代理将尝试与客户远程协作，解决问题。如果问题无法通过远程方式解决，支持代理会将问题上报给工作订单，一名合格的现场技师会对此工作订单进行安排并予以处理。 
## 目标

ABC 公司的企业销售人员侧重于安全需求要求较专业化的定制业务解决方案的客户。因此，企业销售人员通常覆盖多个地点，具有关联的通信，通常需要使用多种资源才能完成项目。ABC 公司的企业销售周期可能长达数月并且需要执行多个灵活的部分。 

向企业客户销售系统后，实施项目可能需要数月。每个项目被分配给一位项目经理，该项目经理需要监督项目规划和日常操作。这包括创建项目计划、定义项目团队和计划资源。 

作为企业销售人员，你负责向客户销售高端定制安全解决方案。你最近接到了来自一家名为 Consolidated Sample 的公司的电话。他们希望获得可覆盖其所有地点的完全集成的安全解决方案。你将 Consolidated Sample 的销售机会输入系统，在项目销售周期中推进并创建相应的项目。 

完成实验室时，你便已经完成以下内容：

- 管理与项目机会相关的日常活动。 

- 添加、创建和定义项目报价。 

- 生成项目合同。 

- 创建项目并定义项目团队。 

## 实验室设置

  - **预计用时**： 45 分钟

## 说明

## 练习 1：创建项目报价和项目预估

项目机会用于捕获潜在项目的大致详细信息。随着越来越多的项目详细信息出现，你可以创建项目报价。项目报价通常包括关于不同角色、日程表和定价的详细信息。项目报价会提供给客户。通过项目报价，你可以开始创建与要销售的项目相关的项目计划。这会在销售项目后节省时间，因为与项目相关的许多详细信息已被获取。

在此练习中，你将创建项目并定义与项目报价相关的详细信息。 

### 任务 1：创建项目报价。  

1. 在“项目机会”打开的情况下，选择 **“报价”** 选项卡。 

2. 在“报价”子网格中，选择 **“新建报价”** 按钮。

3. 新报价记录打开后，将报价上的 **“产品价目表”** 字段设置为 **“美国计费费率”**。 

4. 选择 **“报价单明细”** 选项卡。

5. 选择并打开 **“系统实现”** 订单项。 

6. 在 **“项目”** 字段中，选择 **“新建项目”**。 

7. 在 **“快速创建项目”** 屏幕中，完成项目，如下所示：

	- **名称：** 完成全局实现 - 你的姓名首字母

	- **项目经理：** 选择你的用户记录

	- **日历模板：** 默认工作模板

	- **承包单位：** Fabrikam US

	- **预计开始日期：** 一周后

	- **预计人工成本：** $ 175,000

	- **预计费用成本：** $ 50,000

	- **预计总成本：** $ 225,000

8. 选择 **“保存并关闭”** 按钮。

9. 接下来，我们将定义是否可以对分配给项目的特定角色计费。选择 **“可计费角色”** 选项卡。

10. 选择并打开“机器人工程师”角色，将计费类型设置为 **“不可计费”**。

11. 在 **“命令栏”** 上，选择 **“保存并关闭”** 按钮。

12. 选择 **“报价单明细详细信息”** 选项卡。

13. 在子网格上，单击 **“新建报价单明细详细信息”** 按钮。

14. 完成 **“报价单明细详细信息”** 项，如下所示：

	- **描述：** 通信行运行 - 你的姓名首字母

	- **事务类型：** 时间

	- **角色：** 网络技术员

	- **类别：** 时间

	- **开始日期：** 一个月后

	- **结束日期：** 两个月后

	- **资源单位：** Fabrikam US

	- **单位：** 小时


15. 选择 **“保存并关闭”** 按钮，关闭行详细信息项。 

16. 在 **“命令栏”** 上，选择 **“保存并关闭”** 按钮。 


**备注：** 让“项目报价”保持打开状态，以便在下一个任务中使用它。 


### 任务 2：关闭“项目报价”并创建项目合同。

在此任务中，你将关闭已创建的项目报价并将其转换为项目合同。可以在执行项目时使用和利用项目合同。 


1. 在 **“完成全局安全实现 - 你的姓名首字母”** 项目报价记录打开的情况下，选择命令栏上的 **“中标关闭”** 按钮。 

2. 在 **“确定要关闭报价”** 屏幕上，选择 **“确定”**。

3. 关闭报价后，将显示新创建的 **“完成全局安全实现 - 你的姓名首字母”** 项目合同。 

 

**备注：** 让“项目合同”保持打开状态，以便在下一个任务中使用它。 

## 练习 2：管理项目

利用项目操作的项目销售功能的好处之一是可以在销售过程中创建项目。可以从不同的销售相关记录（例如项目报价和项目合同）访问创建的项目。 

在此练习中，你将管理一些与项目相关的最初任务，例如定义项目详细信息、定义项目团队和概述项目任务。 


### 任务 1：管理基本项目数据 

1. 在 **“完成全局安全实现 - 你的姓名首字母”** 项目合同打开的情况下，选择 **“相关”** 选项卡。 

2. 从显示的菜单中，选择 **“项目”**。

3. 打开 **“全局安全实现 - 你的姓名首字母”** 项目。 

4. 在 **“项目服务”** 业务流程流中，选择 **“新建”** 阶段，选择 **“下一阶段”** 按钮，进入 **“报价”** 阶段。 

5. 在 **“报价”** 阶段中，将 **“预计完成日期”** 字段设置为 **“六个月后”**。 

6. 选择 **“下一阶段”** 按钮，进入 **“计划”** 阶段。 

 
### 任务 2：创建项目团队。

每个项目都有一个团队，团队成员将帮助执行项目。在此任务中，我们将定义组成项目团队成员的资源。 

 
1. 在 **“完成全局安全实现 - 你的姓名首字母”** 项目记录打开的情况下，选择 **“团队”** 选项卡

2. 在 **“所有团队成员”** 子网格上，选择 **“+ 新建”** 按钮。

3. 配置团队成员记录，如下所示：

	- **职位名称：** 机器人工程师 - 你的姓名首字母

	- **可预定资源：** Allison Dickson

	- **角色：** 机器人工程师

4. 选择“保存并关闭”按钮旁的箭头。在出现的菜单中，选择 **“保存并关闭新项”。**

5. 配置下一个团队成员记录，如下所示：

	- **职位名称：** 软件工程师 - 你的姓名首字母

	- **可预定资源：** Bob Kozak

	- **角色：** 软件工程师

6. 选择“保存并关闭”按钮旁的箭头。在出现的菜单中，选择 **“保存并关闭新项”。**

7. 配置团队成员记录，如下所示：

	- **职位名称：** 网络技术员 - 你的姓名首字母

	- **可预定资源：** Dianna Woodward

	- **角色：** 网络技术员

8. 选择 **“保存并关闭”** 按钮。


### 任务 3：定义“项目计划”。

定义项目的另一个重要方面是定义项目任务和项目计划。在此任务中，我们将添加一些项目任务并将它们与不同角色关联。 


1. 在 **“完成全局安全实现 - 你的姓名首字母”** 项目打开的情况下，选择 **“计划”** 选项卡。 

2. 在“计划”子网格中的工具栏上，选择 **“+ 添加”** 按钮。 

3. 在出现的行中，将 **“名称”** 字段设置为 **“系统开发”**。

4. 在“计划”子网格中的工具栏上，再次选择 **“+ 添加”** 按钮，添加另一个项。 

5. 按如下方式配置项：

	- **名称：** 创建系统布局

	- **工作量：** 25

6. 在“计划”子网格中的工具栏上，再次选择 **“+ 添加”** 按钮，添加另一个任务。 

7. 按如下方式配置项：

	- **名称：** 设计摄像头

	- **前置任务：** 创建系统布局

	- **工作量：** 50

8. 在“计划”子网格中的工具栏上，再次选择 **“+ 添加”** 按钮，添加最后一个任务。 

9. 按如下方式配置项：

	- **名称：** 验证和审批设计

	- **前置任务：** 设计摄像头

	- 工作量：8 

 
**备注：** 继续停留在“计划”选项卡上，因为我们将在下一个任务中进行一些额外的修改。 


### 任务 4：将资源与项目关联。

在定义项目计划的过程中，可以指定将用于满足人员配置要求的资源类型。可以是有真实姓名的资源，也可以是泛型资源（以后将使用有姓名的资源进行替代）。在此任务中，你将为你创建的项目任务定义有姓名的资源和泛型资源。 

1. 如有必要，打开 **“完成全局安全实现 - 你的姓名首字母”** 项目，选择 **“计划”** 选项卡。 

2. 找到之前添加的 **“创建系统布局”** 任务，选择 **“资源”** 字段。 

3. 从显示的菜单中，选择 **“创建”**。 

4. 配置项目团队成员，如下所示

	- **职位名称：** 泛型机器人工程师 - 你的姓名首字母

	- **可预定资源：** 泛型资源

	- **角色：** 机器人工程师

5. 选择 **“保存并关闭”** 按钮。 

6. 验证 **“泛型机器人工程师 - 你的姓名首字母”** 资源是否已添加到“资源”字段。 

7. 找到 **“设计摄像头”** 任务并选择 **“资源”** 字段。 

8. 从显示的菜单中，选择 **“创建”**。 

9. 配置项目团队成员，如下所示：

	- **职位名称：** 泛型机器人工程师 - 你的姓名首字母

	- **可预定资源：** 泛型资源

	- **角色：** 机器人工程师

10. 选择 **“保存并关闭”** 按钮。 

11. 找到 **“验证并审批设计”** 任务，选择 **“资源”** 字段。 

12. 从显示的菜单中，选择 **“Allison Dickson”**。 


恭喜！你已在 Dynamics 365 项目操作中成功销售并创建项目。在这里，项目经理可管理项目的不同方面，例如计划资源、监视项目计划并管理时间和费用。 

 

 
