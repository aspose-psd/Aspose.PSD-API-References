---
title: "ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ColorBalanceAdjustmentLayer 속성. Midtones Magenta Green Balance를 가져오거나 설정합니다."
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesmagentagreenbalance/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer.MidtonesMagentaGreenBalance property

Midtones Magenta Green Balance를 가져오거나 설정합니다.

```csharp
public short MidtonesMagentaGreenBalance { get; set; }
```

### Property Value

Midtones Magenta Green Balance.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | Midtones Magenta Green Balance는 -100에서 +100 사이여야 합니다. |

## 예제

다음 코드는 ColorBalanceAdjustmentLayer에 대한 지원을 보여줍니다.

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

### 또 보기

* class [ColorBalanceAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


