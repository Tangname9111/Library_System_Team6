# BookManagerVue

BookManagerVue 是一个基于 Vue.js 的图书管理系统，旨在帮助用户轻松管理和跟踪他们的图书收藏。

## 目录

- [项目简介](#项目简介)
- [功能特性](#功能特性)
- [安装](#安装)
- [使用](#使用)
- [项目结构](#项目结构)
- [贡献](#贡献)
- [许可证](#许可证)

## 项目简介

BookManagerVue 是一个开源项目，提供了一个简单直观的界面来管理图书信息。用户可以添加、编辑、删除和查看图书详情。

## 功能特性

- 添加新书
- 编辑书籍信息
- 删除书籍
- 查看书籍列表
- 搜索书籍

## 安装

1. 克隆仓库到本地：

   ```bash
   git clone https://github.com/yourusername/BookManagerVue.git
   ```

2. 进入项目目录：

   ```bash
   cd BookManagerVue
   ```

3. 安装依赖：

   ```bash
   npm install
   ```

## 使用

1. 启动开发服务器：

   ```bash
   npm run serve
   ```

2. 打开浏览器并访问 `http://localhost:8080`。

## 项目结构
BookManagerVue/
├── public/ # 静态资源
├── src/ # 源代码
│ ├── assets/ # 图片、样式等资源
│ ├── components/ # Vue 组件
│ ├── views/ # 页面视图
│ ├── store/ # Vuex 状态管理
│ ├── utils/ # 工具函数
│ ├── App.vue # 根组件
│ └── main.js # 入口文件
├── .gitignore # Git 忽略文件
├── package.json # 项目配置文件
└── README.md # 项目说明文档

src/
├── api/               # API 请求
│   ├── article.js
│   ├── bookinfo.js
│   ├── booktype.js
│   ├── borrow.js
│   ├── user.js
├── components/        # 可复用组件
│   ├── Breadcrumb/
│   ├── Hamburger/
│   ├── Pagination/
│   ├── SvgIcon/
├── views/             # 页面视图
│   ├── BookList.vue
│   ├── AddBook.vue
│   ├── EditBook.vue
│   ├── BorrowList.vue
│   ├── UserManagement.vue
├── App.vue            # 根组件
└── main.js            # 入口文件

## 贡献

欢迎任何形式的贡献！请阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 了解更多信息。

## 许可证

本项目基于 MIT 许可证开源。详情请参阅 [LICENSE](LICENSE) 文件。