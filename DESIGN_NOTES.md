# MyFish 水色页面设计

这份项目副本以柔和水色为主题，使用浅水蓝、薄荷绿、深青色和留白。原压缩包未修改。

## 页面

- **首页**：欢迎卡片、模块数量与版本信息、前往模块和动态的入口。
- **模块**：四张未来功能的概念卡片，明确标注“尚未开放”。
- **动态**：以卡片形式展示项目现有的 v0.1.1 与 v0.1 记录。
- **我的**：品牌介绍、工作区提示和覆盖配置文件的提醒。

四个页面均支持纵向滚动。底部导航和首页的两个入口可以切换页面。页面中的模块概念仍是静态预览，没有新增模块业务功能。

## 主要文件

- 页面布局：`app/src/main/res/layout/fragment_*.xml`
- 颜色与文字样式：`app/src/main/res/values/colors.xml`、`styles.xml`
- 卡片背景与图标：`app/src/main/res/drawable/`
- 底部导航：`app/src/main/res/layout/activity_main.xml`、`menu/bottom_nav_menu.xml`

为了让现有 Gradle 配置一致，根目录 `build.gradle` 中与 `settings.gradle` 冲突的项目级仓库声明已移除。未改动原有存储权限和文件处理逻辑。
