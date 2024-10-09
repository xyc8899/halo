<p align="center">
    <a href="https://www.halo.run" target="_blank" rel="noopener noreferrer">
        <img width="100" src="https://www.halo.run/logo" alt="Halo logo" />
    </a>
</p>

<p align="center"><b>Halo</b> [ˈheɪloʊ]，强大易用的开源建站工具。</p>
<p align="center">
<a href="https://github.com/halo-dev/halo/releases"><img alt="GitHub release" src="https://img.shields.io/github/release/halo-dev/halo.svg?style=flat-square&include_prereleases" /></a>
<a href="https://hub.docker.com/r/halohub/halo"><img alt="Docker pulls" src="https://img.shields.io/docker/pulls/halohub/halo?style=flat-square" /></a>
<a href="https://github.com/halo-dev/halo/commits"><img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/halo-dev/halo.svg?style=flat-square" /></a>
<a href="https://github.com/halo-dev/halo/actions"><img alt="GitHub Workflow Status" src="https://img.shields.io/github/actions/workflow/status/halo-dev/halo/halo.yaml?branch=main&style=flat-square" /></a>
<a href="https://codecov.io/gh/halo-dev/halo"><img alt="Codecov percentage" src="https://img.shields.io/codecov/c/github/halo-dev/halo/main?style=flat-square&token=YsRUg9fall"/></a>
<a href="https://gitcode.com/feizhiyun/Halo"><img src="https://gitcode.com/feizhiyun/Halo/star/badge.svg" alt="GitCode Stars"></a>
<a href="https://www.producthunt.com/posts/halo-6b401e75-bb58-4dff-9fe9-2ada3323c874?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-halo&#0045;6b401e75&#0045;bb58&#0045;4dff&#0045;9fe9&#0045;2ada3323c874" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=407442&theme=light" alt="Halo - Powerful&#0032;and&#0032;easy&#0045;to&#0045;use&#0032;Open&#0045;Source&#0032;website&#0032;building&#0032;tool | Product Hunt" style="height: 20px;" height="20px" /></a>
<br />
<a href="https://www.halo.run">官网</a>
<a href="https://docs.halo.run">文档</a>
<a href="https://bbs.halo.run">社区</a>
<a href="https://gitee.com/halo-dev">Gitee</a>
<a href="https://t.me/halo_dev">Telegram 频道</a>
</p>

[![Watch the video](https://www.halo.run/upload/halo-github-screenshot.png)](https://www.bilibili.com/video/BV15x4y1U7RU/?share_source=copy_web&vd_source=0ab6cf86ca512a363f04f18b86f55b86)

------------------------------

## 快速开始

如果你的设备有 Docker 环境，可以使用以下命令快速启动一个 Halo 的体验环境：

```bash
docker run -d --name halo -p 8090:8090 -v ~/.halo2:/root/.halo2 halohub/halo:2.21
