---
title: "GrdmResource.PsdVersion"
second_title: "Aspose.PSD for .NET API Referansı"
description: "GrdmResource özelliği. Bu kaynak için gerekli olan minimum PSD sürümünü alır. Ara değerleme yöntemi açıkça depolandığında sürüm 3 gereklidir."
type: docs
weight: 130
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/psdversion/
---
{{< psd/tize >}}
## GrdmResource.PsdVersion property

Bu kaynak için gereken minimum PSD sürümünü alır. Enterpolasyon yöntemi açıkça depolandığında sürüm 3 gereklidir.

```csharp
public override int PsdVersion { get; }
```

## Örnekler

Aşağıdaki kod, GrdmResource içindeki sürümün belirli davranışını gösterir.

```csharp
[C#]

string sourceFile = "Grdm_Classic.psd";
string outputFilePsd = "output_Grdm_Smooth.psd";
string outputFilePng = "output_Grdm_Smooth.png";

using (var img = (PsdImage)PsdImage.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    GradientMapLayer gradientMapLayer = img.Layers[4] as GradientMapLayer;
    GradientMapSettings gradientSettings = gradientMapLayer.GradientSettings;
    GrdmResource grdmResource = gradientMapLayer.Resources[0] as GrdmResource;

    AssertAreEqual(1, grdmResource.PsdVersion);

    gradientSettings.InterpolationMethod = InterpolationMethod.Smooth;
    gradientMapLayer.Update();

    img.Save(outputFilePsd);
    img.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

using (var img = (PsdImage)PsdImage.Load(outputFilePsd, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    GradientMapLayer gradientMapLayer = img.Layers[4] as GradientMapLayer;
    GrdmResource grdmResource = gradientMapLayer.Resources[0] as GrdmResource;

    AssertAreEqual(3, grdmResource.PsdVersion);
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

* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


