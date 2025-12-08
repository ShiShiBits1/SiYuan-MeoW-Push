# MeoW Push & Broadcast Plugin

[简体中文](./README_zh_CN.md)

A plugin for SiYuan Notes that enables MeoW push and broadcast functionality.

## Features

1. **Push Messages**: Send personal push messages with custom content
2. **Broadcast Messages**: Send broadcast messages to specified channels
3. **Settings**: Configure nickname, channelId, and unionId for push services
4. **Context Menu**: Easy access via right-click menu on blocks
5. **Top Bar Integration**: Quick access from the top bar with submenu
6. **Block Content Integration**: Automatically use selected block content for messages

## Installation

### From Marketplace
1. Open SiYuan Notes
2. Go to `Settings > Marketplace`
3. Search for "MeoW Push"
4. Click "Install"
5. Enable the plugin

### Manual Installation
1. Download the latest release from [GitHub Releases](https://github.com/ShiShiBits1/SiYuan-MeoW-Push/releases)
2. Extract the `package.zip` file
3. Copy the extracted folder to `your-siyuan-workspace/data/plugins/`
4. Restart SiYuan Notes
5. Enable the plugin in `Settings > Marketplace`

## Usage

### 1. Configure Settings
1. Click the MeoW Push icon in the top bar
2. Select "设置" (Settings)
3. Fill in your nickname, channelId, and unionId
4. Click "Save"

### 2. Send Push Messages
#### Method 1: From Top Bar
1. Click the MeoW Push icon in the top bar
2. Select "推送消息" (Push Message)
3. Enter the message content
4. Click "Send"

#### Method 2: From Block Menu
1. Right-click on a block
2. Select "推送消息" (Push Message) from the context menu
3. The block content will be automatically filled
4. Click "Send"

### 3. Send Broadcast Messages
#### Method 1: From Top Bar
1. Click the MeoW Push icon in the top bar
2. Select "广播消息" (Broadcast Message)
3. Enter the message content
4. Click "Send"

#### Method 2: From Block Menu
1. Right-click on a block
2. Select "广播消息" (Broadcast Message) from the context menu
3. The block content will be automatically filled
4. Click "Send"

## Configuration

The plugin requires the following configuration:

| Setting | Description | Required |
|---------|-------------|----------|
| Nickname | Your nickname for push messages | Yes |
| ChannelId | Your channel ID for broadcast | Yes |
| UnionId | Your union ID for broadcast | Yes |

## License

MIT License

## Acknowledgments

- Based on [SiYuan Plugin Template](https://github.com/siyuan-note/plugin-sample)
- Uses Vite + Vue3 for development
- MeoW API integration

## Support

For issues and feature requests, please open an [issue](https://github.com/ShiShiBits1/SiYuan-MeoW-Push/issues) on GitHub.
