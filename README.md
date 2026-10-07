# chaofenzi 的个人主页

本仓库是 [chaofenzi 的个人主页](https://chaofenzi.github.io) 的源码，仓库地址为 [chaofenzi/chaofenzi.github.io](https://github.com/chaofenzi/chaofenzi.github.io)。

我正在学习 Git、Linux 和 AI 工具。学习仓库：[hpc-learning](https://github.com/chaofenzi/hpc-learning)。

## 网站内容

- `_pages/about.md`：个人简介和学习仓库链接。
- `_config.yml`：站点标题、网址、仓库名和个人资料配置。
- `_data/navigation.yml`：主页导航。
- `_includes/`、`_layouts/`、`_sass/`、`assets/` 和 `images/`：页面模板、样式、脚本及静态资源。

未提供的学校、学历、论文、工作经历和联系方式不在主页中展示。未配置学术账号时，主页不会加载学术引用统计。

`README.md`、`docs/` 和 `google_scholar_crawler/` 已在 `_config.yml` 中排除，不作为网站内容发布。`docs/` 保留的是原模板使用说明和示例截图。

## 本地预览

安装 Ruby、Bundler 和 Jekyll 所需依赖后运行：

```bash
bundle install
bash run_server.sh
```

访问 `http://127.0.0.1:4000`。修改 `_config.yml` 后需要重启预览服务。

## 模板来源

本网站基于 [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) 模板，使用 MIT 许可证，原版权声明见 [LICENSE](LICENSE)。模板使用了 Font Awesome，并参考了 [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) 和 [Academic Pages](https://github.com/academicpages/academicpages.github.io)。这些项目的作者信息属于模板来源署名。
