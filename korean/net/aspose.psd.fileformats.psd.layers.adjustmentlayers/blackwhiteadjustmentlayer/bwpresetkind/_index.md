---
title: BlackWhiteAdjustmentLayer.BwPresetKind
second_title: .NET API 참조용 Aspose.PSD
description: BlackWhiteAdjustmentLayer 재산. 흑백 사전 설정 종류 값을 가져오거나 설정합니다.
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/bwpresetkind/
---
## BlackWhiteAdjustmentLayer.BwPresetKind property

흑백 사전 설정 종류 값을 가져오거나 설정합니다.

```csharp
public int BwPresetKind { get; set; }
```

### 자산 가치

흑백 사전 설정 종류 값입니다.

### 예

다음 예는 Aspose.PSD에서 흑백 조정 레이어 속성을 조작하는 방법을 보여줍니다.

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

### 또한보십시오

* class [BlackWhiteAdjustmentLayer](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* 집회 [Aspose.PSD](../../../)


