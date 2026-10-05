<!-- ELUCENIA technical documentation · escala-de-rankin-modificada · ja · no clinical/professional/rights approval -->

# 修正Rankin尺度（mRS）

[条件・出典・許諾](https://elucenia.org/ja/tools/escala-de-rankin-modificada)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 患者の現在の状態

`mrs`

- `0` — 0 – 症状なし
- `1` — 1 – 明らかな障害なし：症状があっても通常の活動をすべて行う
- `2` — 2 – 軽度障害：以前の活動をすべて行えないが介助なしで自分のことができる
- `3` — 3 – 中等度の障害：一部介助が必要だが他人の介助なく歩行可能
- `4` — 4 – 中等度から重度の障害：介助なしでは歩行・身体ケア不能
- `5` — 5 – 重度の障害：臥床、失禁があり常時介護が必要
- `6` — 6 – 死亡

## 方法の版

mRS/NINDS C13230第3版：0–6の等級、合計なし；van Swieten 1988：0–5の六つの等級；Cincura 2009：ブラジルでの適応版の参考文献、この検証では再確認していない

## 記載された計算式

患者に最も合う項目を選びます。加算はなく、段階そのもの（0～6）が結果です。

## 限界・対象集団

脳卒中患者の障害を順序尺度で分類し、機能評価と追跡時点に依存します。採用した版の構造化された手順を優先してください。ローカルの0–6版は、1988年の歴史的な抄録に記載された六つのカテゴリーと区別する必要があります。 この文献検証では、公式NINDSデータ要素C13230第3版の0から6の値を確認した。van Swieten（1988）の抄録は0から5の六つの等級を記載している。選択されたコードの一致は、機能評価、面接またはブラジルでの適応版を検証するものではない。

## 参考文献

- [van Swieten JC et al. Interobserver agreement for the assessment of handicap in stroke patients. Stroke, 1988.](https://doi.org/10.1161/01.STR.19.5.604)

- [Cincura C et al. Validation of the National Institutes of Health Stroke Scale, Modified Rankin Scale and Barthel Index in Brazil: the role of cultural adaptation and structured interviewing. Cerebrovasc Dis, 2009.](https://doi.org/10.1159/000177918)

- [NINDS C13230 version 3. Modified Rankin Scale score: official current permissible values 0–6.](https://cde.nlm.nih.gov/deView?tinyId=1Ff4qmrHH1C)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
