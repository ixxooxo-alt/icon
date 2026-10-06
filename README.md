# iOS 风格 3D 玻璃分流图标

**基础图标包与预览已完整发布，并新增 Apple Push 蓝色铃铛图标。** 基础包的 59 个独立图案覆盖原代码的全部 81 个策略分组，另含 DIRECT、REJECT、无可用节点。新增 Apple Push 后，256px 与 512px 目录各有 85 个命名文件。没有修改或接入分流配置。

[下载基础图标包 ZIP（v1.0.0）](https://github.com/ixxooxo-alt/icon/releases) · [图片直链 CSV](icon-urls.csv) · [图片直链 JSON](icon-urls.json) · [精确分组映射](group-icon-map.json)

| 内容 | 已发布 | 目录 |
| --- | ---: | --- |
| 256px 透明 PNG | 85 / 85 | [256px](256px/) |
| 512px 透明 PNG | 85 / 85 | [512px](512px/) |
| 生成原图 | 59 / 59 | [originals](originals/) |
| 总览与地区模式预览 | PNG + JPG | [previews](previews/) |

## Apple Push（新增）

采用第二款青蓝色玻璃铃铛图案，文件名为 `Apple Push.png`。

![Apple Push 蓝色铃铛](512px/Apple%20Push.png)

[256px PNG](https://raw.githubusercontent.com/ixxooxo-alt/icon/main/256px/Apple%20Push.png) · [512px PNG](https://raw.githubusercontent.com/ixxooxo-alt/icon/main/512px/Apple%20Push.png)

基础 ZIP、总览和映射文件对应原 84 个命名文件；本次新增图标从上面的链接单独获取。

## 全部图标总览

![全部图标总览](previews/all-routing-icons-preview.jpg)

[查看高清 PNG](previews/all-routing-icons-preview.png)

## 地区与模式预览

![地区与模式预览](previews/regions-and-modes-preview.jpg)

[查看高清 PNG](previews/regions-and-modes-preview.png)

## 命名与使用

256px、512px 和原图直链均已发布。基础包的 227 张图标 PNG 与新增 Apple Push 的两张尺寸文件均已核对 Git 文件哈希，与本地成品一致。

```text
https://raw.githubusercontent.com/ixxooxo-alt/icon/main/512px/OpenAI.png
```

地区包括香港、日本、韩国、台湾、新加坡、美国、其他地区。六个标准地区的五种模式子组均以实际组名单独输出：手动、手动优先、自动、故障转移、负载均衡。同一种模式在不同地区复用同一图案。

逻辑名称 `Apple Music/TV` 的文件名采用全角斜杠 `Apple Music／TV.png`，映射中的组名保留原代码名称。Policy 是配置段名，fallback 是组类型；文件按代码中的实际分组命名。

固定与解锁图案仅表示分组用途，不代表节点已绑定或已通过解锁验证。

图案由 AI 生成，品牌标识权利归各自权利人所有。
