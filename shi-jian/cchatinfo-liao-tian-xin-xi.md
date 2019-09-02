### C\_ChatInfo

* [ALTERNATIVE\_DEFAULT\_LANGUAGE\_CHANGED](https://wow.gamepedia.com/ALTERNATIVE_DEFAULT_LANGUAGE_CHANGED)
* [BN\_CHAT\_MSG\_ADDON](https://wow.gamepedia.com/BN_CHAT_MSG_ADDON)
* [CHANNEL\_COUNT\_UPDATE](https://wow.gamepedia.com/CHANNEL_COUNT_UPDATE) - 当频道中的玩家数量发生变化时触发，但仅当此频道在ChannelFrame中可见时才会被触发（不得被折叠的类别标题隐藏）。
* [CHANNEL\_FLAGS\_UPDATED](https://wow.gamepedia.com/CHANNEL_FLAGS_UPDATED) - 用户在Blizzards ChannelFrame中更改所选频道时触发。
* [CHANNEL\_INVITE\_REQUEST](https://wow.gamepedia.com/CHANNEL_INVITE_REQUEST)
* [CHANNEL\_LEFT](https://wow.gamepedia.com/CHANNEL_LEFT)
* [CHANNEL\_PASSWORD\_REQUEST](https://wow.gamepedia.com/CHANNEL_PASSWORD_REQUEST) - 在要求用户输入密码时触发（通常在不使用密码或错误密码来尝试加入频道后）。
* [CHANNEL\_ROSTER\_UPDATE](https://wow.gamepedia.com/CHANNEL_ROSTER_UPDATE) - 当用户更改Blizzards ChannelFrame中的所选频道或当前所选频道中的玩家数量更改时触发。
* [CHANNEL\_UI\_UPDATE](https://wow.gamepedia.com/CHANNEL_UI_UPDATE) - 频道用户界面应该更改时触发（例如加入/离开频道会导致此事件触发）
* [CHAT\_COMBAT\_MSG\_ARENA\_POINTS\_GAIN](https://wow.gamepedia.com/CHAT_COMBAT_MSG_ARENA_POINTS_GAIN)
* [CHAT\_MSG\_ACHIEVEMENT](https://wow.gamepedia.com/CHAT_MSG_ACHIEVEMENT) - 当你附近的玩家获得成就时触发
* [CHAT\_MSG\_ADDON](https://wow.gamepedia.com/CHAT_MSG_ADDON) - 客户端从[C\_ChatInfo.SendAddonMessage](https://wow.gamepedia.com/API_C_ChatInfo.SendAddonMessage)收到消息时触发。
* [CHAT\_MSG\_ADDON\_LOGGED](https://wow.gamepedia.com/CHAT_MSG_ADDON_LOGGED) - 客户端从[C\_ChatInfo.SendAddonMessageLogged](https://wow.gamepedia.com/API_C_ChatInfo.SendAddonMessageLogged)收到消息时触发。
* [CHAT\_MSG\_AFK](https://wow.gamepedia.com/CHAT_MSG_AFK) - 当客户端收到AFK自动响应时触发
* [CHAT\_MSG\_BG\_SYSTEM\_ALLIANCE](https://wow.gamepedia.com/CHAT_MSG_BG_SYSTEM_ALLIANCE) - 对于默认为蓝色的战场事件消息触发，因为它们与联盟行动有关，例如袭击墓地或捕获点，或拿起旗帜。
* [CHAT\_MSG\_BG\_SYSTEM\_HORDE](https://wow.gamepedia.com/CHAT_MSG_BG_SYSTEM_HORDE) - 对于默认为红色的战场事件消息触发，因为它们与部落行动有关
* [CHAT\_MSG\_BG\_SYSTEM\_NEUTRAL](https://wow.gamepedia.com/CHAT_MSG_BG_SYSTEM_NEUTRAL) - 对于默认情况下以派系中性色显示的战场事件消息触发。
* [CHAT\_MSG\_BN](https://wow.gamepedia.com/CHAT_MSG_BN)
* [CHAT\_MSG\_BN\_INLINE\_TOAST\_ALERT](https://wow.gamepedia.com/CHAT_MSG_BN_INLINE_TOAST_ALERT)
* [CHAT\_MSG\_BN\_INLINE\_TOAST\_BROADCAST](https://wow.gamepedia.com/CHAT_MSG_BN_INLINE_TOAST_BROADCAST)
* [CHAT\_MSG\_BN\_INLINE\_TOAST\_BROADCAST\_INFORM](https://wow.gamepedia.com/CHAT_MSG_BN_INLINE_TOAST_BROADCAST_INFORM) - 更改Bnet Real ID广播消息时或从[BNSetCustomMessage](https://wow.gamepedia.com/API_BNSetCustomMessage)触发。
* [CHAT\_MSG\_BN\_INLINE\_TOAST\_CONVERSATION](https://wow.gamepedia.com/CHAT_MSG_BN_INLINE_TOAST_CONVERSATION)
* [CHAT\_MSG\_BN\_WHISPER](https://wow.gamepedia.com/CHAT_MSG_BN_WHISPER)
* [CHAT\_MSG\_BN\_WHISPER\_INFORM](https://wow.gamepedia.com/CHAT_MSG_BN_WHISPER_INFORM)
* [CHAT\_MSG\_BN\_WHISPER\_PLAYER\_OFFLINE](https://wow.gamepedia.com/CHAT_MSG_BN_WHISPER_PLAYER_OFFLINE)
* [CHAT\_MSG\_CHANNEL](https://wow.gamepedia.com/CHAT_MSG_CHANNEL) - 客户端收到频道消息时触发。
* [CHAT\_MSG\_CHANNEL\_JOIN](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_JOIN) - 当有人加入你所在的聊天频道时被触发
* [CHAT\_MSG\_CHANNEL\_LEAVE](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_LEAVE) - 当玩家离开你当前所在的频道时被触发。
* [CHAT\_MSG\_CHANNEL\_LIST](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_LIST) - 调用[ListChannels](https://wow.gamepedia.com/API_ListChannels)或[ListChannelByName](https://wow.gamepedia.com/API_ListChannelByName)时触发，并在聊天框中显示消息。
* [CHAT\_MSG\_CHANNEL\_NOTICE](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_NOTICE) - 当你进入或离开聊天频道（或频道最近被限制）时触发。
* [CHAT\_MSG\_CHANNEL\_NOTICE\_USER](https://wow.gamepedia.com/CHAT_MSG_CHANNEL_NOTICE_USER) - 当频道中的某些内容发生变化时启动，如启用审核，用户被踢，通知发生变化等等。GlobalStrings.lua中的CHAT \_ \* \_ NOTICE包含可用类型的完整列表。
* [CHAT\_MSG\_COMBAT\_FACTION\_CHANGE](https://wow.gamepedia.com/CHAT_MSG_COMBAT_FACTION_CHANGE) - 当你获得派系的声望时触发。
* [CHAT\_MSG\_COMBAT\_HONOR\_GAIN](https://wow.gamepedia.com/CHAT_MSG_COMBAT_HONOR_GAIN) - 当玩家获得任何荣誉时，从荣誉击杀到奖励荣誉的任何事情都会触发。
* [CHAT\_MSG\_COMBAT\_MISC\_INFO](https://wow.gamepedia.com/CHAT_MSG_COMBAT_MISC_INFO) - 当你的装备因死亡而导致持久性损失时触发，也可能是其他情况。
* [CHAT\_MSG\_COMBAT\_XP\_GAIN](https://wow.gamepedia.com/CHAT_MSG_COMBAT_XP_GAIN) - 当你从杀死一个生物或完成一个任务中获得经验时会触发。如果你没有从杀死一个生物获得经验，则不会触发。
* [CHAT\_MSG\_COMMUNITIES\_CHANNEL](https://wow.gamepedia.com/CHAT_MSG_COMMUNITIES_CHANNEL) 
* [CHAT\_MSG\_CURRENCY](https://wow.gamepedia.com/CHAT_MSG_CURRENCY) - 当你获得金钱以外的货币时触发（例如[厨师徽记](https://wow.gamepedia.com/Chef%27s_Award)或[冠军的徽记](https://wow.gamepedia.com/Champion%27s_Seal)）。
* [CHAT\_MSG\_DND](https://wow.gamepedia.com/CHAT_MSG_DND) - 当客户端收到“请勿打扰”自动响应时触发。
* [CHAT\_MSG\_EMOTE](https://wow.gamepedia.com/CHAT_MSG_EMOTE) - 在发送或接收自定义表情（使用/ e，/ emote或使用emote标记发送聊天命令）时触发。
* [CHAT\_MSG\_FILTERED](https://wow.gamepedia.com/CHAT_MSG_FILTERED)
* [CHAT\_MSG\_GUILD](https://wow.gamepedia.com/CHAT_MSG_GUILD) - 在公会频道中发送或接收消息时触发。
* [CHAT\_MSG\_GUILD\_ACHIEVEMENT](https://wow.gamepedia.com/CHAT_MSG_GUILD_ACHIEVEMENT) - 当公会成员完成一项成就时触发。
* [CHAT\_MSG\_GUILD\_ITEM\_LOOTED](https://wow.gamepedia.com/CHAT_MSG_GUILD_ITEM_LOOTED)
* [CHAT\_MSG\_IGNORED](https://wow.gamepedia.com/CHAT_MSG_IGNORED) - 当你密语屏蔽你的人时触发。
* [CHAT\_MSG\_INSTANCE\_CHAT](https://wow.gamepedia.com/CHAT_MSG_INSTANCE_CHAT) 
* [CHAT\_MSG\_INSTANCE\_CHAT\_LEADER](https://wow.gamepedia.com/CHAT_MSG_INSTANCE_CHAT_LEADER)
* [CHAT\_MSG\_LOOT](https://wow.gamepedia.com/CHAT_MSG_LOOT) - 战利品文本被发送到聊天窗口时触发（有人选择需求，贪婪，放弃，roll，接收）。这也会通过“某人制造 &lt;物品&gt;”等消息，以及通过交易窗口“某人收到 &lt;物品&gt;”。不接收货币（为此使用[CHAT\_MSG\_CURRENCY](https://wow.gamepedia.com/CHAT_MSG_CURRENCY)）。
* [CHAT\_MSG\_MONEY](https://wow.gamepedia.com/CHAT_MSG_MONEY) - 当单位劫掠金币时触发
* [CHAT\_MSG\_MONSTER\_EMOTE](https://wow.gamepedia.com/CHAT_MSG_MONSTER_EMOTE) - 收到来自怪物的表情时触发
* [CHAT\_MSG\_MONSTER\_PARTY](https://wow.gamepedia.com/CHAT_MSG_MONSTER_PARTY)
* [CHAT\_MSG\_MONSTER\_SAY](https://wow.gamepedia.com/CHAT_MSG_MONSTER_SAY) - NPC说话时触发。 _注：（我不知道为什么是NPC，见原文）_
* [CHAT\_MSG\_MONSTER\_WHISPER](https://wow.gamepedia.com/CHAT_MSG_MONSTER_WHISPER)  - NPC密语你时触发。
* [CHAT\_MSG\_MONSTER\_YELL](https://wow.gamepedia.com/CHAT_MSG_MONSTER_YELL) - NPC大喊时触发。例子应该是团队boss或奥山的先锋大喊
* [CHAT\_MSG\_OFFICER](https://wow.gamepedia.com/CHAT_MSG_OFFICER) - 在公会官员频道发送或接收消息时触发。
* [CHAT\_MSG\_OPENING](https://wow.gamepedia.com/CHAT_MSG_OPENING)
* [CHAT\_MSG\_PARTY](https://wow.gamepedia.com/CHAT_MSG_PARTY) - 在小队频道中发送或接收消息时触发。
* [CHAT\_MSG\_PARTY\_LEADER](https://wow.gamepedia.com/CHAT_MSG_PARTY_LEADER) - 在团队领袖发送或接收消息时触发。
* [CHAT\_MSG\_PET\_BATTLE\_COMBAT\_LOG](https://wow.gamepedia.com/CHAT_MSG_PET_BATTLE_COMBAT_LOG) 
* [CHAT\_MSG\_PET\_BATTLE\_INFO](https://wow.gamepedia.com/CHAT_MSG_PET_BATTLE_INFO)
* [CHAT\_MSG\_PET\_INFO](https://wow.gamepedia.com/CHAT_MSG_PET_INFO)
* [CHAT\_MSG\_RAID](https://wow.gamepedia.com/CHAT_MSG_RAID)
* [CHAT\_MSG\_RAID\_BOSS\_EMOTE](https://wow.gamepedia.com/CHAT_MSG_RAID_BOSS_EMOTE)
* [CHAT\_MSG\_RAID\_BOSS\_WHISPER](https://wow.gamepedia.com/CHAT_MSG_RAID_BOSS_WHISPER)
* [CHAT\_MSG\_RAID\_LEADER](https://wow.gamepedia.com/CHAT_MSG_RAID_LEADER)
* [CHAT\_MSG\_RAID\_WARNING](https://wow.gamepedia.com/CHAT_MSG_RAID_WARNING)
* [CHAT\_MSG\_RESTRICTED](https://wow.gamepedia.com/CHAT_MSG_RESTRICTED)
* [CHAT\_MSG\_SAY](https://wow.gamepedia.com/CHAT_MSG_SAY)
* [CHAT\_MSG\_SKILL](https://wow.gamepedia.com/CHAT_MSG_SKILL)
* [CHAT\_MSG\_SYSTEM](https://wow.gamepedia.com/CHAT_MSG_SYSTEM)
* [CHAT\_MSG\_TARGETICONS](https://wow.gamepedia.com/CHAT_MSG_TARGETICONS)
* [CHAT\_MSG\_TEXT\_EMOTE](https://wow.gamepedia.com/CHAT_MSG_TEXT_EMOTE)
* [CHAT\_MSG\_TRADESKILLS](https://wow.gamepedia.com/CHAT_MSG_TRADESKILLS)
* [CHAT\_MSG\_WHISPER](https://wow.gamepedia.com/CHAT_MSG_WHISPER)
* [CHAT\_MSG\_WHISPER\_INFORM](https://wow.gamepedia.com/CHAT_MSG_WHISPER_INFORM)
* [CHAT\_MSG\_YELL](https://wow.gamepedia.com/CHAT_MSG_YELL)
* [CHAT\_SERVER\_DISCONNECTED](https://wow.gamepedia.com/CHAT_SERVER_DISCONNECTED)
* [CHAT\_SERVER\_RECONNECTED](https://wow.gamepedia.com/CHAT_SERVER_RECONNECTED)
* [CLEAR\_BOSS\_EMOTES](https://wow.gamepedia.com/CLEAR_BOSS_EMOTES)
* [LANGUAGE\_LIST\_CHANGED](https://wow.gamepedia.com/LANGUAGE_LIST_CHANGED)
* [QUEST\_BOSS\_EMOTE](https://wow.gamepedia.com/QUEST_BOSS_EMOTE)
* [RAID\_BOSS\_EMOTE](https://wow.gamepedia.com/RAID_BOSS_EMOTE)
* [RAID\_BOSS\_WHISPER](https://wow.gamepedia.com/RAID_BOSS_WHISPER)
* [RAID\_INSTANCE\_WELCOME](https://wow.gamepedia.com/RAID_INSTANCE_WELCOME)
* [UPDATE\_CHAT\_COLOR](https://wow.gamepedia.com/UPDATE_CHAT_COLOR)
* [UPDATE\_CHAT\_COLOR\_NAME\_BY\_CLASS](https://wow.gamepedia.com/UPDATE_CHAT_COLOR_NAME_BY_CLASS)
* [UPDATE\_CHAT\_WINDOWS](https://wow.gamepedia.com/UPDATE_CHAT_WINDOWS)
* [UPDATE\_FLOATING\_CHAT\_WINDOWS](https://wow.gamepedia.com/UPDATE_FLOATING_CHAT_WINDOWS)



