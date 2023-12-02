# 基于`io.sentry.unity` 的二次修改

该库主要服务于 `https://github.com/AlianBlank/GameFrameX` 作为子库使用。


# 使用方式(三种方式)
1. 直接在 `manifest.json` 文件中的`dependencies` 下添加以下内容
   ```json
      {"io.sentry.unity": "https://github.com/AlianBlank/io.sentry.unity.git"}
    ```
2. 在Unity 的`Packages Manager` 中使用`Git URL` 的方式添加库,地址为：https://github.com/AlianBlank/io.sentry.unity.git

3. 直接下载仓库放置到Unity 项目的`Packages` 目录下。会自动加载识别

# 改动功能

1. 增加`link.xml` 防止代码被裁剪

# 官方文档

https://docs.sentry.io/platforms/unity/

当前同步的版本信息：
0.22.0



<p align="center">
  <a href="https://sentry.io" target="_blank" align="left">
    <img src="https://raw.githubusercontent.com/getsentry/sentry-unity/main/.github/sentry-wordmark-dark-400x119.svg" width="280">
  </a>
  <a href="https://docs.sentry.io/platforms/unity/" target="_blank" align="right">
    <img src="https://raw.githubusercontent.com/getsentry/sentry-unity/main/.github/unity-verified-logo.svg" width="280">
  </a>
  <br />
</p>

Sentry SDK for Unity
===========

This is the UPM package for the Sentry SDK for Unity.

Install it via `UPM`:
```
https://github.com/getsentry/unity.git#0.22.0
```

## Source code

The source code for this project is located at: https://github.com/getsentry/sentry-unity/

## Resources

* [![Documentation](https://img.shields.io/badge/documentation-sentry.io-green.svg)](https://docs.sentry.io/platforms/unity/)
* [![Discussions](https://img.shields.io/github/discussions/getsentry/sentry-unity.svg)](https://github.com/getsentry/sentry-unity/discussions)
* [![Discord Chat](https://img.shields.io/discord/621778831602221064?logo=discord&logoColor=ffffff&color=7389D8)](https://discord.gg/PXa5Apfe7K)
* [![Stack Overflow](https://img.shields.io/badge/stack%20overflow-sentry-green.svg)](http://stackoverflow.com/questions/tagged/sentry)
* [![Twitter Follow](https://img.shields.io/twitter/follow/getsentry?label=getsentry&style=social)](https://twitter.com/intent/follow?screen_name=getsentry)
