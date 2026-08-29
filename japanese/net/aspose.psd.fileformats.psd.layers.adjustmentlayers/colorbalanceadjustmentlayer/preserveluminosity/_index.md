---
title: "ColorBalanceAdjustmentLayer.PreserveLuminosity"
second_title: "Aspose.PSD for .NET API Reference"
description: "ColorBalanceAdjustmentLayer プロパティ。この BlncResource が輝度を保持するかどうかを示す値を取得または設定します"
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

この [`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) が輝度を保持するかどうかを示す値を取得または設定します。

```csharp
public bool PreserveLuminosity { get; set; }
```

### Property Value

`true` は輝度を保持する場合です。そうでなければ `false` です。

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


