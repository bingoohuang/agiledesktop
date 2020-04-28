# 在Finder的右键菜单中添加「Open in VSCode」

[原文](https://liam.page/2020/04/22/Open-in-VSCode-on-macOS)

操作步骤如下：

1. 打开 Automator.app（自动操作）, 选择 Quick Action（快速操作）
2. 配置工作流
    - Workflow recieves current（工作流接受当前），选择 files or folders（文件或文件夹）
    - in（位于），选择 Finder（访达)
3. 新增一个 Open Finder Items（打开访达项目）的操作，拖动到右边
    - open with（打开方式），选择 Visual Studio Code.app
    - 保存为 `Open in VSCode`

此时，在 Finder 中选中任意目录，而后右键 -> Quick Actions（快速操作）-> Open in VSCode 即可用 VSCode 打开选中的目录。
