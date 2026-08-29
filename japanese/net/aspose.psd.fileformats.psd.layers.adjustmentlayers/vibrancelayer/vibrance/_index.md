---
title: "VibranceLayer.Vibrance"
second_title: "Aspose.PSD for .NET API Reference"
description: "VibranceLayer プロパティ。バイブランスを取得または設定します"
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
{{< psd/tize >}}
## VibranceLayer.Vibrance property

バイブランスを取得または設定します。

```csharp
public int Vibrance { get; set; }
```

### Property Value

そのバイブランス。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | バイブランスは -180 から +180 の範囲でなければなりません。 |

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


