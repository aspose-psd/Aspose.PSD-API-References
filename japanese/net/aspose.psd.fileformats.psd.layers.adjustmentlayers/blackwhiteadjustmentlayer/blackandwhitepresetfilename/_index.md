---
title: "BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName"
second_title: "Aspose.PSD for .NET API Reference"
description: "BlackWhiteAdjustmentLayer プロパティ。黒白プリセットファイル名を取得または設定します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/blackandwhitepresetfilename/
---
{{< psd/tize >}}
## BlackWhiteAdjustmentLayer.BlackAndWhitePresetFileName property

白黒プリセットファイル名を取得または設定します。

```csharp
public string BlackAndWhitePresetFileName { get; set; }
```

### Property Value

黒白プリセットファイル名です。

## 例

次の例は、Aspose.PSD で黒白調整レイヤーのプロパティを操作できる方法を示しています

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

### 関連項目

* class [BlackWhiteAdjustmentLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


