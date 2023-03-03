---
title: BlackWhiteAdjustmentLayer.UseTint
second_title: Aspose.PSD for .NET API リファレンス
description: BlackWhiteAdjustmentLayer 財産. 色合い を使用するかどうかを示す値を取得または設定します
type: docs
weight: 120
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/usetint/
---
## BlackWhiteAdjustmentLayer.UseTint property

[色合い] を使用するかどうかを示す値を取得または設定します。

```csharp
public bool UseTint { get; set; }
```

### プロパティ値

`真実` [ティントカラー]を使用した場合;さもないと、`間違い` .

### 例

次の例は、Aspose.PSD で白黒調整レイヤー プロパティを操作する方法を示しています。

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
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../blackwhiteadjustmentlayer/)
* 組み立て [Aspose.PSD](../../../)


