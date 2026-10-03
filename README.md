# 频率密室兼容入口

本项目保留旧世界页面的访问路径，介绍并进入 `world_flutter` 的频率密室。游戏中心是唯一发现、分类、继续和结果入口；本页没有第二份游戏目录或独立世界玩法。

`public/index.html` 是本轮可直接静态服务的实际入口，使用 Frequency Terminal 的黑色、酸黄与琥珀主题。点击“进入频率密室”前往 `/XJY.GAME.COMP.world_flutter/`，点击“返回游戏中心”前往 `/XJY.GAME.COMP.gameCenter/`。`public/assets/frequency-courtyard.webp` 共用实际世界场景。全部页面相对资源可在 `/XJY.GAME.COMP.world_vue/` 子路径加载。

`src/entry-manifest.json` 记录静态运行目录与 canonical 地址。原根 App.vue/main.js、pages、static 和 UniApp 配置保持原状，未未经协调迁移或删除。部署本轮兼容页时以 public 的内容为输出；不需要为了纯静态页面新增 npm 或 Flutter 依赖。

桌面和手机真实浏览器已完成本地页面渲染及进入频率密室、返回游戏中心的闭环验证，对应候选构建与本地 docs 已核对。发布使用 master 分支的 /docs，线上地址为 https://shadowplusing.cn/XJY.GAME.COMP.world_vue/；发布完成以 GitHub Pages 对应提交的构建结果为准。过程、原图和截图在仓库外，只有运行必要资源进入源目录。
