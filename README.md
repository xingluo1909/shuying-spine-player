<div align="center">
  <br />
  <h1>数影 Spine Player</h1>
  <p align="center">
  🌐 <a href="README.md">中文</a> · <a href="README.en.md">English</a> · <a href="README.jp.md">日本語</a>
</p>
  <p>
    <strong>跨平台非官方 2D 骨骼动画播放器，不止于Spine</strong>
    <br />
    多版本播放 · 格式转换 · 骨架合并 · Live2D · 3D 预览（test） · AI超分
  </p>
  <p>
    <a href="#"><img src="https://img.shields.io/badge/版本-1.627.0-7c6af7?style=for-the-badge&labelColor=1a1a2e" alt="版本"></a>
    <a href="#"><img src="https://img.shields.io/badge/Spine-2.1%20%7C%203.x%20%7C%204.x-00d4aa?style=for-the-badge&labelColor=1a1a2e" alt="Spine支持"></a>
    <a href="#"><img src="https://img.shields.io/badge/Live2D-Cubism%202%20%7C%204-ff6b9d?style=for-the-badge&labelColor=1a1a2e" alt="Live2D"></a>
    <a href="#"><img src="https://img.shields.io/badge/多语言-中%20%7C%20EN%20%7C%20日-4fc3f7?style=for-the-badge&labelColor=1a1a2e" alt="多语言"></a>
    <br />
    <a href="#"><img src="https://img.shields.io/badge/Tauri-ffc131?style=for-the-badge&labelColor=1a1a2e&logo=tauri" alt="Tauri"></a>
    <a href="#"><img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&labelColor=1a1a2e&logo=react" alt="React"></a>
    <a href="#"><img src="https://img.shields.io/badge/Rust-ed672f?style=for-the-badge&labelColor=1a1a2e&logo=rust" alt="Rust"></a>
    <a href="#"><img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&labelColor=1a1a2e&logo=three.js" alt="Three.js"></a>
    <a href="#"><img src="https://img.shields.io/badge/Pixi.js-B537B4?style=for-the-badge&labelColor=1a1a2e&logo=pixi.js" alt="Pixi.js"></a>
     <a href="#"><img src="https://img.shields.io/github/downloads/xingluo1909/shuying-spine-player/total?style=for-the-badge&labelColor=1a1a2e&color=brightgreen" alt="下载量"></a>

  </p>
  <br />
</div>

---

## 📖 简介
  这是集**播放、格式转换、合并、超分**等等功能于一体的Windows**非官方**骨骼动画播放器项目，目前已实现从 **Spine 2.1** 到 **3.x** 到 **4.x** 的多版本兼容播放与指定格式转换，同时支持 Live2D Cubism 模型导入。

<p align="center">
  <img src="IMG/zhi-h.png" alt="Screenshot 1" width="800" />
</p>
  
## ✨ 功能特性
### 🎬 播放器核心
| 功能 | 说明 |
|------|------|
| **Spine 多版本支持** | 2.1 / 3.x / 4.x |
| **Live2D 多版本支持** | Cubism 2 / 4 |
| **Spine 双引擎渲染** | Enhanced（统一转换型） / Native（双播放器核心兼容型）|
| **多图层叠加** | 多个 Spine/Live2D 文件同屏播放，独立缩放及拖拽排序 |
| **动画控制** | 播放/暂停/停止，帧精确跳转，循环模式切换 |
| **皮肤/部件切换** | 实时切换角色皮肤、显示/隐藏部件 |
| **导出模块** | 支持PNG单帧导出，多种分辨率预设，AI 超分增强导出 |
| **懒加载导入** | 上千素材导入毫无压力 |
---
## 🛠️ 技术栈
| 层面 | 技术 |
|------|------|
| **桌面框架** | [Tauri 2](https://v2.tauri.app/)（Rust + WebView2） |
| **前端框架** | [React 19](https://react.dev/) + TypeScript |
| **后端语言** | Rust |
---
## 🗺️ 更新日志

# D-04(进度预览占位·win)
1.着重优化导出功能，追求最大化清晰度，同时开放逐个导出选项及文件名特殊hash计算避免重名问题

2.修复了一些spine及l2d的播放bug

3.仿终端tui的主题——琥珀上线

4.优化设置选项配置，新增骨骼显示辅助分析

5.移除一些冗余的工具组件，包体更轻盈。

6.优化播放器页的使用体验，新增多种功能。

# D-03
1.全新亮色主题上线，重构界面UI布局。
<p align="center">
  <img src="IMG/zhi-q.png" alt="Screenshot 1" width="800" />
</p>
2.安全性增强，修复了一些播放和格式上的bug

3.更流畅的播放——全新懒加载机制上线

4.新增分析模式机制，素材分类更加便捷。

# D-02 （Win）
1.多语言支持，支持中/英/日三语(机翻)，切换即时生效。

2.liv2d支持，并且特别优化播放器相关组件，实现spine+l2d同屏播放。呈现效果如下图所示：

<p align="center">
  <img src="IMG/L2D+.png" alt="Screenshot 1" width="800" />
</p>

3.FBX支持，呈现效果如下图所示：
<p align="center">
  <img src="IMG/FBX-FGO.png" alt="Screenshot 1" width="800" />
</p>

4.导出功能支持。

5.修复一些l2d&spine的播放bug及更多版本支持。

# D-01 （Mac&Win）
spine版本支持，合并模块仅限定于3.8，并且同源关系素材。
| 源 ↓ \ 目标 → | **3.8** | **4.0** | **4.1** | **4.2** |
|:-------------:|:-------:|:-------:|:-------:|:-------:|
| **2.1** | ✅ | ✅ | ✅ | ✅ |
| **3.6** | ✅ | ✅ | ✅ | ✅ |
| **3.7** | ✅ | ✅ | ✅ | ✅ |
| **3.8** | ✅ | ✅ | ✅ | ✅ |
| **4.0** | ✅ | ✅ | ✅ | ✅ |
| **4.1** | ✅ | ✅ | ✅ | ✅ |
| **4.2** | ✅ | ✅ | ✅ | ✅ |




---
## 🔄 后续计划 (尚未发布)
  目前尚在进行测试的模块:
 - [ ]  1.导出模块更多功能测试
- [ ]   2.桌宠模块测试
- [ ]   3.多主题功能测试。✅️，开放剩余主题❌️
- [ ]   4.cli功能测试
- [ ]   5.MMD播放功能测试✅️
- [ ]   6.实验性fbx转spine ✅️❌️
- [ ]   7.开放json,skel自由转换✅️
- [ ]   8.GLB支持✅️
- [ ]   9.PSKX支持✅️
---
> 如果遇到无法读取、错误、失败等案例，欢迎提出 Issue（最好附带文件），来个测试反馈吧，自己找bug是真的慢:(  
> 项目地址：https://github.com/xingluo1909/shuying-spine-player
> 本仓库为发布页，免费提供更新支持。
> 感谢曾经在论坛中帮助过我的人们:)
---
最后以个人喜欢的动画片角色演示收尾（素材仅作播放器功能演示，无任何商业用途，如侵请联系删除，本仓库不包含任何提取工具与方法）
<p align="center">
  <img src="IMG/ta.png" alt="Screenshot 1" width="800" />
</p>
希望这个软件能像它们一样，陪伴你我之后的成长旅程(=｀ω´=)
