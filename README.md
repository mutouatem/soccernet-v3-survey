# SoccerNet-v3 文献工作台

围绕 SoccerNet-v3（*Scaling up SoccerNet with multi-view spatial localization and
re-identification*, Cioppa et al., Scientific Data 2022）整理的两份文献综述，外加一份方法与公式的配套笔记。

**网页版**：https://mutouatem.github.io/soccernet-v3-survey/

## 内容

| 文件 | 内容 | 语料 |
|---|---|---|
| [`citations.html`](citations.html) | **跨视角球员重识别综述** — 引用 SoccerNet-v3 的文献全览，回答「这个 benchmark 上已经做到哪一步」 | 102 篇 |
| [`methodology.html`](methodology.html) | **SoccerNet-v3 方法论图谱** — Re-ID / 跨视角 / 遮挡 / 检测四方向的顶会进展，回答「外面有什么方法能搬过来」 | 37 篇 |
| [`reid-methods.html`](reid-methods.html) | **v3 跨视角 ReID：三篇文献里的方法与公式** — RFES-ReID 与 SoccerNet 2022 / 2023 两届挑战赛里每个 re-ID 方法的拆解，公式逐条标注出处（配套笔记，不计入语料） | 3 篇 |

## 两条主要结论

1. **v3 的跨视角 re-ID 标注基本被绕开了。** 172,622 条直播↔回放对应中，报告过成绩的只有两届挑战赛和一篇方法论文，而那篇方法对视角差异没有任何显式设计。
2. **外部方法里没有对应的设定。** 最接近的空地跨视角 Re-ID 匹配的是*不同时刻*、*外观可区分*的个体；而足球场上同队 11 人球衣完全相同，主流遮挡 Re-ID「恢复未遮挡区域特征即可判别身份」的前提不成立。

## 可见性

本站设置了 `noindex` meta 与全站 `robots.txt` 禁止抓取，不会被搜索引擎收录。
仓库本身公开，链接可直接访问。

## 语料来源

OpenAlex API（引用关系、引用数）+ Google Scholar（补充 OpenAlex 漏收条目）。
基准数字均回溯各篇原文核对。
