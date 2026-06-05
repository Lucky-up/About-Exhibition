# About-Exhibition
> 预览地址：https://lucky-up.github.io/About-Exhibition/

## 项目介绍
纯静态展示页面，原生 HTML/CSS 开发，依托 GitHub Pages 部署，用于展示「2026第一届中国·北京-东南亚芳香博览会」相关介绍。

## 目录结构
```
About-Exhibition/
├── index.html                # 网站首页入口
├── css/                      # 全局样式目录
│   ├── common.css            # 公共通用样式
│   ├── home.css              # 首页专属样式
│   ├── china.css             # 中国展区页面样式
│   ├── singapore.css         # 新加坡展区页面样式
│   ├── data.css              # 产业数据页样式
│   └── new.css               # 新闻页样式
├── html/                     # 各栏目主页面
│   ├── china.html            # 中国展区介绍页
│   ├── singapore.html        # 新加坡展区介绍页
│   ├── data.html             # 行业数据统计页
│   ├── new.html              # 新闻资讯列表页
│   └── article/             # 新闻详情子页面目录
│       ├── 01.html
│       ├── 02.html
│       ├── 03.html
│       ├── 04.html
│       ├── 05.html
│       └── 06.html
└── images/                   # 全站图片资源（海报、配图、素材）
```

## 本地启动
1. 拉取代码
```bash
git clone https://github.com/lucky-up/About-Exhibition.git
cd About-Exhibition
```
2. 直接双击 `index.html` 在浏览器打开即可。

## 部署方式
1. 代码提交推送至仓库
2. 仓库 `Settings → Pages`，选择主干分支+根目录部署
3. 自动生成 Pages 访问链接
