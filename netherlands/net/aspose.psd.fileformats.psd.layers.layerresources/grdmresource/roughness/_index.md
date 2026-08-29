---
title: "GrdmResource.Roughness"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "GrdmResource eigenschap. Ruwheidsfactor Wanneer Gradient type Noise we kunnen Roughness 0  2048 toewijzen"
type: docs
weight: 160
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/
---
{{< psd/tize >}}
## GrdmResource.Roughness property

Ruwheidsfactor Wanneer 'Gradient type' = 'Noise', kunnen we 'Roughness' (0 - 2048) toewijzen.

```csharp
public int Roughness { get; set; }
```

## Voorbeelden

De volgende code demonstreert ondersteuning van de GrdmResource resource.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // controleer huidige waarden
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // Rode kleur voor het tweede kleurpunt van de gradiënt.
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // controleer gewijzigde waarden
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

### Zie ook

* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


