[中文](README_zh_CN.md)

# Publisher

<img alt="logo" width="160" height="160" src="./icon.png"/>

Publish articles from siyuan-note to platforms like WordPress、Cnblogs、Yuque etc. `Free` and `open source`.

> This repository is a personal maintenance fork of
> [terwer/siyuan-plugin-publisher](https://github.com/terwer/siyuan-plugin-publisher). It keeps the original GPL v3
> license and copyright notices, and may include changes tailored for personal use.

## Fork Changes

- Fixed local system publishing so the configured storage path is respected.
- Added a Hugo-oriented article category field for local system publishing.
- Cleaned up fork documentation by removing upstream-only community and donation links.

> Please [click here to see the latest docs](https://siyuan.wiki/s/20240330142711-bc3gjg0), it updates in real
> time.

## Quick Start

1. Click on the plugin marketplace, search for `Publisher`, and install the plugin.
2. Enable the plugin, then click on the airplane button in the top-left toolbar of the siyuan-note window to start using it.  
   ![](./docs/images/publisher-icon.png)
3. Document menu (optional): Refer to [docs](https://siyuan.wiki/s/20230810132040-nn4q7vs) FAQ 12 to enable the document menu and start using it.

## Update History

Major Update:

- `v1.41.0` was released on 3/16/2026, now has the following features:
  - add full Astro platform support (including GitHub, gitlab, and local system) 😄
- `v1.38.0` was released on 10/25/2025, now supporting the following features:
  - publishing to file system as local files 🚀
  - The initial release enables publishing to your local file system. Support for additional protocols and services—including FTP, SFTP, and various cloud drives is planned for future updates. 🎉

Please check [CHANGELOG.md](CHANGELOG.md) directly.

# Thanks

- Thanks to the third-party framework for supporting the bottom layer of this project

  Names not listed in order

  |    Name     | version |vendor|
    |:-----------:|:-------:| :---------: |
  |    turbo    |  1.9+   |Vercel|
  |     Vue     | 3.3.4+  |Evan You|
  |    Vite     |  4.2+   |Evan You|
  | TypeScript  |  5.0+   |Microsoft|
  | siyuan-note | 2.9.0+  |D,V|

- Thanks to [leolee9086](https://github.com/leolee9086) and [ciwoyipang]() for the icon resource
