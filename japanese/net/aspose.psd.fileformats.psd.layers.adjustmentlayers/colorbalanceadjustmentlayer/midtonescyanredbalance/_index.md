---
title: "ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance"
second_title: "Aspose.PSD for .NET API Reference"
description: "ColorBalanceAdjustmentLayer プロパティ。Midtones Cyan Red Balance を取得または設定します"
type: docs
weight: 40
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonescyanredbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesCyanRedBalance property

Midtones Cyan Red Balance の値を取得または設定します。

```csharp
public short MidtonesCyanRedBalance { get; set; }
```

### Property Value

Midtones Cyan Red Balanceです。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | Midtones Cyan Red Balance は -100 から +100 の範囲である必要があります。 |

## 例

以下のコードは ColorBalanceAdjustmentLayer のサポートを示しています。

```csharp
[C#]

var filePath = "ColorBalance.psd";
var outputPath = "ColorBalance_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    foreach (var layer in im.Layers)
    {
        var cbLayer = layer as ColorBalanceAdjustmentLayer;
        if (cbLayer != null)
        {
            cbLayer.ShadowsCyanRedBalance = 30;
            cbLayer.ShadowsMagentaGreenBalance = -15;
            cbLayer.ShadowsYellowBlueBalance = 40;
            cbLayer.MidtonesCyanRedBalance = -90;
            cbLayer.MidtonesMagentaGreenBalance = -25;
            cbLayer.MidtonesYellowBlueBalance = 20;
            cbLayer.HighlightsCyanRedBalance = -30;
            cbLayer.HighlightsMagentaGreenBalance = 67;
            cbLayer.HighlightsYellowBlueBalance = -95;
            cbLayer.PreserveLuminosity = true;
        }
    }

    im.Save(outputPath);
}
```

### 関連項目

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


