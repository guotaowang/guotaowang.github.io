# Guotao Wang GitHub Homepage

这是一个可直接部署到 GitHub Pages 的个人学术主页静态站点。

## 文件结构

- `index.html`: 页面内容
- `style.css`: 页面样式

## 部署方式

### 方式 1：创建用户主页仓库（推荐）

1. 在 GitHub 新建仓库：`guotaowang.github.io`
2. 把当前目录里的文件上传到该仓库根目录
3. 推送后，GitHub 会自动把站点发布到：

```text
https://guotaowang.github.io/
```

### 方式 2：已有仓库中开启 Pages

1. 把本目录文件放进仓库
2. 进入 GitHub 仓库设置 `Settings -> Pages`
3. 在 `Build and deployment` 中选择：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`

## 你后面最建议补的内容

- 个人邮箱
- Google Scholar 链接
- 个人简历 PDF
- 个人头像
- 更多论文和项目链接

## 可直接修改的位置

- 首页简介：`index.html`
- 研究方向：`index.html`
- 代表论文：`index.html`
- 视觉风格：`style.css`
