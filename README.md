# OSB-ABI-Support
# **项目名称**

二进制abi接口分析

# **项目描述**

为OBS构建系统实现ABI接口分析功能，自动识别软件包的依赖包abi接口是否变动自动加入reason列表中，便于更精确的进行自动化批量构建

# **所属赛道:**

2023全国大学生操作系统比赛的“OS功能设计”赛道

# **参赛要求**


# **项目导师**


# **难度**

中等


# 特征

* 需要了解包管理工作机制
* 熟悉perl python c/c++ 等语言
* 需要了解OBS整体架构
* 需要了解

# 参考文档

 [openbuildservice-help](https://openbuildservice.org/help/manuals/obs-user-guide/)

 [open-build-service](https://github.com/openSUSE/open-build-service)

 **深入理解计算机系统**

# License

GPL-3.0


# 预期目标

**注意：下面的三个步骤是必要内容，选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标。**

第一题： 完成ABI接口分析

* 软件包构建完成记录二进制的ABI接口信息
* 软件包重复rebuild提取二进制ABI接口信息与数据库中的信息对比
* ABI变更触发依赖树中的包进行rebuild
  第二题：完成OBS构建系统的ABI分析支持

* 为OBS调度器添加根据ABI接口变化自动确认是否rebuild功能

