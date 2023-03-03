---
title: ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance
second_title: .NET API 참조용 Aspose.PSD
description: ColorBalanceAdjustmentLayer 재산. 중간톤 노랑 파랑 균형을 가져오거나 설정합니다.
type: docs
weight: 60
url: /ko/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesyellowbluebalance/
---
## ColorBalanceAdjustmentLayer.MidtonesYellowBlueBalance property

중간톤 노랑 파랑 균형을 가져오거나 설정합니다.

```csharp
public short MidtonesYellowBlueBalance { get; set; }
```

### 자산 가치

미드톤 옐로우 블루 밸런스.

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentOutOfRangeException | 중간톤 노란색 파란색 균형은 -100에서 +100 사이여야 합니다. |

### 예

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

### 또한보십시오

* class [ColorBalanceAdjustmentLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* 집회 [Aspose.PSD](../../../)


