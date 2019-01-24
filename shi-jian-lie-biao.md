# 事件列表

###### 此列表是补丁7.3.5（2018-02-01）的最新列表。

[ACHIEVEMENT\_EARNED](https://wow.gamepedia.com/ACHIEVEMENT_EARNED) → [成就](https://wow.gamepedia.com/Category:API_events/Achievements)  获得成就时触发

ACHIEVEMENT\_SEARCH\_UPDATED → ?

[ACTIONBAR\_HIDEGRID](https://wow.gamepedia.com/ACTIONBAR_HIDEGRID) → [动作条](https://wow.gamepedia.com/Category:API_events/Action_Bar) 当动作条编号消失时触发，通常是在您将某些内容拖动到动作条时

[ACTIONBAR\_PAGE\_CHANGED](https://wow.gamepedia.com/ACTIONBAR_PAGE_CHANGED) → [动作条](https://wow.gamepedia.com/Category:API_events/Action_Bar) 操作栏页面更改时触发，通常是在按上一页和下一页按钮时。

[ACTIONBAR\_SHOWGRID](https://wow.gamepedia.com/ACTIONBAR_SHOWGRID) → [动作条](https://wow.gamepedia.com/Category:API_events/Action_Bar) 当动作条编号出现时触发，通常是在将一个技能拖动到动作条时

ACTIONBAR\_SHOW\_BOTTOMLEFT → ?

[ACTIONBAR\_SLOT\_CHANGED](https://wow.gamepedia.com/ACTIONBAR_SLOT_CHANGED) → [动作条](https://wow.gamepedia.com/Category:API_events/Action_Bar)  当任何动作条按钮的内容发生变化时触发;通常是按钮的拖入和拖出

[ACTIONBAR\_UPDATE\_COOLDOWN](https://wow.gamepedia.com/ACTIONBAR_UPDATE_COOLDOWN) → [动作条](https://wow.gamepedia.com/Category:API_events/Action_Bar) 当动作条或背包槽的冷却时间开始或停止时触发。登录新区域时也会触发。

[ACTIONBAR\_UPDATE\_STATE](https://wow.gamepedia.com/ACTIONBAR_UPDATE_STATE) → [动作条](#) 当动作条上任何内容的状态发生变化时触发。这包括冷却和禁用。

[ACTIONBAR\_UPDATE\_USABLE](https://wow.gamepedia.com/ACTIONBAR_UPDATE_USABLE) → [动作条](#) 当动作条中的某些内容或您的商品资源变得可用时（例如，在进食或饮用药水，进入/离开隐身之后）就会被触发。这受到可用的怒气/法力/能量的影响，但不受范围的影响。

ACTION\_WILL\_BIND\_ITEM → ?

ACTIVATE\_GLYPH → ?

[ACTIVE\_TALENT\_GROUP\_CHANGED](https://wow.gamepedia.com/ACTIVE_TALENT_GROUP_CHANGED) → [玩家](https://wow.gamepedia.com/Category:API_events/Player) 当玩家切换哪个天赋组（双重专精）处于活动状态时触发。

ADDONS\_UNLOADING → ?

[ADDON\_ACTION\_BLOCKED](https://wow.gamepedia.com/ADDON_ACTION_BLOCKED) → [系统](https://wow.gamepedia.com/Category:API_events/System) （此事件似乎不再使用，请改用ADDON\_ACTION\_FORBIDDEN）

[ADDON\_ACTION\_FORBIDDEN](https://wow.gamepedia.com/ADDON_ACTION_FORBIDDEN) → [系统](https://wow.gamepedia.com/Category:API_events/System)  当AddOn尝试使用始终被禁止的操作（移动，定位等）时触发。

[ADDON\_LOADED](https://wow.gamepedia.com/ADDON_LOADED) → [系统](https://wow.gamepedia.com/Category:API_events/System) 加载插件后立即触发 - 即其[.toc](https://wow.gamepedia.com/.toc)文件中的所有文件都已执行，并且已加载其SavedVariables（如果已声明）。

ADVENTURE\_MAP\_CLOSE → ?

ADVENTURE\_MAP\_OPEN → ?

ADVENTURE\_MAP\_QUEST\_UPDATE → ?

ADVENTURE\_MAP\_UPDATE\_INSETS → ?

ADVENTURE\_MAP\_UPDATE\_POIS → ?

AJ\_DUNGEON\_ACTION → ?

AJ\_OPEN → ?

AJ\_PVE\_LFG\_ACTION → ?

AJ\_PVP\_ACTION → ?

AJ\_PVP\_LFG\_ACTION → ?

AJ\_PVP\_RBG\_ACTION → ?

AJ\_PVP\_SKIRMISH\_ACTION → ?

AJ\_QUEST\_LOG\_OPEN → ?

AJ\_RAID\_ACTION → ?

AJ\_REFRESH\_DISPLAY → ?

AJ\_REWARD\_DATA\_RECEIVED → ?

ALLIED\_RACE\_CLOSE → ?

ALLIED\_RACE\_OPEN → ?

ALTERNATIVE\_DEFAULT\_LANGUAGE\_CHANGED → ?

[ARCHAEOLOGY\_CLOSED](https://wow.gamepedia.com/ARCHAEOLOGY_CLOSED) → [考古](https://wow.gamepedia.com/Category:API_events/Archaeology) 无论方法如何（单击X，按Esc，按考古按钮等），只要考古窗口关闭，此事件就会触发。

ARCHAEOLOGY\_FIND\_COMPLETE → ?

ARCHAEOLOGY\_SURVEY\_CAST → ?

[ARCHAEOLOGY\_TOGGLE](https://wow.gamepedia.com/ARCHAEOLOGY_TOGGLE) → [考古](https://wow.gamepedia.com/Category:API_events/Archaeology) 只要使用了法术书中的考古按钮，就会触发此事件。这包括再次按下按钮关闭窗口。

AREA\_SPIRIT\_HEALER\_IN\_RANGE → [死亡](https://wow.gamepedia.com/Category:API_events/Death)

AREA\_SPIRIT\_HEALER\_OUT\_OF\_RANGE → [死亡](https://wow.gamepedia.com/Category:API_events/Death)

ARENA\_COOLDOWNS\_UPDATE → ?

ARENA\_CROWD\_CONTROL\_SPELL\_UPDATE → ?

ARENA\_OPPONENT\_UPDATE → [竞技场](https://wow.gamepedia.com/Category:API_events/Arena)

ARENA\_PREP\_OPPONENT\_SPECIALIZATIONS → ?

ARENA\_SEASON\_WORLD\_STATE → [竞技场](https://wow.gamepedia.com/Category:API_events/Arena)

ARTIFACT\_CLOSE → [神器](https://wow.gamepedia.com/Category:API_events/Artifact)

ARTIFACT\_DIGSITE\_COMPLETE → ?

ARTIFACT\_ENDGAME\_REFUND → ?

ARTIFACT\_RELIC\_FORGE\_CLOSE → ?

ARTIFACT\_RELIC\_FORGE\_PREVIEW\_RELIC\_CHANGED → ?

ARTIFACT\_RELIC\_FORGE\_UPDATE → ?

ARTIFACT\_RELIC\_INFO\_RECEIVED → ?

ARTIFACT\_RESPEC\_PROMPT → ?

ARTIFACT\_TIER\_CHANGED → ?

[ARTIFACT\_UPDATE](https://wow.gamepedia.com/ARTIFACT_UPDATE) → [考古学](https://wow.gamepedia.com/Category:API_events/Archaeology),[神器](https://wow.gamepedia.com/Category:API_events/Artifact) 每当更新碎片的数据（例如，在完成新碎片之后）时，将触发此事件。

[ARTIFACT\_XP\_UPDATE](https://wow.gamepedia.com/ARTIFACT_XP_UPDATE) → [神器](https://wow.gamepedia.com/Category:API_events/Artifact) 当为当前装备的神器武器获得神器能量时触发事件。

[AUCTION\_BIDDER\_LIST\_UPDATE](https://wow.gamepedia.com/AUCTION_BIDDER_LIST_UPDATE) → [拍卖行](https://wow.gamepedia.com/Category:API_events/Auction)

[AUCTION\_HOUSE\_CLOSED](https://wow.gamepedia.com/AUCTION_HOUSE_CLOSED) → [拍卖行](https://wow.gamepedia.com/Category:API_events/Auction)  拍卖界面关闭时会触发此事件。

[AUCTION\_HOUSE\_DISABLED](https://wow.gamepedia.com/AUCTION_HOUSE_DISABLED) → [拍卖行](https://wow.gamepedia.com/Category:API_events/Auction) 拍卖行无法运作时被触发。

[AUCTION\_HOUSE\_SHOW](https://wow.gamepedia.com/AUCTION_HOUSE_SHOW) → [拍卖行](https://wow.gamepedia.com/Category:API_events/Auction) 首次显示拍卖界面时会触发此事件。这通常通过右键单击主要城市中的拍卖师来完成。

[AUCTION\_ITEM\_LIST\_UPDATE](https://wow.gamepedia.com/AUCTION_ITEM_LIST_UPDATE) → [拍卖行](https://wow.gamepedia.com/Category:API_events/Auction) 更新拍卖列表时会触发此事件。

[AUCTION\_MULTISELL\_FAILURE](https://wow.gamepedia.com/AUCTION_MULTISELL_FAILURE) → [拍卖行](https://wow.gamepedia.com/Category:API_events/Auction) 列出多个堆失败（或中止？）时触发。

[AUCTION\_MULTISELL\_START](https://wow.gamepedia.com/AUCTION_MULTISELL_START) → [拍卖行](https://wow.gamepedia.com/Category:API_events/Auction) 当客户端开始列出多个堆栈时触发。

[AUCTION\_MULTISELL\_UPDATE](https://wow.gamepedia.com/AUCTION_MULTISELL_UPDATE) → [拍卖行](https://wow.gamepedia.com/Category:API_events/Auction) 当客户端列出堆作为列出多个堆的一部分时触发。

AUCTION\_OWNED\_LIST\_UPDATE → [拍卖行](https://wow.gamepedia.com/Category:API_events/Auction)

AUTH\_CHALLENGE\_FINISHED → ?

AUTH\_CHALLENGE\_UI\_INVALID → ?

[AUTOFOLLOW\_BEGIN](https://wow.gamepedia.com/AUTOFOLLOW_BEGIN) → [移动](https://wow.gamepedia.com/Category:API_events/Movement) 当你开始自动跟随一个盟友时被触发。

[AUTOFOLLOW\_END](https://wow.gamepedia.com/AUTOFOLLOW_END) → [移动](https://wow.gamepedia.com/Category:API_events/Movement) 当你停止自动跟随一个盟友时被触发。

AVOIDANCE\_UPDATE → ?

[BAG\_CLOSED](https://wow.gamepedia.com/BAG_CLOSED) → [物品](https://wow.gamepedia.com/Category:API_events/Item) 当背包从背包槽里移动（删除）时被触发。玩家背包和银行都会触发。

BAG\_NEW\_ITEMS\_UPDATED → ?

[BAG\_OPEN](https://wow.gamepedia.com/BAG_OPEN) → [物品](https://wow.gamepedia.com/Category:API_events/Item) 当可打开的容器（不是装备的包）被打开时被触发。

BAG\_OVERFLOW\_WITH\_FULL\_INVENTORY → ?

BAG\_SLOT\_FLAGS\_UPDATED → ?

[BAG\_UPDATE](https://wow.gamepedia.com/BAG_UPDATE) → [物品](https://wow.gamepedia.com/Category:API_events/Item) 当背包库存发生变化时被触发。包0，16槽默认背包，登录时可能不会触发。登录（或重新加载控制台）后，即使是银行库存也会触发此事件。移动库存中的物品时，会多次触发：源袋和目标袋各一次。如果所涉及的物品是默认背包，则此事件也将以容器ID“-2”（如果您在同一行李中移动物品，则两次）触发。

[BAG\_UPDATE\_COOLDOWN](https://wow.gamepedia.com/BAG_UPDATE_COOLDOWN) → [物品](https://wow.gamepedia.com/Category:API_events/Item) 将冷却更新调用发送到行李时触发

[BAG\_UPDATE\_DELAYED](https://wow.gamepedia.com/BAG_UPDATE_DELAYED) → [物品](https://wow.gamepedia.com/Category:API_events/Item) 在针对特定操作的所有适用的BAG\_UPDATE事件被触发后触发。

[BANKFRAME\_CLOSED](https://wow.gamepedia.com/BANKFRAME_CLOSED) → [银行](https://wow.gamepedia.com/Category:API_events/Bank) 银行窗口关闭时触发两次。

[BANKFRAME\_OPENED](https://wow.gamepedia.com/BANKFRAME_OPENED) → [银行](https://wow.gamepedia.com/Category:API_events/Bank) 银行窗口打开时触发

BANK\_BAG\_SLOT\_FLAGS\_UPDATED → ?

BARBER\_SHOP\_APPEARANCE\_APPLIED → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

BARBER\_SHOP\_CLOSE → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

BARBER\_SHOP\_COST\_UPDATE → ?

BARBER\_SHOP\_OPEN → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

BARBER\_SHOP\_SUCCESS → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

[BATTLEFIELDS\_CLOSED](https://wow.gamepedia.com/BATTLEFIELDS_CLOSED) → [战场](https://wow.gamepedia.com/Category:API_events/Battleground) 当战场窗口关闭时触发。

[BATTLEFIELDS\_SHOW](https://wow.gamepedia.com/BATTLEFIELDS_SHOW) → [战场](https://wow.gamepedia.com/Category:API_events/Battleground) 在战场窗口打开时触发。

BATTLEFIELD\_MGR\_DROP\_TIMER\_CANCELED → ?

BATTLEFIELD\_MGR\_DROP\_TIMER\_STARTED → ?

BATTLEFIELD\_MGR\_EJECTED → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

BATTLEFIELD\_MGR\_EJECT\_PENDING → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

BATTLEFIELD\_MGR\_ENTERED → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

BATTLEFIELD\_MGR\_ENTRY\_INVITE → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

BATTLEFIELD\_MGR\_QUEUE\_INVITE → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

BATTLEFIELD\_MGR\_QUEUE\_REQUEST\_RESPONSE → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

BATTLEFIELD\_MGR\_QUEUE\_STATUS\_UPDATE → ?

BATTLEFIELD\_MGR\_STATE\_CHANGE → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

[BATTLEFIELD\_QUEUE\_TIMEOUT](https://wow.gamepedia.com/BATTLEFIELD_QUEUE_TIMEOUT) → [杂项](https://wow.gamepedia.com/Category:API_events/Misc) 当战争游戏请求超时而没有响应时被触发。

BATTLEGROUND\_OBJECTIVES\_UPDATE → ?

BATTLEGROUND\_POINTS\_UPDATE → ?

BATTLEPET\_FORCE\_NAME\_DECLENSION → ?

BATTLETAG\_INVITE\_SHOW → ?

BATTLE\_PET\_CURSOR\_CLEAR → ?

BILLING\_NAG\_DIALOG → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

[BIND\_ENCHANT](https://wow.gamepedia.com/BIND_ENCHANT) → [物品 ](https://wow.gamepedia.com/Category:API_events/Item)附加未绑定项目时触发。

BLACK\_MARKET\_BID\_RESULT → ?

BLACK\_MARKET\_CLOSE → ?

BLACK\_MARKET\_ITEM\_UPDATE → ?

BLACK\_MARKET\_OPEN → ?

BLACK\_MARKET\_OUTBID → ?

BLACK\_MARKET\_UNAVAILABLE → ?

BLACK\_MARKET\_WON → ?

[BN\_BLOCK\_FAILED\_TOO\_MANY](https://wow.gamepedia.com/BN_BLOCK_FAILED_TOO_MANY) → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_BLOCK\_LIST\_UPDATED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_CHAT\_MSG\_ADDON → ?

BN\_CHAT\_WHISPER\_UNDELIVERABLE → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_CONNECTED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_CUSTOM\_MESSAGE\_CHANGED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_CUSTOM\_MESSAGE\_LOADED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_DISCONNECTED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

[BN\_FRIEND\_ACCOUNT\_OFFLINE](https://wow.gamepedia.com/BN_FRIEND_ACCOUNT_OFFLINE) → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

[BN\_FRIEND\_ACCOUNT\_ONLINE](https://wow.gamepedia.com/BN_FRIEND_ACCOUNT_ONLINE) → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_FRIEND\_INFO\_CHANGED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_FRIEND\_INVITE\_ADDED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_FRIEND\_INVITE\_LIST\_INITIALIZED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_FRIEND\_INVITE\_REMOVED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_FRIEND\_INVITE\_SEND\_RESULT → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_FRIEND\_LIST\_SIZE\_CHANGED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_INFO\_CHANGED → ?

BN\_NEW\_PRESENCE → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_REQUEST\_FOF\_FAILED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_REQUEST\_FOF\_SUCCEEDED → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_SELF\_OFFLINE → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_SELF\_ONLINE → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BN\_SYSTEM\_MESSAGE → [战网](https://wow.gamepedia.com/Category:API_events/Battle.net)

BONUS\_ROLL\_ACTIVATE → ?

BONUS\_ROLL\_DEACTIVATE → ?

BONUS\_ROLL\_FAILED → ?

BONUS\_ROLL\_RESULT → ?

BONUS\_ROLL\_STARTED → ?

[BOSS\_KILL](https://wow.gamepedia.com/BOSS_KILL) → ? 当玩家杀死raid boss时被触发。

[CALENDAR\_ACTION\_PENDING](https://wow.gamepedia.com/CALENDAR_ACTION_PENDING) → [日历](https://wow.gamepedia.com/Category:API_events/Calendar) 在日历API繁忙或空闲时触发

CALENDAR\_CLOSE\_EVENT → [日历](https://wow.gamepedia.com/Category:API_events/Calendar)

CALENDAR\_EVENT\_ALARM → [日历](https://wow.gamepedia.com/Category:API_events/Calendar)

CALENDAR\_NEW\_EVENT → [日历](https://wow.gamepedia.com/Category:API_events/Calendar)

[CALENDAR\_OPEN\_EVENT](https://wow.gamepedia.com/CALENDAR_OPEN_EVENT) → [日历](https://wow.gamepedia.com/Category:API_events/Calendar) 从服务器检索到事件数据后，在调用CalendarOpenEvent后触发

CALENDAR\_UPDATE\_ERROR → [日历](https://wow.gamepedia.com/Category:API_events/Calendar)

CALENDAR\_UPDATE\_EVENT → [日历](https://wow.gamepedia.com/Category:API_events/Calendar)

CALENDAR\_UPDATE\_EVENT\_LIST → [日历](https://wow.gamepedia.com/Category:API_events/Calendar)

[CALENDAR\_UPDATE\_GUILD\_EVENTS](https://wow.gamepedia.com/CALENDAR_UPDATE_GUILD_EVENTS) → [日历](https://wow.gamepedia.com/Category:API_events/Calendar)

[CALENDAR\_UPDATE\_INVITE\_LIST](https://wow.gamepedia.com/CALENDAR_UPDATE_INVITE_LIST) → [日历](https://wow.gamepedia.com/Category:API_events/Calendar) 一旦对邀请列表进行了排序，就会在CalendarEventSortInvites之后触发。

CALENDAR\_UPDATE\_PENDING\_INVITES → [日历](https://wow.gamepedia.com/Category:API_events/Calendar)

CANCEL\_GLYPH\_CAST → ?

[CANCEL\_LOOT\_ROLL](https://wow.gamepedia.com/CANCEL_LOOT_ROLL) → [劫掠](https://wow.gamepedia.com/Category:API_events/Loot) 当玩家取消对某个项目的roll点时触发

CANCEL\_SUMMON → [玩家](https://wow.gamepedia.com/Category:API_events/Player)

CHALLENGE\_MODE\_COMPLETED → ?

CHALLENGE\_MODE\_DEATH\_COUNT\_UPDATED → ?

CHALLENGE\_MODE\_KEYSTONE\_RECEPTABLE\_OPEN → ?

CHALLENGE\_MODE\_KEYSTONE\_SLOTTED → ?

CHALLENGE\_MODE\_LEADERS\_UPDATE → ?

CHALLENGE\_MODE\_MAPS\_UPDATE → ?

CHALLENGE\_MODE\_NEW\_RECORD → ?

CHALLENGE\_MODE\_RESET → ?

CHALLENGE\_MODE\_START → ?

[CHANNEL\_COUNT\_UPDATE](https://wow.gamepedia.com/CHANNEL_COUNT_UPDATE) → [杂项](https://wow.gamepedia.com/Category:API_events/Misc) 当频道中的玩家数量发生变化时触发。但仅当此频道在频道框架中可见时才会被触发（不得被折叠的类别标题隐藏）

[CHANNEL\_FLAGS\_UPDATED](https://wow.gamepedia.com/CHANNEL_FLAGS_UPDATED) → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)  用户在暴雪频道框架中更改所选频道时触发

CHANNEL\_INVITE\_REQUEST → [通讯](https://wow.gamepedia.com/Category:API_events/Communication)

[CHANNEL\_PASSWORD\_REQUEST](https://wow.gamepedia.com/CHANNEL_PASSWORD_REQUEST) → [杂项](https://wow.gamepedia.com/Category:API_events/Misc) 在要求用户输入密码时触发（通常在尝试加入没有密码或错误密码的频道后）

[CHANNEL\_ROSTER\_UPDATE](https://wow.gamepedia.com/CHANNEL_ROSTER_UPDATE) → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)  当用户更改暴雪频道框架中的所选频道或当前所选频道中的播放器数量更改时触发

[CHANNEL\_UI\_UPDATE](https://wow.gamepedia.com/CHANNEL_UI_UPDATE) → [杂项](https://wow.gamepedia.com/Category:API_events/Misc) 频道用户界面应该更改时触发（例如加入/离开频道会导致此事件触发）

CHANNEL\_VOICE\_UPDATE → [杂项](https://wow.gamepedia.com/Category:API_events/Misc)

CHARACTER\_ITEM\_FIXUP\_NOTIFICATION → ?

[CHARACTER\_POINTS\_CHANGED](https://wow.gamepedia.com/CHARACTER_POINTS_CHANGED) → [玩家](https://wow.gamepedia.com/Category:API_events/Player) 当玩家的可用天赋点发生变化时被触发

CHARACTER\_UPGRADE\_SPELL\_TIER\_SET → ?

CHAT\_COMBAT\_MSG\_ARENA\_POINTS\_GAIN → ?



  


  


  


  


  


  


  


  
  


  


  


  


  


  


  


