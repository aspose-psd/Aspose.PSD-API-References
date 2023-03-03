---
title: PsdImage.AddVibranceAdjustmentLayer
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage 方法. 自然な彩度調整レイヤーを追加します
type: docs
weight: 430
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/
---
## PsdImage.AddVibranceAdjustmentLayer method

自然な彩度調整レイヤーを追加します。

```csharp
public VibranceLayer AddVibranceAdjustmentLayer()
```

### 戻り値

新しく作成されたバイブランス レイヤー。

### 例

次のコード例は、VibranceLayer レイヤーのサポートと、この調整を編集する機能を示しています。

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // 新しい VibranceLayer を作成する
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### 関連項目

* class [VibranceLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)


