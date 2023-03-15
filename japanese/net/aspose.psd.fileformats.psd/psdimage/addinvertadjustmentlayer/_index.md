---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage 方法. 反転調整レイヤーを追加します
type: docs
weight: 360
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

反転調整レイヤーを追加します。

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### 戻り値

作成した反転レイヤー

### 例

次のコードは、InvertAdjustmentLayer のサポートと、InvertAdjustmentLayer を追加する方法を示しています。

```csharp
[C#]

var filePath = "InvertStripes_before.psd";
var outputPath = "InvertStripes_after.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    im.AddInvertAdjustmentLayer();
    im.Save(outputPath);
}
```

### 関連項目

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)


