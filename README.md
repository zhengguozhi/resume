## 一份优雅简约的简历

- 优化构建，页面秒开无闪烁
- 自适应屏幕兼容移动端
- Github Action 自动部署部署到 ghpages，可在线浏览
- 自动生成 PDF，全自动化流程

## 使用

1. fork 本项目后再 clone 到本地修改
2. 进入项目目录执行`npm i`安装依赖
3. 执行`npm run dev`开始开发，根据你的情况修改`src/index.html`里的内容
4. 替换`webpack-dist.config.js`文件里的`resume.zhengguozhi.cn`为你自己的域名，并根据[该文档配置你的域名解析](https://help.github.com/cn/github/working-with-github-pages/about-custom-domains-and-github-pages)
5. 修改完后 push 到 master 分支，Github Action 会自动部署
