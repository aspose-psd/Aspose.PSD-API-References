---
title: "VibranceLayer.Saturation"
second_title: "Aspose.PSD for .NET API Reference"
description: "VibranceLayer プロパティ。彩度を取得または設定します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/saturation/
---
{{< psd/tize >}}
## VibranceLayer.Saturation property

彩度を取得または設定します。

```csharp
public int Saturation { get; set; }
```

### Property Value

彩度。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 彩度は -100 から +100 の範囲である必要があります |

## 例

以下のコード例は VibranceLayer レイヤーのサポートと、この調整を編集する機能を示しています。

```csharp
[C#]

string sourceFileName = "WithoutVibrance.psd";
string outputFileNamePsd = "out_VibranceLayer.psd";
string outputFileNamePng = "out_VibranceLayer.png";

using (PsdImage image = (PsdImage) Image.Load(sourceFileName))
{
    // 新しい VibranceLayer の作成
    VibranceLayer vibranceLayer = image.AddVibranceAdjustmentLayer();
    vibranceLayer.Vibrance = 50;
    vibranceLayer.Saturation = 100;

    image.Save(outputFileNamePsd);
    image.Save(outputFileNamePng, new PngOptions());
}
```

### 関連項目

* class [VibranceLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../../)


