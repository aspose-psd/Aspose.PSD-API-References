---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdLoadOptions özelliği. Çarpıtma dönüşümü ile veya olmadan işlenmiş görüntüyü kaydetme durumunu alır veya ayarlar"
type: docs
weight: 30
url: /tr/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

Render edilmiş görüntüyle, eğri dönüşümle birlikte veya olmadan kaydedilip kaydedilmeyeceğini alır veya ayarlar.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` çarpıtma dönüşümüyle görüntüyü işle `false`.

## Örnekler

Aşağıdaki kod, Warp efekti oluşturulmasını gösterir.

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### Ayrıca Bakınız

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


