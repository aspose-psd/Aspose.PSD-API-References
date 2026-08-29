---
title: "列挙体 InterpolationMode"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.InterpolationMode 列挙体。InterpolationMode 列挙体は、画像が拡大または回転されるときに使用されるアルゴリズムを指定します。"
type: docs
weight: 5520
url: /ja/net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

`InterpolationMode` 列挙体は、画像が拡大または回転されるときに使用されるアルゴリズムを指定します。

```csharp
public enum InterpolationMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Invalid | `-1` | 無効な補間モードです。 |
| Default | `0` | デフォルトモードを指定します。 |
| Low | `1` | 低品質の補間を指定します。 |
| High | `2` | 高品質の補間を指定します。 |
| Bilinear | `3` | 双一次補間を指定します。事前フィルタリングは行われません。このモードは画像を元のサイズの 50% 未満に縮小する場合には適していません。 |
| Bicubic | `4` | 双三次補間を指定します。事前フィルタリングは行われません。このモードは画像を元のサイズの 25% 未満に縮小する場合には適していません。 |
| NearestNeighbor | `5` | 最近傍補間を指定します。 |
| HighQualityBilinear | `6` | 高品質な双一次補間を指定します。高品質な縮小を保証するために事前フィルタリングが実行されます。 |
| HighQualityBicubic | `7` | 高品質な双三次補間を指定します。高品質な縮小を保証するために事前フィルタリングが実行されます。このモードは最高品質の変換画像を生成します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


