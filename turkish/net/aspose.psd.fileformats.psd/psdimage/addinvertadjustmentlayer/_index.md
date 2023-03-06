---
title: PsdImage.AddInvertAdjustmentLayer
second_title: Aspose.PSD for .NET API Referansı
description: PsdImage yöntem. Bir ters ayarlama katmanı ekler.
type: docs
weight: 360
url: /tr/net/aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/
---
## PsdImage.AddInvertAdjustmentLayer method

Bir ters ayarlama katmanı ekler.

```csharp
public InvertAdjustmentLayer AddInvertAdjustmentLayer()
```

### Geri dönüş değeri

Oluşturulan ters katman

### Örnekler

Aşağıdaki kod, InvertAdjustmentLayer desteğini ve InvertAdjustmentLayer'ın nasıl ekleneceğini gösterir.

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

### Ayrıca bakınız

* class [InvertAdjustmentLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/)
* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)


