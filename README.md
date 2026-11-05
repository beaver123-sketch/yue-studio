# Yue Studio

个人作品展示与工具空间（V1 视觉预览）。

## 在线访问

GitHub Pages（首次需在 **Settings → Pages → Build and deployment → Source** 选择 **GitHub Actions**）：

https://beaver123-sketch.github.io/yue-studio/

## 当前范围

- **Home**：极简品牌首页
- **Portfolio**：作品列表、分类筛选及详情示例
- **Tools**：工具入口及说明示例
- **About**：个人简介
- **Workspace**：仅为私人空间占位页，不展示真实资料

**重要：当前公开站点为视觉 V1，内容是安全示例；并未迁移 Career 全量数据、OKR 或私人文件。**

## 持续部署

- 仅 `site/` 下的静态网页文件会被发布。
- 每次提交到 `main`，`.github/workflows/pages.yml` 自动运行 GitHub Pages 部署。
- 部署完成后刷新公开网址即可查看修改。为避免缓存，必要时强制刷新。
- 不要把密钥、内部业务数据、私人文档、Career 加密档案或 OKR 放进 `site/`。

## 迭代计划

1. 根据视觉反馈继续调整首页、Portfolio、Tools。
2. 构建安全的后台登录、服务端鉴权与私有数据/文件存储。
3. 导入 Career 的完整内容（需从原应用导出并审查权限），历史建筑及设计作品后续上传。
4. 建立项目、工具、作品与 OKR 关联，并分别控制公开范围。

仓库地址：https://github.com/beaver123-sketch/yue-studio
