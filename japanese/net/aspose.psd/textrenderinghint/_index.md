---
title: Enum TextRenderingHint
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.TextRenderingHint 列挙. テキスト レンダリングの品質を指定します
type: docs
weight: 5700
url: /ja/net/aspose.psd/textrenderinghint/
---
## TextRenderingHint enumeration

テキスト レンダリングの品質を指定します。

```csharp
public enum TextRenderingHint
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| SystemDefault | `0` | 各文字は、システムのデフォルトのレンダリング ヒントを使用してグリフ ビットマップを使用して描画されます。テキストは、ユーザーがシステムに対して選択したフォント スムージング設定を使用して描画されます. |
| SingleBitPerPixelGridFit | `1` | 各文字はグリフ ビットマップを使用して描画されます。ヒンティングは、ステムと曲率の文字の外観を改善するために使用されます. |
| SingleBitPerPixel | `2` | 各文字はグリフ ビットマップを使用して描画されます。ヒンティングは使用されません. |
| AntiAliasGridFit | `3` | 各文字は、アンチエイリアス処理されたグリフ ビットマップとヒントを使用して描画されます。アンチエイリアシングにより品質が大幅に向上しますが、パフォーマンス コストが高くなります. |
| AntiAlias | `4` | 各文字は、ヒントなしでアンチエイリアス処理されたグリフ ビットマップを使用して描画されます。アンチエイリアシングによるより良い品質。ヒンティングがオフになっているため、ステム幅の違いが目立つ場合があります。 |
| ClearTypeGridFit | `5` | 各文字は、ヒント付きのグリフ ClearType ビットマップを使用して描画されます。最高品質の設定。 ClearType フォント機能を利用するために使用されます。 |

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


