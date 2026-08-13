---
title: "GrdmResource.ColorPoints"
second_title: "Aspose.PSD for .NET API Referansı"
description: "GrdmResource özelliği. Renk noktalarını alır veya ayarlar"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colorpoints/
---
{{< psd/tize >}}
## GrdmResource.ColorPoints property

Renk noktalarını alır veya ayarlar.

```csharp
public IGradientColorPoint[] ColorPoints { get; set; }
```

### Property Value

Renk noktaları.

## Örnekler

Aşağıdaki kod, GrdmResource kaynağının desteğini gösterir.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // geçerli değerleri kontrol et
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // İkinci degrade renk noktası için kırmızı renk
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // değiştirilen değerleri kontrol et
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Ayrıca Bakınız

* interface [IGradientColorPoint](../../../aspose.psd.fileformats.psd.layers/igradientcolorpoint/)
* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


