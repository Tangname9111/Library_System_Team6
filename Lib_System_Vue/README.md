# BookManagerVue

BookManagerVue 是一个基于 Vue.js 的图书管理系统，旨在帮助用户轻松管理和跟踪他们的图书收藏。

## 目录

- [功能特性](#功能特性)
- [安装](#安装)
- [使用](#使用)
- [项目结构](#项目结构)

## 功能特性

- 添加新书
- 编辑书籍信息
- 删除书籍
- 查看书籍列表
- 搜索书籍
- 借阅书籍
- 用户管理

## 安装

1. 克隆仓库到本地：

   ```bash
   git clone https://github.com/Tangname9111/Library_System_Team6.git
   ```

2. 进入项目目录：

   ```bash
   cd Library_System_Team6
   ```

3. 安装依赖：

   ```bash
   npm install
   ```

## 使用

1. 启动开发服务器：

   ```bash
   npm run dev
   ```

2. 打开浏览器并访问 `http://localhost:8080`。

## 项目结构
BookManagerVue/
├── public/ # 静态资源
├── src/ # 源代码
│ ├── api/               # API 请求
│ │   ├── article.js     # 文章相关 API
│ │   ├── bookinfo.js    # 图书信息相关 API
│ │   ├── booktype.js    # 图书类型相关 API
│ │   ├── borrow.js      # 借阅相关 API
│ │   └── user.js        # 用户相关 API
│ ├── components/        # 可复用组件
│ │   ├── Breadcrumb/    # 面包屑组件
│ │   ├── Hamburger/     # 汉堡菜单组件
│ │   ├── Pagination/     # 分页组件
│ │   └── SvgIcon/       # SVG 图标组件
│ ├── views/             # 页面视图
│ │   ├── BookList.vue   # 图书列表页面
│ │   ├── AddBook.vue    # 添加图书页面
│ │   ├── EditBook.vue   # 编辑图书页面
│ │   ├── BorrowList.vue  # 借阅列表页面
│ │   └── UserManagement.vue # 用户管理页面
│ ├── store/             # Vuex 状态管理
│ ├── utils/             # 工具函数
│ ├── App.vue            # 根组件
│ └── main.js            # 入口文件
├── .gitignore # Git 忽略文件
├── package.json # 项目配置文件
└── README.md # 项目说明文档
