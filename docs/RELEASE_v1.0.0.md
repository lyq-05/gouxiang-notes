# 构想手记 v1.0.0

> 作品优先，内容分层；从本地预览走向正式上线。

**发布类型**：首个公开作品版本  
**发布日期**：2026-10-29  
**上一版本**：无已发布 GitHub 版本  
**运行方式**：现代桌面或移动浏览器；WebGL 效果依赖设备支持

## 在线体验

| 平台 | 入口 | 说明 |
| --- | --- | --- |
| Web | https://lyqdev.cn/ | 无安装包，直接访问 |

## 本次发布

- 作品首页、四个应用详情与自动环绕画廊。
- ERP 业务案例、开发手记和独立日常页面。
- 可展开联系卡包、金属反射、鼠标光迹与圆形转场。
- 本地内容管理台支持草稿、预览、发布和备份。
- HTTPS 静态部署、备案链接与前一版本保留。
- 公网音乐仅展示歌单，没有音频附件。

## 界面

![构想手记首页](https://raw.githubusercontent.com/lyq-05/gouxiang-notes/v1.0.0/docs/screenshots/01-home.png)

![联系卡包](https://raw.githubusercontent.com/lyq-05/gouxiang-notes/v1.0.0/docs/screenshots/03-contact.png)

## 验证与已知限制

上线时完成 15 项已有 CMS / 业务测试及主要页面访问检查，页面资源引用已核对。后台和 ERP 操作接口仅本地使用；SQLite 测试不证明 PostgreSQL 并发行为。不同设备的 WebGL 性能有差异，侧边浏览器圆形转场偶发闪烁仍待优化。

## 更新与备份

这是网站版本记录，没有客户端升级包。后续本地修改确认后再正式发布，不会因 GitHub 提交自动更新网站。源码备份不包含账号凭据、数据库、音乐音源及未发布草稿。

## 相关链接

[网站](https://lyqdev.cn/) · [项目介绍](https://github.com/lyq-05/gouxiang-notes) · [更新记录](https://github.com/lyq-05/gouxiang-notes/blob/main/CHANGELOG.md)
