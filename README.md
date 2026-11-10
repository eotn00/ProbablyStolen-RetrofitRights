# 改造权 / Retrofit Rights

《深空当铺 / Probably Stolen》的容器材料扩容与仓储显示调整 Mod，可独立使用，无需拾荒拓展作为前置。

本仓库用于**正式版下载和问题反馈**，不提供源码。

- **[下载最新正式版](https://github.com/eotn00/ProbablyStolen-RetrofitRights/releases/latest)**：在 Assets 中下载 `RetrofitRights-版本号.zip`，不要下载 GitHub 自动生成的 Source code 压缩包。
- **[反馈问题](https://github.com/eotn00/ProbablyStolen-RetrofitRights/issues/new/choose)**：请说明实际遇到的问题，并上传复现后的 `Player.log`。
- [Steam 创意工坊](https://steamcommunity.com/sharedfiles/filedetails/?id=3833929097)
- [搭配使用：拾荒拓展](https://github.com/eotn00/ProbablyStolen-ScavengerSkills)

## 安装与更新（Windows）

1. 退出游戏，先备份存档。
2. 下载 Releases 中的 Mod ZIP，将其中的 `RetrofitRights` 文件夹解压到游戏安装目录的 `Mods` 下。
3. 确认结构为 `Mods/RetrofitRights/manifest.xml` 和 `Mods/RetrofitRights/RetrofitRights.dll`，不要额外套一层同名目录。
4. 在游戏模组菜单启用，按游戏提示重启。游戏内按 **F8** 打开菜单；详细玩法见包内 `README.txt`。

Steam 可通过“管理 → 浏览本地文件”找到游戏安装目录。也可直接订阅工坊安装。

**不要同时保留工坊版与同 ID 的本地版或测试版。** 切换来源前先备份存档，退出游戏后处理重复副本。更新本地版时替换 Mod 文件，不删除个人存档。

## 基本操作与存档提醒

- 先购买改造权等级，再按住 Shift 将材料拖到容器图标，逐格改造；直接拖进格子是存放物品。垃圾场默认允许不按 Shift 提交，可在配置中关闭。
- 显示调整不改变实际容量；显示模块可单独使用，扩容模块依赖显示模块。
- **不要在存档仍依赖扩容格子时直接卸载 Mod。** 关闭功能与卸载不是同一回事；已有容量、材料进度及小窝迁移注意事项见包内说明。
- 发明家背包的材料扩容仍由拾荒拓展负责。第三方特殊容器不保证全部兼容。

## 如何反馈问题

先搜索已有 Issues，再使用问题反馈表单，提供：

- 游戏版本、Mod 版本、安装来源，以及其他已启用的 Mod；
- 实际遇到的问题、预期表现和复现步骤；涉及容器时请注明容器种类、分页及相关设置；
- **本次发生问题后的完整 `Player.log` 附件**；截图、录像可辅助说明，但不能代替日志。

### 获取 Player.log（Windows）

1. 运行游戏并复现问题。
2. 按 `Win + R`，输入以下路径并回车：

   ```text
   %USERPROFILE%\AppData\LocalLow\Questing Goose Studio\Probably Stolen
   ```

3. 及时复制备份 `Player.log`，然后把它拖入反馈表单的日志输入框。**不要再次启动游戏后才取日志**，旧日志可能被覆盖；必要时同时提供 `Player-prev.log` 并注明。
4. 若 GitHub 不接受 `.log`，将日志压缩为 ZIP，或复制一份改为 `.txt` 后上传。不要只粘贴几行报错或上传日志截图。

Issues 和附件是公开的。上传前检查是否含用户名、个人路径等隐私；必要时仅遮盖敏感信息，保留相关错误及上下文。不要上传密码、令牌或无关个人文件。找不到日志时，请在日志栏说明已检查的路径和无法提供的原因。

反馈时不必先确定是哪个 Mod 的问题，请如实描述现象和启用列表。
