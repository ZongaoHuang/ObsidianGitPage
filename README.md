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
### 安装Git插件
1. 在Obsidian的仓库设置中，关闭安全模式，下载Git插件
![](png2.png)
2. 安装完 Obsidian git 插件后，你还需要本地拥有 git，你需要新建一个 GitHub 仓库，假设仓库取名为 `repo` 
3. 然后你需要把你当前的 Obsidian 仓库所在的文件夹与 GitHub 仓库关联，也就是将本地的Obsidian 文件夹**（包含 .obsidian 的文件夹）**上传到 GitHub仓库。

> [!NOTE] Title
> 具体上传哪个文件夹可能有疑惑，你需要首先找到 .obsidian 这个文件夹，然后该目录在另一个文件夹就是你的仓库文件夹，然后就把当前包含 .obsidian 的文件夹进行上传
