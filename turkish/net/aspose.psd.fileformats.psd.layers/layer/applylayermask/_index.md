---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Layer yöntemi. Katman maskesini katmana uygular ve ardından maskeyi siler"
type: docs
weight: 350
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Katman maskesini katmana uygular, ardından maskeyi siler.

```csharp
public void ApplyLayerMask()
```

## Örnekler

Aşağıdaki kod, maskeyi katmana uygulama özelliğini gösterir.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ayrıca Bakınız

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


