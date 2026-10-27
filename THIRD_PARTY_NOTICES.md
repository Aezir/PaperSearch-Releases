# 第三方声明

## Remix Icon

UI 中使用固定提交 `9fb7967c0a4c09910161192bde99efd3df09f5eb` 的单个 Remix Icon 图标，转换为 Android VectorDrawable 并随安装包离线分发。图标受 Remix Icon License v1.0 约束，完整许可见 `third_party/remixicon/LICENSE.txt`；APK 中也包含许可副本。

产品桌面、自适应、圆形、单色图标和关于页使用用户提供的 tadpole-logo-kit.zip 中的蝌蚪品牌资源，不使用 Remix Icon 作为品牌标志。原附件摘要及使用范围见 docs/branding/source.json。服务品牌图标仅用于表示、链接到相应服务。

## SearchJumper

参考版本：`hoothin/SearchJumper@af4a0fbbec7f154a72cc7658ab865fa3fda65e11`。参考 README 搜索模板说明、schema.json 的 name/url 结构和配置交互。未复制、改写或移植其 GPL-3.0 源代码。导入器只把简单 GET 搜索 URL 当作数据读取，不执行 SearchJumper 的脚本表达式或页面自动化。

## PiliPlus

仅检查官方发布 APK 的 Intent 声明、官方 AndroidManifest.xml 和运行行为，以验证 `bilibili://search?keyword=…` 协议互通。未复用 PiliPlus 源代码或资源。

## theSVG

品牌 Logo 来源为 https://thesvg.org/ 对应的官方仓库 glincker/thesvg，固定提交 fa87032438a21826df5a4fbb0e6b0ce9d02147d6。原始 SVG、逐个来源与许可元数据、SHA-256 见 third_party/thesvg/。保留 LICENSE、LEGAL.md、TRADEMARK.md，APK 包含许可与声明副本。SVG 等比渲染成透明 PNG。底栏统一为单色剪影，搜索栏及选择条保留服务品牌颜色；OpenAI / GitHub 单色图标根据主题着色以保证对比度。

内置 13 个品牌 Logo（含自定义入口可选的 GitHub）；高德、拼多多、京东未在该固定版本目录中找到对应品牌，保留备用图标。品牌图标用于识别跳转服务；商标归相应权利人所有。旧配置中的预设图标在显示时兼容映射，自定义图标选择保留。

本项目原创部分采用 LICENSE 中的严格个人非商业许可。该许可不覆盖或改变以上第三方许可及商标权。
