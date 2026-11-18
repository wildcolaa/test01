# Make Yourself at Home

欢迎回家。一款以智能家居协作与自由对话为核心的斜俯视叙事解谜游戏。

## 下载与运行

- [Windows 64 位游戏包](./Make-Yourself-at-Home-Windows.zip)
- [Unity 完整源码包](./Make-Yourself-at-Home-Unity-Source.zip)

下载 ZIP 后完整解压，运行 Windows 包中的 Make Yourself at Home.exe。请保留同目录的数据文件夹和 DLL。

WASD 或方向键移动，靠近设备按 E 交互。对话时可打字发送，或按住空格使用麦克风。自由生成对话与语音识别需要在设置中填写自己的 Groq API Key。

## 在 Unity 中打开

使用 Unity 6000.3.20f1 打开解压后的源码目录，再打开 Assets/ThirdDay/Scenes/ThirdDay.unity。

源码包含 Assets、Packages、ProjectSettings。API Key 与个人存档保存在本机 PlayerPrefs。包内包含家具模型细化和背景城市纸纹的最新改动。

## 验证

Windows 构建成功，0 个构建错误。带图形的独立运行程序通过 15 秒启动检查。此检查覆盖启动，不等同于对当前发行包进行完整通关测试。

文件校验见 [SHA256SUMS.txt](./SHA256SUMS.txt)。
