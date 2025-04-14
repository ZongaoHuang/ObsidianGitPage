# ObsidianGitPage

使用 Obsidian + VitePress + Git 实现全流程的个人技文档或博客的撰写，同步，部署与上线。

## 功能介绍


## 工作流程

- 使用 Obsidian 在本地撰写内容
- 使用 git 将本地内容与 GitHub 仓库同步
- 使用 VitePress 获取 Markdown 内容生成个性化博客页面
- 使用 Github Actions 部署为 `https://<username>.github.io/repo` 页面

## 部署步骤

### 安装Obsidian
1. 在 [Obsidian - Sharpen your thinking](https://obsidian.md/) 选择合适的版本在本地安装Obsidian
2. 新建一个Obsidian仓库
![](png1.png)
3. 在仓库里新建一些内容，熟悉一下Obsidian的使用方法吧！
### 安装Git插件并上传 GitHub 仓库
1. 在Obsidian的仓库设置中，关闭安全模式，下载Git插件
![](png2.png)
2. 安装完 Obsidian git 插件后，你还需要本地拥有 git，你需要新建一个 GitHub 仓库，假设仓库取名为 `ObsidianTest` 
3. 然后你需要把你当前的 Obsidian 仓库所在的文件夹与 GitHub 仓库关联，也就是将本地的Obsidian 文件夹上传到 GitHub仓库，注意这里的上传的文件夹应当是包含 .obsidian 的。如下，初始化 GitHub 仓库后，此时本地的文件夹至少包括如下标红内容。
![](1744633542385_d.png)
4. 然后你需要在本地进行新建内容测试，确保本地新增内容能够成功的上传到对应的GitHub仓库。到此，以及完成了我们的**同步功能**！
### 安装 VitePress
1. 打开 VitePress官网安装教程 [快速开始 | VitePress](https://vitepress.dev/zh/guide/getting-started)，了解安装步骤，做好前置准备。
2. 本地使用编译器 VSCode 打开GitHub仓库所在的文件夹，上面截图所在的文件夹。
3. 在编译器终端输入 `npm add -D vitepress` 进行配置下载
4. 在编译器终端输入 `npx vitepress init` 进行初始化（3和4两步具体参照 VitePress官网安装教程），注意在初始化时，建议直接选择在根目录 `./`
5. 