---
title: "BlackWhiteAdjustmentLayer.UseTint"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "BlackWhiteAdjustmentLayer 속성. 가져오거나 설정합니다 색조 색상이 사용되는지 여부를 나타내는 값"
type: docs
weight: 120
url: /ko/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.UseTint property

[tint color]가 사용되는지 여부를 나타내는 값을 가져오거나 설정합니다.

```csharp
public bool UseTint { get; set; }
```

### Property Value

`true` 사용된 경우 [tint color]; 그렇지 않으면 `false`.

## 예제

다음 예제는 Aspose.PSD에서 흑백 조정 레이어 속성을 조작하는 방법을 보여줍니다

```csharp
[C#]

sourceFileName = "BlackWhiteAdjustmentLayerStripesMask.psd";
outputFileName = "OutputBlackWhiteAdjustmentLayerStripesMask.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    var blwhLayer = (BlackWhiteAdjustmentLayer)image.Layers[1];

    blwhLayer.Reds = 15;
    blwhLayer.Yellows = 25;
    blwhLayer.Greens = 35;
    blwhLayer.Cyans = 10;
    blwhLayer.Blues = 50;
    blwhLayer.Magentas = 105;
    blwhLayer.UseTint = true;
    blwhLayer.BwPresetKind = 4;
    blwhLayer.BlackAndWhitePresetFileName = "bwPresetFileName";
    blwhLayer.TintColorRed = 60;
    blwhLayer.TintColorGreen = 80;
    blwhLayer.TintColorBlue = 200;

    image.Save(outputFileName, new PsdOptions());
}
```

### 또 보기

* class [BlackWhiteAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


