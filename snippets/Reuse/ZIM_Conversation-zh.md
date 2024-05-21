## 功能简介

`会话`，指当用户发送“单聊/群聊”消息时，SDK 自动建立的逻辑关系。ZIM SDK 提供了会话管理功能，支持用户登录后拉取会话列表、创建/更新/删除会话、置顶会话等。

通常可以应用在社交聊天、游戏社区、在线咨询等业务场景中，获取展示单聊、群聊会话列表。

<img src="/Pics/ZIM/Common/messagesList.png" width="35%">

<div class="mk-hint">

- ZIM SDK 不维护单聊的好友关系链，因此可以向任何用户发送消息，建立会话关系。如果需要实现用户之间的好友关系连接，请您根据自己的业务需要，自行搭建和维护用户管理逻辑。
- 用户只有在发送了消息后（文本/富媒体消息，不包含自定义消息），才会产生一条会话记录；未发送消息时，没有会话记录产生。
</div>







