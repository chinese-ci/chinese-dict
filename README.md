# 纯词库物料

本仓库发布[词铸 CiZhu](https://github.com/chinese-ci/cizhu) 的纯词库物料：UTF-8、一行一个词条、按类目分文件、文件名即类目，不含输入编码、频次、权重或来源信息。物料可被任意输入法或词库工具消费。

## 结构

- `阳春白雪/`：[GB/T 20093-2022](https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=88537A39BE1C3D1B5C6294F70838096E) 的 24 个一级类目，外加 `地名/`。v1 中这 24 类暂不细分子类，每类只有一个 `其它.txt` 收纳该类全部词条；`地名/` 则按行政区划、道路、机构、风景名胜、国外地名、其它分文件。
- `下里巴人/`：日常口语、生活服务、成语熟语、新词、方言、游戏电竞、动漫二次元、影视娱乐 8 类，按提案子类目分文件 + `其它.txt`。
- `下里巴人/成语熟语/诗词名句.txt` 在 v1 为 planned 空文件。
- 每个类目内子类目按提案顺序排列，`其它.txt` 最后。

## 生成

物料由[词铸 CiZhu](https://github.com/chinese-ci/cizhu) 的采集与[词修 CiXiu](https://github.com/chinese-ci/cixiu) 工具生成，本仓库只保存归一后的词条字符串。公开物料不含来源名称、权重或字形原值。

## 许可

数据采用 [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)（见 `LICENSE`）。如后续加入脚本，脚本默认 [MIT](https://opensource.org/license/mit)；纯数据仍为 CC0。
