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
2. 安装完Obsidian git插件后，你还需要本地拥有git，你需要新建一个GitHub仓库，假设仓库取名为 `repo` 
3. 然后你需要把你当前的Obsidian仓库所在的文件夹与GitHub仓库关联，也就是讲