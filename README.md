# QPrint (智印) 🖨️ ✨

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)

**QPrint (智印)** 是一款开箱即用的**纯前端批量排版与打印神器**。

专为教育工作者、行政人员及活动组织者打造。只需导入一份 Excel 名单和对应的照片，即可通过简单的拖拽排版，瞬间批量生成数百份奖状、证书、工牌或桌牌，并直接调用浏览器打印或导出。

<img width="1912" height="914" alt="image" src="https://github.com/user-attachments/assets/fe7b3db8-f3d3-43fe-8ec6-a3e87e03a4ec" />
<img width="1912" height="914" alt="image" src="https://github.com/user-attachments/assets/21b32fe1-c321-4a4d-a01b-a1d0b6eb6802" />


**🌐 [在线体验 (Live Demo) ](http://qprint.qwejay.cn/)**

---

## 🌟 核心特性 (Features)

- ⚡ **纯本地处理，极致隐私**：无需任何后端服务器，所有 Excel 数据和照片均通过 `IndexedDB` 和 `LocalStorage` 在本地浏览器内解析与渲染，**数据绝不上云，绝对安全**。
- 📊 **智能数据合并**：内置轻量级表格解析，支持 `.xlsx`, `.csv` 或**直接从微信/Excel 复制粘贴**。
- 🖼️ **照片与二维码智配**：
  - 自动根据 Excel 中的列名进行**媒体精准配对**。
  - 一键为指定变量（如证书编号）生成专属二维码。
- 🎨 **自由可视化排版**：
  - 支持多选对齐（按住 `Ctrl`）、图层层级调整、吸附居中。
  - **CDN 加速与本地双重保底**：内置的高清背景图与字体优先使用 COS 节点加速，若节点失效则自动无缝降级使用本地内置资源。
  - **支持导入本地自定义字体**（`.ttf`, `.woff` 等）。
- 💾 **工程化管理**：支持一键下载 `.json` 项目文件，随时跨设备导入继续编辑。

---

## 🚀 快速开始 (Quick Start)

本项目为纯静态前端项目，**零配置，无需构建（No Build Tools Required）**。

你可以直接访问 **[QPrint 官网](http://qprint.qwejay.cn/)** 使用，或者部署到你自己的服务器：

1. `Clone` 或 `Download` 本仓库到本地。
2. 将项目目录部署至任何静态服务器（Nginx, Vercel, GitHub Pages 等）。
3. 也可以直接双击 `index.html` 离线使用！

---

## 📖 使用指南 (User Guide)

只需简单的 4 步即可完成批量打印：

1. **① 背景选择**：在左侧边栏选择预设模板，或上传你自己的空白奖状底图。
2. **② 名单导入**：切换到“名单导入”卡片，上传包含信息的 Excel 表格，或直接粘贴数据。
3. **③ 照片导入 (可选)**：将包含照片的文件夹拖入库中即可自动配对。
4. **④ 占位符排版与打印**：
   - 使用双花括号包裹表格的列名，例如：`{{姓名}}`。
   - 点击顶部导航栏的 **“🖨️ 打印 / 导出”**，调用系统打印机批量输出！

---

## 📜 许可证 & 声明 (License)

本项目由 **[Qwejay](https://github.com/Qwejay)** 设计与开发。
[GPL-3.0 license](./LICENSE) &copy; 2026 QwejayHuang. 
