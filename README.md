# 薯算签名资料更新

当前资料包版本：`2026.10.4.1`；最低助手版本：`0.3.0`。资料对应 Steam PC Brotato **1.1.15.4**，包括64角色、66条参考路线、257条武器等级记录（78个注册武器系列）、247件道具、17个武器类型羁绊、46项属性与机制主题，以及全部24个原生属性资源。

来源目录共552条记录：保留原有534个 Wiki 页面，另有1条官方版本信息、17条补充参考，其中10条可自动核对，7条用于人工参考。每条记录保留作者、版本、阅读范围、修订或固定源码提交、采集时间及适用限制。记录数不是独立来源数；打包日期不代表重新提取游戏或重新阅读全部网页。社区策略与助手情景推导不是原生评分、胜率或最优保证。

`stable/index.json` 是RSA-PSS/SHA-256签名目录；`stable/<SHA256>.spudpack` 是不可变签名资料包。发布者公钥SPKI SHA-256：`7f9e67a1ee2ee9f6191a0b14ebea7ddd3e1b997cf08afba2bd7780e31686dd1c`。用户通过已验证的助手更新功能读取资料，暂存包在下次启动时重新校验并启用，可回退。旧版资料包继续保留；清单按助手版本与实际消费者合同分别提供兼容包。

资料更新不会执行网页代码、自动改变推荐规则或扩大游戏版本支持。新游戏版本、未知模组或新机制需要相应程序与连接组件验证。来源检查失败、离线或清单过期时保留已经验证的本地资料，不冒充数据已更新。

Brotato及游戏内容权利属于Blobfish及相应权利人。版本参考：[Steam官方公告](https://steamcommunity.com/app/1942280/announcements/)和[Steam游戏页面](https://store.steampowered.com/app/1942280/Brotato/)。本目录不包含游戏资源、原生源码、程序、存档、运行日志或发布者私钥。

Wiki资料归属[Brotato Wiki及其贡献者](https://brotato.wiki.spellsandguns.com/Characters)，页面Copyright Policy链接[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)。签名资料保留各页面标题、固定修订及采集摘要；对Wiki内容的整理、中文改写和策略提示保留作者归属及相同方式共享要求。

角色路线参考作者ArosRising：[Wiki固定修订8521](https://brotato.wiki.spellsandguns.com/index.php?oldid=8521&title=ArosRising%27s_Character_Guide)、[原始公开文档](https://docs.google.com/document/d/1EfW2UVO55TejfiSRUObuuZ5FmA2lmgD2lQrJBnQW6hY/edit)及作者计算工具属于同一来源链。补充参考还包括[Mojimoon的固定版本冷却研究](https://github.com/mojimoon/brotato/blob/0e9f72e7cc8bac406929ef63e0e94ca58d2778f0/docs/Brotato-weapon-cooldown-en.md)、[SchniePlayer的固定版本计算器源码](https://github.com/SchniePlayer/Brotato-Calculator/tree/373a47e55ff303213c38600053c68cf3fc4cc70b)、作者攻略及可复现实测。各条采纳限制在包内来源记录中明确，平衡模组修改值和被原生机制反证的陈述不用于冒充原版规则。

第三方原作和游戏内容继续适用各自权利，不因资料包签名获得新的许可。
