# Lighthouse-Run-WebGL
## 在 Unity 上制作的简单3D小游戏，】利用 WebGL 进行网页编译
- WebGL是什么：WebGL是浏览器里的 2D/3D 图形接口，让页面用显卡加速绘制，无需安装插件。
- Unity 的 WebGL 平台导出会把C# 代码编译成 WebAssembly，在浏览器利用 WebGL 做渲染。
- 这是目前把 Unity 游戏无插件地跑在网页上的主流方式。
## 基本操作步骤
- 在 Unity 中切换为 WebGL 目标平台（ Building Settings => Switch Platform ）
- 在目标平台（ WebGL ）的 Player Settings 中调节相关配置
- 执行：File > Build Settings > WebGL > Build（或 Build And Run）
- 产物为一个文件夹，通常包含：index.html (网页入口文件)、xxx.loader.js（加载器）、xxx.framework.js（或打包后的 js）、xxx.wasm（WebAssembly）、xxx.data（资源数据）
- 在 Github 新建仓库同步文件，使用 Pages 发布即可。
