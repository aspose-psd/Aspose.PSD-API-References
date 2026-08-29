---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdImage メソッド。反転調整レイヤーを追加します。"
type: docs
weight: 380
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

反転調整レイヤーを追加します。

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### 戻り値

作成された反転レイヤー

## 例

以下のコードは InvertAdjustmentLayer のサポートと InvertAdjustmentLayer の追加方法を示しています。

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
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


