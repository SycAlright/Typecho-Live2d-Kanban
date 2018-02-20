# Typecho-Live2d-Kanban

| 插件名称 | 适用程序 | 版本号 | 更新日期 |
| ------- | -------- | ----- | -------- |
|看板娘（Live2d）插件| Typecho 1.1 | 1.0.1 | 2018-02-20 |

#### GNU General Public License v3.0

#### 插件介绍
加载插件后，页面右（左）下角出现看板娘，目前使用B站Live看板娘（2233娘）。
刷新页面会自动换衣、将鼠标移动到看板娘头上点击左键并移动会盯着鼠标。

#### 注意事项
 - 如开启插件后没有出现看板娘，请检查使用的主题模板的页首钩子`<?php $this->header(); ?>`和页脚钩子`<?php $this->footer(); ?>`是否存在。
 - 首次加载页面、网络慢、机器配置低、浏览器版本不支持等情况，可能导致看板娘无法正常加载、渲染。
 - 渲染会延长页面加载时间。

#### 详细介绍
[《看板娘（Live2d）插件》- SycBlog][2]

#### 相关致谢
 - 2233娘版权归Bilibili所有，与此项目无关，侵删致谢。
 - Live2d WebGL: [Live2D/CubismJsComponents][1]


  [1]: https://github.com/Live2D/CubismJsComponents
  [2]: https://www.mfeng.cc/archives/2018/02/20/Typecho_Live2d_Kanban.html
