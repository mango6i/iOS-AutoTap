# iOS AutoTap

**适用于 iOS / iPadOS 15.0+ 的跨应用自动点击与操作录制工具。**

AutoTap 提供单点、多点、点击录制和手势录制四种模式，支持真实触摸模拟、跨应用悬浮控制、独立脚本管理，以及点击和滑动操作回放。界面适配 iPhone、iPad、浅色模式和深色模式。

> [!IMPORTANT]
> **AutoTap 必须使用 TrollStore（巨魔商店）安装。**
> 跨进程悬浮窗和真实触摸模拟依赖 TrollStore 提供的系统权限。普通自签、企业签名及其他安装方式不受支持，核心功能可能无法运行。

[下载最新版本](https://github.com/mango6i/iOS-AutoTap/releases/latest) · [直接下载 AutoTap v1.0.3](https://github.com/mango6i/iOS-AutoTap/releases/download/v1.0.3/AutoTap_v1.0.3.ipa)

## 工作模式

| 模式 | 功能 |
| --- | --- |
| 单点模式 | 在一个指定位置循环点击，可独立设置间隔、按压时长和执行次数。 |
| 多点模式 | 添加多个数字目标，按照 `1 → 2 → 3…` 的编号顺序循环执行。 |
| 点击录制 | 连续记录手动点击位置，保存为可重复运行的独立脚本。 |
| 手势录制 | 同时记录点击与滑动轨迹，保存手势持续时间并进行回放。 |

## 主要功能

- 跨应用悬浮控制条，支持开始、暂停、继续和关闭。
- 数字目标可独立拖动和设置，运行时显示当前执行位置。
- 每个目标可分别设置点击间隔、毫秒/秒/分钟单位、按压时长和执行次数。
- 支持无限循环、指定循环次数、启动倒计时以及每轮完成后的等待时间。
- 四种模式的运行状态、配置和脚本相互独立。
- 支持脚本导入、导出、重命名和删除。
- 点击脚本与手势脚本分别保存和管理。
- 脚本及通用设置持久化保存在应用数据目录。
- 自动跟随系统浅色或深色外观。
- 支持运行时屏幕常亮、锁屏自动暂停及解锁后恢复待命状态。
- 支持 iPhone 与 iPad 自适应界面。
- 支持从应用内检查 GitHub Releases 新版本。

## 系统与安装要求

- **系统版本：** iOS / iPadOS 15.0 或更高版本。
- **安装工具：** TrollStore（巨魔商店），必须使用。
- **设备要求：** 能够正常安装并运行 TrollStore 的 iPhone 或 iPad。
- **不支持：** 普通自签、企业签名以及无法提供所需系统权限的其他安装方式。

## 安装与使用

1. 从 [Releases](https://github.com/mango6i/iOS-AutoTap/releases/latest) 下载最新的 `AutoTap_vX.Y.Z.ipa`。
2. 使用 **TrollStore（巨魔商店）** 安装 IPA。
3. 打开 AutoTap，在首页选择需要的模式。
4. 新建配置或载入已保存脚本，再开启对应模式。
5. 将悬浮目标拖到需要操作的位置。
6. 点击悬浮控制条的开始按钮运行；运行中可暂停、继续或关闭。

## 脚本导入与导出

导出的脚本默认保存到“文件”应用中的“我的 iPhone/AutoTap”目录。导入时会优先打开该目录，也可以从其他文件夹选择兼容脚本。

## 当前版本

### AutoTap v1.0.3

- [查看版本说明](https://github.com/mango6i/iOS-AutoTap/releases/tag/v1.0.3)
- [下载 AutoTap_v1.0.3.ipa](https://github.com/mango6i/iOS-AutoTap/releases/download/v1.0.3/AutoTap_v1.0.3.ipa)
- SHA-256：`B968A94947755078CC41F70A62E670E05EA8E9034FCBDDE8D2E0E6E23258F7DC`

## 发布内容说明

本仓库只发布可安装的成品 IPA，不提供 AutoTap 应用源码。GitHub 自动显示的 `Source code (zip)` 和 `Source code (tar.gz)` 仅包含本仓库的说明文件，并不是 AutoTap 源码。安装时请下载对应版本的 `.ipa` 文件。

## 免责声明

本工具仅用于个人自动化、辅助操作和测试。请遵守所使用应用或服务的规则；因不当使用造成的账号、数据或设备风险由使用者自行承担。
