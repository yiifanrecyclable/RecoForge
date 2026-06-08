# RecoForge

> 一款面向 3D 打印产品创作者的综合管理工具。
> A management tool for 3D printing product creators.

![Version](https://img.shields.io/badge/version-0.2.2-blue)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-lightgrey)

---

## ✨ 功能 / Features

**产品管理 / Product Management**
- 产品分组与版本迭代管理
- Organize products into groups with version tracking

**成本核算 / Cost Calculation**
- 实时计算打印件、定制件、直采件、辅料的综合成本
- Real-time cost calculation across print parts, custom parts, purchase parts, and other expenses

**零件管理 / Part Management**
- 打印件：自动计算材料费 + 电费，支持多辅材
- Print parts: automatic material + electricity cost, multi-material support
- 定制件：外协加工件管理
- Custom parts: outsourced processing parts
- 直采件：从标件库选取，自动同步价格
- Purchase parts: select from standard parts library with live price sync
- 辅料：其他零散成本项
- Other expenses: miscellaneous cost items

**数据管理 / Data Management**
- 耗材库、标件库统一管理
- Material library and standard parts library
- 图片上传与裁剪（版本封面、零件缩略图）
- Image upload with cropping (version covers, part thumbnails)
- Markdown 格式产品报告导出
- Markdown product report export

**工作区 / Workspace**
- 所有数据本地存储（SQLite），安全可靠
- All data stored locally (SQLite), safe and reliable
- 支持自定义工作区路径
- Customizable workspace path

---

## 📦 下载安装 / Download

前往 [Releases](https://github.com/YOUR_USERNAME/RecoForge/releases) 页面下载对应平台的安装包。
Download the installer for your platform from the [Releases](https://github.com/YOUR_USERNAME/RecoForge/releases) page.

| 平台 / Platform | 文件 / File |
|-----------------|-------------|
| Windows | `.exe` 安装包 / installer |
| macOS | `.dmg` 安装包 / installer |

---

## 🛠 技术栈 / Tech Stack

| 层级 / Layer | 技术 / Technology |
|-------------|-------------------|
| 框架 / Framework | [Tauri v2](https://tauri.app/) |
| 前端 / Frontend | React 19 + TypeScript |
| 状态管理 / State | Zustand |
| UI 组件 / UI | shadcn/ui + TailwindCSS v4 |
| 数据库 / Database | SQLite (WAL mode) |
| 图标 / Icons | [Lucide](https://lucide.dev/) |

---

## 📸 截图 / Screenshots

_待补充 / Coming soon_

---

## 📝 更新日志 / Changelog

### v0.2.2

- 产品自定义分组（创建、重命名、删除、折叠、移入/移出）
- Custom product groups (create, rename, delete, collapse, move products in/out)
- 导航栏图标更新 / Updated navigation icons
- 设置页二维码与联系作者按钮 / QR codes and contact button in settings
- 多项交互优化与 bug 修复 / Multiple UX improvements and bug fixes

完整日志见 [CHANGELOG.md](./CHANGELOG.md)。
Full changelog: [CHANGELOG.md](./CHANGELOG.md).

---

## 🤝 反馈与联系 / Contact

如需联系作者，可在软件设置页扫码添加微信。
Scan the WeChat QR code in the app settings to contact the author.

---

_Made with ❤️ for the 3D printing community_
