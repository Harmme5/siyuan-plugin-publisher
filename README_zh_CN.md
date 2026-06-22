[English](README.md)

# 发布工具

<img alt="logo" width="160" height="160" src="./icon.png"/>

将思源笔记的文章发布到语雀等平台，`开源`、`免费` 。

> 本仓库是
> [terwer/siyuan-plugin-publisher](https://github.com/terwer/siyuan-plugin-publisher)
> 的个人维护 fork，保留原项目的 GPL v3 许可证和版权声明，并包含面向个人使用场景的调整。

## 本 fork 的改动

- 修复本地系统发布时不使用配置中存储路径的问题。
- 为本地系统 Hugo 发布新增面向 `categories` 的“文章种类”字段。
- 清理 fork 文档，移除只适用于上游项目的社区和捐赠入口。

> [猛击这里](https://siyuan.wiki/s/20230810132040-nn4q7vs)，查看最新帮助文档。

## 快速上手

1. 点击插件市场，搜索 `发布工具`，安装插件。
2. 启用插件，然后在思源笔记窗口左上角工具栏有一个飞机按钮，点击，即可使用。
   ![](./docs/images/publisher-icon.png) 
3. 文档菜单（可选），参考 [帮助文档](https://siyuan.wiki/s/20230810132040-nn4q7vs) FAQ第12条，打开文档菜单，即可使用。
    

## 更新历史

**重大更新：**

- `v1.41.0` 于 3/16/2026 发布，新增功能
  - 支持 Astro 平台（支持 GitHub、Gitlab 以及本地系统） 😄
- `v1.38.0` 于 2025/10/25 发布，新增功能
  - 支持发布到`文件系统`了
  - 一期已经支持本地系统，后续会陆续支持ftp、sftp、各种网盘等🎉

请直接查看 [CHANGELOG](CHANGELOG.md)

# 感谢

感谢第三方框架对本项目底层的支持

排名不分先后

|    Name     | version |  vendor   |
| :---------: | :-----: | :-------: |
|    turbo    |  1.9+   |  Vercel   |
|     Vue     | 3.3.4+  | Evan You  |
|    Vite     |  4.2+   | Evan You  |
| TypeScript  |  5.0+   | Microsoft |
| siyuan-note | 2.9.0+  |    D,V    |

- 感谢 [leolee9086](https://github.com/leolee9086) 和 [赐我一胖]() 提供的图标资源
