---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: .NET API 참조용 Aspose.PSD
description: ColorBalanceAdjustmentLayer 재산. 이 여부를 나타내는 값을 가져오거나 설정합니다.BlncResource 광도를 유지합니다.
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

이 여부를 나타내는 값을 가져오거나 설정합니다.[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) 광도를 유지합니다.

```csharp
public bool PreserveLuminosity { get; set; }
```

### 자산 가치

`진실` 광도를 유지한다면; 그렇지 않으면,`거짓` .

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


