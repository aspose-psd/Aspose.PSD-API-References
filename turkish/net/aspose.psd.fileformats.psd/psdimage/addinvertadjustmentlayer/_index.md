---
title: "PsdImage.AddInvertAdjustmentLayer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdImage yöntemi. Tersine çevirme ayar katmanı ekler"
type: docs
weight: 380
url: /tr/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddInvertAdjustmentLayer method

Ters çevirme ayar katmanını ekler.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Dönüş Değeri

Oluşturulan tersine çevirme katmanı

## Örnekler

Aşağıdaki kod, InvertAdjustmentLayer desteğini ve InvertAdjustmentLayer eklemeyi gösterir.

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

### Ayrıca Bakınız

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


