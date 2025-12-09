# MeoW 推送与广播插件

[English](https://github.com/ShiShiBits1/SiYuan-MeoW-Push/blob/main/README.md)

一个为 SiYuan 笔记开发的 MeoW 推送和广播功能插件。

## 功能特性

1. **个人推送**: 发送带有自定义内容的个人推送消息
2. **广播消息**: 向指定频道发送广播消息
3. **设置功能**: 配置推送服务的昵称、channelId 和 unionId
4. **右键菜单**: 通过块右键菜单便捷访问
5. **顶部栏集成**: 从顶部栏快速访问，带有二级菜单
6. **块内容集成**: 自动使用选中块的内容作为消息

## 安装方法

### 从集市安装
1. 打开 SiYuan 笔记
2. 进入 `设置 > 集市`
3. 搜索 "MeoW 推送"
4. 点击 "安装"
5. 启用插件

### 手动安装
1. 从 [GitHub Releases](https://github.com/ShiShiBits1/SiYuan-MeoW-Push/releases) 下载最新版本
2. 解压 `package.zip` 文件
3. 将解压后的文件夹复制到 `你的思源工作空间/data/plugins/`
4. 重启 SiYuan 笔记
5. 在 `设置 > 集市` 中启用插件

## 使用说明

### 1. 配置设置
1. 点击顶部栏的 MeoW 推送图标
2. 选择 "设置"
3. 填写昵称、channelId 和 unionId
4. 点击 "保存"

### 2. 发送推送消息
#### 方法一：从顶部栏
1. 点击顶部栏的 MeoW 推送图标
2. 选择 "推送消息"
3. 输入消息内容
4. 点击 "发送"

#### 方法二：从块菜单
1. 右键点击一个块
2. 从上下文菜单中选择 "推送消息"
3. 块内容会自动填入
4. 点击 "发送"

### 3. 发送广播消息
#### 方法一：从顶部栏
1. 点击顶部栏的 MeoW 推送图标
2. 选择 "广播消息"
3. 输入消息内容
4. 点击 "发送"

#### 方法二：从块菜单
1. 右键点击一个块
2. 从上下文菜单中选择 "广播消息"
3. 块内容会自动填入
4. 点击 "发送"

## 配置说明

插件需要以下配置：

| 设置项 | 描述 | 是否必填 |
|--------|------|----------|
| 昵称 | 用于推送消息的昵称 | 是 |
| channelId | 用于广播的频道 ID | 是 |
| unionId | 用于广播的联盟 ID | 是 |

## 许可证

MIT License

## 致谢

- 基于 [SiYuan 插件模板](https://github.com/siyuan-note/plugin-sample)
- 使用 Vite + Vue3 开发
- 集成 MeoW API

## 支持

如有问题或功能需求，请在 GitHub 上提交 [issue](https://github.com/ShiShiBits1/SiYuan-MeoW-Push/issues)。
