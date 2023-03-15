---
title: VibranceLayer.Vibrance
second_title: Aspose.PSD for .NET API リファレンス
description: VibranceLayer 財産. バイブランスを取得または設定します
type: docs
weight: 20
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/vibrance/
---
## VibranceLayer.Vibrance property

バイブランスを取得または設定します。

```csharp
public int Vibrance { get; set; }
```

### プロパティ値

バイブランス.

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | バイブランスは -180 から +180 の範囲でなければなりません |

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

* class [VibranceLayer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../vibrancelayer/)
* 組み立て [Aspose.PSD](../../../)


