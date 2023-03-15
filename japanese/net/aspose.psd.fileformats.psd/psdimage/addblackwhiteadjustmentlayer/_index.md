---
title: PsdImage.AddBlackWhiteAdjustmentLayer
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage 方法. 白黒調整レイヤーを追加します
type: docs
weight: 290
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/
---
## PsdImage.AddBlackWhiteAdjustmentLayer method

白黒調整レイヤーを追加します。

```csharp
public BlackWhiteAdjustmentLayer AddBlackWhiteAdjustmentLayer()
```

### 戻り値

作成した白黒調整レイヤー。

### 例

次の例は、実行時に Aspose.PSD で白黒調整レイヤーを追加する方法を示しています。

```csharp
[C#]

string sourceFileName = "Stripes.psd";
string outputFileName = "OutputStripes.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    BlackWhiteAdjustmentLayer newLayer = image.AddBlackWhiteAdjustmentLayer();
    newLayer.Name = "BlackWhiteAdjustmentLayer";
    newLayer.Reds = 22;
    newLayer.Yellows = 92;
    newLayer.Greens = 70;
    newLayer.Cyans = 79;
    newLayer.Blues = 7;
    newLayer.Magentas = 28;

    image.Save(outputFileName, new PsdOptions());
}
```

### 関連項目

* class [BlackWhiteAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)


