# GroupInvitation 插件

## 简介

`GroupInvitation` 插件允许您的聊天机器人根据特定关键词自动邀请用户加入指定的群聊。这个插件适用于需要基于用户消息内容自动处理群聊邀请的场景。

## 安装

此插件作为聊天机器人系统的一部分，需要将其放置在正确的插件目录下：

1. 将 `group_invitation` 文件夹复制到您的聊天机器人的 `plugins` 目录中。
2. 确保 `__init__.py` 和 `group_invitation.py` 文件位于 `group_invitation` 文件夹中。

## 配置

`GroupInvitation` 插件依赖于 `config.json` 文件进行配置。请按照以下步骤进行配置：

1. 复制 `config.json.template` 文件并重命名为 `config.json`。
2. 在 `config.json` 文件中，添加您希望机器人响应的关键词和对应的群聊名称。例如：

   ```json
   {
       "群聊": "我的群聊"
   }
   ```

   这意味着当用户发送包含“群聊”这一关键词的消息时，机器人将尝试邀请该用户加入名为“我的群聊”的群组。

## 使用

安装并正确配置插件后，当机器人收到包含特定关键词的消息时，它将自动触发群聊邀请流程。

## 贡献

如果您有任何改进意见或功能请求，请随时提交 Pull Request 或创建 Issue。

## 许可

请确保遵守相关的使用和分发许可。