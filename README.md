# 威胁猎人手册

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OTRF/ThreatHunter-Playbook/master)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Twitter](https://img.shields.io/twitter/follow/HunterPlaybook.svg?style=social&label=Follow)](https://twitter.com/HunterPlaybook)
[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

<img src="docs/images/logo/logo.png" width=200>

威胁猎人手册是一个基于社区的开源项目，旨在通过利用不同操作系统的安全事件日志，分享威胁狩猎的概念，帮助发展狩猎活动的技术和假说。该项目不仅提供有关威胁检测的信息，而且还提供了做数据分析时非常重要的步骤，如数据文档、数据建模，甚至包括数据质量评估。

此外，在这个项目中共享的分析方法，以类SQL语句的格式呈现了主机和网络级别特定的攻击链，以便您可以使用自己喜欢的工具或查询格式来应用它们的检测逻辑。本报告提供的检测方法也遵循[MITRE ATT&CK](https://attack.mitre.org/wiki/Main_Page)的结构，对战术组中的后渗透攻击行为进行了分类。

最后，该项目以[交互式笔记本](https://github.com/hunters-forge/notebooks-forge#what-is-a-notebook)的形式记录检测策略，以提供一种简单而灵活的方式来可视化预期输出，并能够通过[BinderHub](https://mybinder.readthedocs.io/en/latest/index.html)的云计算环境对预记录的[安全数据集](https://github.com/Moofeng/Security-Datasets)进行分析。

# 目标

* 促进威胁狩猎相关技术和假说的发展
* 帮助威胁猎人理解后渗透攻击中观察到的行为模式
* 通过提供更多围绕可疑事件的上下文数据，减少误报的数量
* 通过免费的云计算环境分享实时的分析验证案例
* 在全球范围内共享并传递威胁狩猎的概念和流程
* 将预记录的数据集匹配到相应的攻击技术
* 通过开源项目促进信息安全的学习

# 交互式笔记本

我把整个项目转换成了一本书，方便大家阅读并复现文档内的各个步骤

* https://threathunterplaybook.com/

# 作者

Roberto Rodriguez [@Cyb3rWard0g](https://twitter.com/Cyb3rWard0g)

# 译者
* 慕长风 [@Moofeng](https://twitter.com/M0ofeng)

# 官方提交者

* Jose Luis Rodriguez [@Cyb3rPandaH](https://twitter.com/Cyb3rPandaH) 加入了他在数据科学方面的专业知识

# 贡献

希望能看到其他威胁猎人用一些很棒的想法来检测攻击者的行为模式并提交pr，你贡献的案例越多，手册对社区的帮助也会更大
* 请按照TEMPLATE格式提交pr
* 强烈建议在提交pr(文章，白皮书，狩猎笔记等)前测试你的攻击链或提供参考资料
  * 狩猎笔记是非常有用的，可以帮助解释为什么你要分析特定的事件
* 请随意提交pr，以提高威胁狩猎技术，分享即是关怀

# To-Do

* [ ] OSX & Linux Playbooks
* [ ] Cloud AWS Playbooks
* [ ] Update Binder Libraries (Testing)
