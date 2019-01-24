[CHAT\_MSG\_ACHIEVEMENT](https://wow.gamepedia.com/CHAT_MSG_ACHIEVEMENT) → [成就](https://wow.gamepedia.com/Category:API_events/Achievements),[通讯](https://wow.gamepedia.com/Category:API_events/Communication),[公会](https://wow.gamepedia.com/Category:API_events/Guild) 当您附近的玩家完成一项成就时被触发。

[CHAT\_MSG\_ADDON](https://wow.gamepedia.com/CHAT_MSG_ADDON) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 客户端从[SendAddonMessage](https://wow.gamepedia.com/API_SendAddonMessage)收到消息时触发

[CHAT\_MSG\_AFK](https://wow.gamepedia.com/CHAT_MSG_AFK) →[通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当客户端收到AFK自动响应时触发

[CHAT\_MSG\_BG\_SYSTEM\_ALLIANCE](https://wow.gamepedia.com/CHAT_MSG_BG_SYSTEM_ALLIANCE) → [战场](https://wow.gamepedia.com/Category:API_events/Battleground),[通讯](https://wow.gamepedia.com/Category:API_events/Communication) 对于默认为蓝色的战场事件消息，因为它们与联盟行动有关，例如袭击墓地或占领点，或拿起旗帜。

[CHAT\_MSG\_BG\_SYSTEM\_HORDE](https://wow.gamepedia.com/CHAT_MSG_BG_SYSTEM_HORDE) → [战场](https://wow.gamepedia.com/Category:API_events/Battleground),[通讯](https://wow.gamepedia.com/Category:API_events/Communication) 它们是关于部落行动而被触发，因为战斗场事件消息默认为红色

[CHAT\_MSG\_BG\_SYSTEM\_NEUTRAL](https://wow.gamepedia.com/CHAT_MSG_BG_SYSTEM_NEUTRAL) → [战场](https://wow.gamepedia.com/Category:API_events/Battleground),[通讯](https://wow.gamepedia.com/Category:API_events/Communication)  对于默认情况下以派系中性色显示的战场事件消息被触发。

CHAT\_MSG\_BN\_INLINE\_TOAST\_ALERT → [战场](https://wow.gamepedia.com/Category:API_events/Battleground),[通讯](https://wow.gamepedia.com/Category:API_events/Communication)

CHAT\_MSG\_BN\_INLINE\_TOAST\_BROADCAST → [战场](https://wow.gamepedia.com/Category:API_events/Battleground),[通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_BN\_INLINE\_TOAST\_BROADCAST\_INFORM](https://wow.gamepedia.com/CHAT_MSG_BN_INLINE_TOAST_BROADCAST_INFORM) → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net),[通讯](https://wow.gamepedia.com/Category:API_events/Communication) 更改战网真实ID广播消息时或从[API BNSetCustomMessage](https://wow.gamepedia.com/API_BNSetCustomMessage)触发

[CHAT\_MSG\_BN\_INLINE\_TOAST\_CONVERSATION](https://wow.gamepedia.com/CHAT_MSG_BN_INLINE_TOAST_CONVERSATION) → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net),[通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_BN\_WHISPER](https://wow.gamepedia.com/CHAT_MSG_BN_WHISPER) → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net),[通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_BN\_WHISPER\_INFORM](https://wow.gamepedia.com/CHAT_MSG_BN_WHISPER_INFORM) → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net),[通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_BN\_WHISPER\_PLAYER\_OFFLINE](https://wow.gamepedia.com/CHAT_MSG_BN_WHISPER_PLAYER_OFFLINE) → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net),[通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_CHANNEL](https://wow.gamepedia.com/CHAT_MSG_CHANNEL) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 客户端收到频道消息时触发。

[CHAT\_MSG\_CHANNEL\_JOIN](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_JOIN) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当有人加入您所在的聊天频道时被触发

[CHAT\_MSG\_CHANNEL\_LEAVE](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_LEAVE) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当玩家离开您当前所在的频道时被触发。

[CHAT\_MSG\_CHANNEL\_LIST](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_LIST) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)  调用[ListChannels](https://wow.gamepedia.com/API_ListChannels)\(\)或[ListChannelByName](https://wow.gamepedia.com/API_ListChannelByName)\(\)时触发，并在聊天框中显示消息。

[CHAT\_MSG\_CHANNEL\_NOTICE](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_NOTICE) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当您进入或离开聊天频道（或最近节流频道）时被触发

[CHAT\_MSG\_CHANNEL\_NOTICE\_USER](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_NOTICE_USER) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)  当频道中的某些内容发生变化时启动，如启用审核，用户被踢，通知发生变化等等。GlobalStrings.lua中的CHAT \_ \* \_ NOTICE包含可用类型的完整列表。

[CHAT\_MSG\_COMBAT\_FACTION\_CHANGE](https://wow.gamepedia.com/CHAT_MSG_COMBAT_FACTION_CHANGE) → [战斗](https://wow.gamepedia.com/Category:API_events/Combat) 当玩家的阵营改变时触发。即：“你对木喉要塞的声望略有增加。” -- 新1.09

[CHAT\_MSG\_COMBAT\_HONOR\_GAIN](https://wow.gamepedia.com/CHAT_MSG_COMBAT_HONOR_GAIN) → [战斗](https://wow.gamepedia.com/Category:API_events/Combat),[荣誉](https://wow.gamepedia.com/Category:API_events/Honor)  当玩家获得任何荣誉时，任何事情都会被触发，从荣誉击杀到奖励荣誉。

[CHAT\_MSG\_COMBAT\_MISC\_INFO](https://wow.gamepedia.com/CHAT_MSG_COMBAT_MISC_INFO) → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)  当您的装备因死亡而导致耐久性损失时触发，并可能在其他情况下触发。（自1.9起荣誉变化不再触发）

[CHAT\_MSG\_COMBAT\_XP\_GAIN](https://wow.gamepedia.com/CHAT_MSG_COMBAT_XP_GAIN) → [玩家](https://wow.gamepedia.com/Category:API_events/Player) 当你从杀死一个生物或完成任务中获得经验时会触发。如果你没有从杀死一个生物获得经验，则不会触发。

[CHAT\_MSG\_CURRENCY](https://wow.gamepedia.com/CHAT_MSG_CURRENCY) → [劫掠](https://wow.gamepedia.com/Category:API_events/Loot) 当你获得货币以外的货币时会触发（例如[Chef's Awards](https://wow.gamepedia.com/Chef%27s_Award)或[Champion's Seals](https://wow.gamepedia.com/Champion%27s_Seal)）

[CHAT\_MSG\_DND](https://wow.gamepedia.com/CHAT_MSG_DND) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当客户端收到“请勿打扰”自动响应时触发

[CHAT\_MSG\_EMOTE](https://wow.gamepedia.com/CHAT_MSG_EMOTE) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 在发送或接收自定义表情（由/ e，/ emote使用的表格或带有表情标志的发送聊天消息命令）时触发

CHAT\_MSG\_FILTERED → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 

[CHAT\_MSG\_GUILD](https://wow.gamepedia.com/CHAT_MSG_GUILD) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication),[公会](https://wow.gamepedia.com/Category:API_events/Guild) 在公会频道中发送或接收消息时触发。

[CHAT\_MSG\_GUILD\_ACHIEVEMENT](https://wow.gamepedia.com/CHAT_MSG_GUILD_ACHIEVEMENT) → [成就](https://wow.gamepedia.com/Category:API_events/Achievements),[通讯](https://wow.gamepedia.com/Category:API_events/Communication),[公会](https://wow.gamepedia.com/Category:API_events/Guild) 当公会成员完成一项成就时触发。

CHAT\_MSG\_GUILD\_ITEM\_LOOTED → ?

[CHAT\_MSG\_IGNORED](https://wow.gamepedia.com/CHAT_MSG_IGNORED) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)  当你密语一个忽略你的玩家时被触发。当测试这个事件时，角色名称被发送两次作为arg1和arg2，暴雪似乎使用arg2并忽略了arg1。

CHAT\_MSG\_INSTANCE\_CHAT → ?

CHAT\_MSG\_INSTANCE\_CHAT\_LEADER → ?

[CHAT\_MSG\_LOOT](https://wow.gamepedia.com/CHAT_MSG_LOOT) → [劫掠](https://wow.gamepedia.com/Category:API_events/Loot) 战利品文本被发送到聊天窗口时触发（有人选择需求，贪婪，传递，滚动，接收）。这也会通过交易技巧触发“人员创建&lt;item&gt;”等消息，并通过交易窗口触发“人员接收&lt;item&gt;”。

[CHAT\_MSG\_MONEY](https://wow.gamepedia.com/CHAT_MSG_MONEY) → [劫掠](https://wow.gamepedia.com/Category:API_events/Loot) 当一个单位抢钱时触发。

[CHAT\_MSG\_MONSTER\_EMOTE](https://wow.gamepedia.com/CHAT_MSG_MONSTER_EMOTE) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 因为来自怪物的表情而被触发，比如“觅食鱼人试图在恐惧中逃跑！”

[CHAT\_MSG\_MONSTER\_PARTY](https://wow.gamepedia.com/CHAT_MSG_MONSTER_PARTY) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_MONSTER\_SAY](https://wow.gamepedia.com/CHAT_MSG_MONSTER_SAY) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当NPC说某事时触发。

[CHAT\_MSG\_MONSTER\_WHISPER](https://wow.gamepedia.com/CHAT_MSG_MONSTER_WHISPER) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当一个NPC密语你时触发

[CHAT\_MSG\_MONSTER\_YELL](https://wow.gamepedia.com/CHAT_MSG_MONSTER_YELL) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当NPC大喊大叫时，例如副本boss或奥特兰克山谷先锋大喊大叫。

[CHAT\_MSG\_OFFICER](https://wow.gamepedia.com/CHAT_MSG_OFFICER) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 在公会官员频道发送或接收消息时触发。

CHAT\_MSG\_OPENING → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_PARTY](https://wow.gamepedia.com/CHAT_MSG_PARTY) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)，[队伍](#) 在小队频道中发送或接收消息时触发。

[CHAT\_MSG\_PARTY\_LEADER](https://wow.gamepedia.com/CHAT_MSG_PARTY_LEADER) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)，[队伍](#) 当队长发送或接收消息时触发。

CHAT\_MSG\_PET\_BATTLE\_COMBAT\_LOG → ?

CHAT\_MSG\_PET\_BATTLE\_INFO → ?

CHAT\_MSG\_PET\_INFO → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_RAID](https://wow.gamepedia.com/CHAT_MSG_RAID) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)，[队伍](#) 在团队中发送或接收消息时触发。

[CHAT\_MSG\_RAID\_BOSS\_EMOTE](https://wow.gamepedia.com/CHAT_MSG_RAID_BOSS_EMOTE) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

CHAT\_MSG\_RAID\_BOSS\_WHISPER → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_RAID\_LEADER](https://wow.gamepedia.com/CHAT_MSG_RAID_LEADER) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)，[队伍](#)  从团队领袖发送或接收消息时触发。

[CHAT\_MSG\_RAID\_WARNING](https://wow.gamepedia.com/CHAT_MSG_RAID_WARNING) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)，[队伍](#) 从团队领导发送或接收警告消息时触发。

CHAT\_MSG\_RESTRICTED → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_SAY](https://wow.gamepedia.com/CHAT_MSG_SAY) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 在Say通道中发送或接收消息时触发。

[CHAT\_MSG\_SKILL](https://wow.gamepedia.com/CHAT_MSG_SKILL) → [玩家](https://wow.gamepedia.com/Category:API_events/Player),[技能](https://wow.gamepedia.com/Category:API_events/Skill) 在显示有关技能的聊天消息时触发。

[CHAT\_MSG\_SYSTEM](https://wow.gamepedia.com/CHAT_MSG_SYSTEM) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 收到系统聊天消息（它们以黄色显示）时触发。

[CHAT\_MSG\_TARGETICONS](https://wow.gamepedia.com/CHAT_MSG_TARGETICONS) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) raid目标图标设置时触发。如果玩家正在观看聊天输出中的raid图标（在“过滤器”右键菜单中，在“其他”下，查找“目标图标”），聊天过滤器将使用此选项。

[CHAT\_MSG\_TEXT\_EMOTE](https://wow.gamepedia.com/CHAT_MSG_TEXT_EMOTE) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 使用表情符号激发表情。/dance，/ healme等

CHAT\_MSG\_TRADESKILLS → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_MSG\_WHISPER](https://wow.gamepedia.com/CHAT_MSG_WHISPER) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当从另一位玩家收到密语时触发。

[CHAT\_MSG\_WHISPER\_INFORM](https://wow.gamepedia.com/CHAT_MSG_WHISPER_INFORM) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 当玩家向另一位玩家发送密语时被触发

[CHAT\_MSG\_YELL](https://wow.gamepedia.com/CHAT_MSG_YELL) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication) 在大喊频道中发送或接收消息时触发。

[CHAT\_SERVER\_DISCONNECTED](https://wow.gamepedia.com/CHAT_SERVER_DISCONNECTED) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHAT\_SERVER\_RECONNECTED](https://wow.gamepedia.com/CHAT_SERVER_RECONNECTED) → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

CINEMATIC\_START → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

CINEMATIC\_STOP → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

CLEAR\_BOSS\_EMOTES → ?

CLOSE\_INBOX\_ITEM → [邮件](https://wow.gamepedia.com/Category:API_events/Mail)

[CLOSE\_TABARD\_FRAME](https://wow.gamepedia.com/CLOSE_TABARD_FRAME) → [杂项](https://wow.gamepedia.com/Category:API_events/Misc) 公会战袍框架关闭时被触发

[CLOSE\_WORLD\_MAP](https://wow.gamepedia.com/CLOSE_WORLD_MAP) →  [地图](https://wow.gamepedia.com/Category:API_events/Map)  假设世界地图被关闭/隐藏时会触发，但事实并非如此。解决方法是使用“WORLD\_MAP\_UPDATE”设置全局变量，在其他地方使用OnUpdate函数

[COMBAT\_LOG\_EVENT](https://wow.gamepedia.com/COMBAT_LOG_EVENT) → [战斗](https://wow.gamepedia.com/Category:API_events/Combat) 

[COMBAT\_LOG\_EVENT\_UNFILTERED](https://wow.gamepedia.com/COMBAT_LOG_EVENT_UNFILTERED) → [战斗](https://wow.gamepedia.com/Category:API_events/Combat)

  


