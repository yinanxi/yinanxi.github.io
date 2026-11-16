# 发布到 GitHub Pages

仓库名称：`yinanxi.github.io`，目标网址：`https://yinanxi.github.io`。

1. 在 GitHub 账号 yinanxi 下创建同名公开仓库。
2. 将本项目推送到该仓库的 main 分支。
3. 在仓库 Settings → Pages 中将 Source 设置为 GitHub Actions。
4. 等待 Actions 中的 Deploy site 成功。之后每次更新 main 都会自动发布。

网站已配置 `url: https://yinanxi.github.io` 和空 `baseurl`。不要使用上游示例的 `/al-folio` 路径。

## 本地更新

安装 Ruby 3.3+ 后执行 `bundle install`，再执行 `bundle exec jekyll serve`，打开 http://localhost:4000。

按用户要求，网站仅提供网页履历，不发布简历 PDF 和电话号码。网页使用邮箱、Google Scholar 和 GitHub 联系方式。
