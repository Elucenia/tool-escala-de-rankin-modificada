<!-- ELUCENIA technical documentation · escala-de-rankin-modificada · zh · no clinical/professional/rights approval -->

# 改良 Rankin 量表（mRS）

[条件、来源与许可](https://elucenia.org/zh/tools/escala-de-rankin-modificada)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 患者当前状态

`mrs`

- `0` — 0 – 无症状
- `1` — 1 – 无明显残疾：虽有症状，仍能完成所有日常活动
- `2` — 2 – 轻度残疾：不能完成全部既往活动，但可独立自理
- `3` — 3 – 中度残疾：需要一些帮助，但步行不需他人辅助
- `4` — 4 – 中重度残疾：无法独立步行或照料身体
- `5` — 5 – 重度残疾：卧床、失禁、需持续照护
- `6` — 6 – 死亡

## 方法版本

mRS/NINDS C13230第3版：0–6级，不相加；van Swieten 1988：六个等级0–5；Cincura 2009：巴西适应性修订的参考文献，本次核查未重新核查该修订

## 已记录的公式

选择最符合患者的类别。不作加和：结果即等级本身（0至6）。

## 限制与适用人群

用于卒中患者残障程度的有序分类，依赖功能评估及随访时间。宜采用所用版本的结构化说明。本地0–6版本应与1988年历史摘要中描述的六个类别区分。 本次文献核查在官方NINDS数据元素C13230第3版中读取了0至6的取值。van Swieten（1988）的摘要描述了0至5的六个等级。所选代码相符并不验证功能评估、访谈或巴西适应性修订。

## 参考文献

- [van Swieten JC et al. Interobserver agreement for the assessment of handicap in stroke patients. Stroke, 1988.](https://doi.org/10.1161/01.STR.19.5.604)

- [Cincura C et al. Validation of the National Institutes of Health Stroke Scale, Modified Rankin Scale and Barthel Index in Brazil: the role of cultural adaptation and structured interviewing. Cerebrovasc Dis, 2009.](https://doi.org/10.1159/000177918)

- [NINDS C13230 version 3. Modified Rankin Scale score: official current permissible values 0–6.](https://cde.nlm.nih.gov/deView?tinyId=1Ff4qmrHH1C)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

轻度残疾：独立

mRS 0 至 2：有利的功能结局（独立）。


### 2

中度残疾：部分依赖


### 3

重度残疾：完全依赖

