---
title: "列挙体 TextRenderingHint"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.TextRenderingHint 列挙体。テキストレンダリングの品質を指定します。"
type: docs
weight: 6200
url: /ja/net/aspose.psd/textrenderinghint/
---
{{< psd/tize >}}
## TextRenderingHint enumeration

テキストレンダリングの品質を指定します。

```csharp
public enum TextRenderingHint
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| SystemDefault | `0` | 各文字はそのグリフビットマップを使用して描画され、システム既定のレンダリングヒントが適用されます。テキストは、ユーザーがシステムで選択したフォントスムージング設定に従って描画されます。 |
| SingleBitPerPixelGridFit | `1` | 各文字はそのグリフビットマップを使用して描画されます。ヒンティングは、ステムや曲線上の文字の外観を向上させるために使用されます。 |
| SingleBitPerPixel | `2` | 各文字はそのグリフビットマップを使用して描画されます。ヒンティングは使用されません。 |
| AntiAliasGridFit | `3` | 各文字はヒンティング付きのアンチエイリアスされたグリフビットマップを使用して描画されます。アンチエイリアスにより品質は大幅に向上しますが、パフォーマンスコストが高くなります。 |
| AntiAlias | `4` | 各文字はヒンティングなしのアンチエイリアスされたグリフビットマップを使用して描画されます。アンチエイリアスにより品質が向上しますが、ヒンティングがオフのためステム幅の違いが目立つことがあります。 |
| ClearTypeGridFit | `5` | 各文字はヒンティング付きの ClearType グリフビットマップを使用して描画されます。最高品質の設定です。ClearType フォント機能を活用するために使用されます。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


