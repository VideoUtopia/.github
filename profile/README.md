# Utopic - 乌托邦短视频网络应用

Utopic是一个基于Web的短视频网络应用，旨在为用户提供丰富的功能，包括自由浏览视频、登录注册、浏览热门视频、获取视频推荐、浏览不同视频分类等。此外，Utopic还提供视频上传自动帧截取功能，使用户能够自由发布言论、点赞和评论喜欢的视频，以及关注他们喜欢的视频制作者。用户还可以搜索视频、发布自己的视频内容以及收藏喜欢的视频。"Utopic"这个名字寓意着我们对这个项目的美好愿景，即创造一个理想的社交视频体验。

## 项目特点

- **前端框架**: Utopic的前端采用了Flutter框架，这意味着它具有出色的图形绘制和自定义UI能力。Flutter还提供强大的跨平台功能，可以轻松推出不同平台的版本。
- **后端语言**: 后端采用Go语言，它具有出色的性能和并发支持，为Utopic提供了稳定和高效的服务。
- **数据库**: 数据存储方面，我们使用了七牛云存储Kodo，并结合Redis缓存，以确保数据的快速访问和高可用性。
- **持续集成/持续交付 (CI/CD)**: 我们在前端使用GitHub Actions来实现CI/CD流程，以确保项目的稳定性和持续改进。在后端，我们使用github webhook、hookdoo以及自定义脚本来实现持续部署，以提高开发效率。

## 项目效果展示

视频展示：https://www.bilibili.com/video/BV1qz4y1P77w/

## 访问Utopic

Utopic已经成功部署并可以通过以下方式访问：

1. 国内服务器：[utopic.gallifrey.asia](https://utopic.gallifrey.asia/)
2. GitHub Pages: [videoutopia.github.io](https://videoutopia.github.io/)

## 项目仓库

详细的设计文档和代码仓库可以在以下链接找到：

- **前端仓库**: [VideoUtopia/utopia-front (GitHub)](https://github.com/VideoUtopia/utopia-front)
- **后端仓库**: [VideoUtopia/utopia-back (GitHub)](https://github.com/VideoUtopia/utopia-back)
