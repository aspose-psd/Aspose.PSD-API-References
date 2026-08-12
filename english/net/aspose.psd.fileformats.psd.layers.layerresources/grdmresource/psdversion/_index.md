---
title: GrdmResource.PsdVersion
second_title: Aspose.PSD for .NET API Reference
description: GrdmResource property. Gets the minimal PSD version required for this resource. Version 3 is needed when interpolation method is stored explicitly
type: docs
weight: 130
url: /net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/psdversion/
---
{{< psd/tize >}}
## GrdmResource.PsdVersion property

Gets the minimal PSD version required for this resource. Version 3 is needed when interpolation method is stored explicitly.

```csharp
public override int PsdVersion { get; }
```

## Examples

The following code demonstrates the specific behaviour of version in GrdmResource.

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

### See Also

* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


