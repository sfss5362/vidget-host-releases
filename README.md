# VidGet Pro 桌面客户端

[VidGet Pro Chrome 扩展](https://chromewebstore.google.com/) 的配套桌面客户端. 扩展嗅探到网页视频后, 把下载任务通过 Chrome Native Messaging 转给本客户端处理.

## 下载安装

请到 [Releases 页](https://github.com/sfss5362/vidget-host-releases/releases/latest) 下载最新版本.

| 平台 | 文件 |
|---|---|
| macOS (Apple Silicon) | `vidget-host_x.x.x_aarch64.dmg` |
| Windows x64 | `vidget-host_x.x.x_x64-setup.exe` |

## macOS 安装步骤

1. 下载 `.dmg` 文件
2. 双击 dmg, 把 "嗅嗅 VidGet Pro" 拖到 Applications 文件夹
3. 第一次启动 macOS 会拦截 (因为没 Apple 公证), 弹窗点 "好" 关闭
4. 打开**系统设置 → 隐私与安全性**, 滚到底部找到 "嗅嗅 VidGet Pro 已被阻止"
5. 点 **"仍要打开"**, 系统二次确认时再点 "打开"
6. 之后回到 Chrome 扩展, 任意视频页点下载即可

> 一次性操作, 系统会缓存信任状态, 后续启动不再拦截.

## Windows 安装步骤

1. 下载 `.exe` 安装程序
2. 双击运行
3. SmartScreen 可能提示 "未识别的发布者", 点 "更多信息" → "仍要运行"
4. 按引导完成安装
5. 之后回到 Chrome 扩展, 任意视频页点下载即可

## 卸载

- **macOS**: 直接把 `嗅嗅 VidGet Pro.app` 拖到废纸篓
- **Windows**: 控制面板 → 程序与功能 → "嗅嗅 VidGet Pro" → 卸载

## 隐私

[完整隐私政策](https://chrome-plugin-iyf-bilibili-down.netlify.app/privacy.html) — 零数据收集, 全本地处理, 不向任何远程服务器发送数据.

## 反馈

通过 Chrome Web Store 商店页的 "开发者联系方式" 反馈问题.
