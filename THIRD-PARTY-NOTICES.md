# Third-Party Notices / 第三方组件声明

AiSayDo 基于以下开源项目修改而成。感谢原作者的杰出工作。
本项目的修改与再分发遵循各上游组件的原始许可，声明保留如下。

## 1. DeepSeek Harness（本项目的主要基础）

- 上游：DeepSeek Harness `@deepseek-ai/dsh` 及全部 `@deepseek-ai/dsh-*` 插件包
- 版本：0.1.2-alpha.1
- 许可：MIT License
- 版权：Copyright (c) 2026 DeepSeek

```
MIT License

Copyright (c) 2026 DeepSeek

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 2. dsh-desktop（桌面应用壳）

- 上游：`dataelement/dsh-desktop`
- 许可：MIT License
- 版权：Copyright (c) 2026 DataElement
- 来源：https://github.com/dataelement/dsh-desktop

## 3. Cordis（插件化运行时框架）

- 上游：Cordis
- 许可：MIT License
- 版权：Copyright (c) 2021-present Shigma
- 说明：AiSayDo 的插件化能力构建于 Cordis 框架之上

## 4. 其他依赖项

项目依赖的 npm 包共 600 余个，许可分布如下。各包的完整许可文本随其
源码保留于各自包目录内的 `LICENSE` 文件中，此处仅作汇总：

| 许可 | 数量 | 代表性组件 |
|---|---|---|
| MIT | 546 | react, vite, koa 等 |
| Apache-2.0 | 62 | AWS SDK 系列、googleapis 等 |
| ISC | 23 | semver, graceful-fs, picocolors 等 |
| BSD-3-Clause | 15 | protobufjs, diff 等 |
| BSD-2-Clause | 2 | domino, json-schema-typed |
| LGPL-3.0-or-later | 1 | @img/sharp-libvips（预编译二进制，按上游原样分发） |
| 0BSD / BlueOak-1.0.0 / Python-2.0 | 各 1 | tslib, sax, argparse |

特别说明：

- **Apache-2.0** 组件：已保留其原始版权与 NOTICE 声明（见各包目录）。
- **BSD-3-Clause** 组件：未经事先书面许可，不使用上游贡献者名义为衍生产品背书。
- **LGPL-3.0** 组件（libvips）：以上游发布的独立二进制形式原样分发，未做静态修改；
  如需替换或修改该组件，可依据 LGPL 条款从上游重新构建。

---

*本文件由 AiSayDo 维护。如发现遗漏的许可声明，请提交 Issue。*
