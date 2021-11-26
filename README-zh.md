# WindowsGSM.Satisfactory
支持 **幸福工厂专用服务器** 的 WindowsGSM 插件!

- [English](README.md)

# 需求
WindowsGSM >= 1.21.0

# 游戏

- 游戏
https://store.steampowered.com/app/526870/Satisfactory/

- 专用服务器
https://store.steampowered.com/app/1690800/Satisfactory_Survival/

# 安装

1. 下载 latest release
2. 将 **WindowsGSM.Satisfactory.cs** 文件夹复制到 `plugins` 文件夹中
3. 点击 **[RELOAD PLUGINS]** 按钮重新加载插件或重启 WindowsGSM

# 使用

## 创建服务器

1. 选择菜单 **[Servers - Install GameServer]**
2. 在 **Game Server** 列表中选择 **Satisfactory Dedicated server [Satisfactory.cs]**
3. 填写服务器名称
4. 点击 **[INSTALL]**，并等待服务器安装完毕

## 配置服务器

1. 在服务器列表中选择已经创建的服务器
2. 点击左下区域的 **[EDIT CONFIG]** 按钮
3. 在右侧区域修改配置。支持的配置参数如下：

    | 参数 | 说明 |
    | ---- | ---- |
    | Server Port | 游戏服务器端口，默认为 `7777` |
    | Server Query Port | 游戏服务器查询端口，默认为 `15777`。游戏中添加服务器时需要填写此端口 |
    | Server Max Players | 最大玩家数量，默认为 `4`。_当前服务器可能不支持_ |
    | Server Start Param | 服务器启动参数，一般不需要修改 |

4. 服务器选项

    | 选项 | 建议 |  说明 |
    | ---- | ---- | ---- |
    | Embed Console | 开 | 内嵌控制台到 WindowsGSM 主窗口 |
    | Update on Start | 开 | 启动时更新服务器。先尝试更新服务器，再启动服务器 |
    | Backup on Start | 关 | 启动时备份服务器。注意，备份的是整个服务器端，数据量可能比较大 |
    | Auto Start | 开 | 自动启动服务器。当 WindowsGSM 启动时，会自动启动此游戏服务器 |
    | Auto Restart | 开 | 自动重启服务器。当游戏服务器崩溃时，会自动重启此游戏服务器 |
    | Auto Update | 开 | 自动更新服务器。开启游戏服务器后，每隔30分钟会检测一次是否存在更新，如果存在更新，则先停止游戏服务器，再更新服务器，更新完毕后自动启动服务器 |
    | SET AFFINITY | - | 设置相关性。可指定服务器使用哪些CPU核心，以调整游戏服务器对主机性能的影响 |
    | Restart Crontab | - | 设置重启计划任务。可设置每天、每周、每月的某时间重启服务器 |


## 其他

1. 如有需要，可在 WindowsGSM 设置中，将之设置为开机启动： **Start WindowsGSM on Login**
2. 另外建议开启崩溃后自动重启 WindowsGSM ： **Auto Restart WindowsGSM on Crash**
3. 如有兴趣，可以试试 **Discord Bot** 功能，可以在 Discord 中，通过主动发送指令，来查询、控制游戏服务器的运行、更新等


# 服务器设置

1. 打开游戏并连接服务器
2. 第一次连接时初始化参数
3. 在游戏中管理服务器

# 许可协议

本软件遵循 MIT License 许可协议，详情请参考 [LICENSE.md](LICENSE.md)。

