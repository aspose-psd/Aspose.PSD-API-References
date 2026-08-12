---
title: "Klasse BaseLayerSectionResource"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.BaseLayerSectionResource class. Basisklasse voor laagsectie-resources"
type: docs
weight: 2560
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/
---
{{< psd/tize >}}
## BaseLayerSectionResource class

Basisklasse voor laagsectie-resources

```csharp
public abstract class BaseLayerSectionResource : LayerResource
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BlendModeKey](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/blendmodekey/) { get; set; } | Haalt of stelt de blend mode key in. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Haalt de laagresource-sleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/length/) { get; } | Haalt de lengte van de laagresource op in bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Haalt de minimale PSD-versie op die vereist is voor laagresource. 0 geeft geen beperkingen aan. |
| [SectionType](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/sectiontype/) { get; set; } | Haalt op of stelt het sectietype in. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Haalt de handtekening op. |
| [Subtype](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/subtype/) { get; set; } | Haalt op of stelt het subtype in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/save/)(StreamContainer, int) | Slaat de resource op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Voorbeelden

De volgende code toont de klassehiërarchie van laagsectie-resources.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string srcFile = "123 1.psd";
string outFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[3].Resources[3] as LayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[3].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Length, 4);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).BlendModeKey, BlendMode.Absent);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Subtype, LayerSectionSubtype.NotUsed);

    psdImage.Save(outFile);
}

// controleer na het opslaan
using (var psdImage = (PsdImage)Image.Load(outFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[3].Resources[3] as LayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[3].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).SectionType, LayerSectionType.SectionDivider);

    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Length, 4);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).BlendModeKey, BlendMode.Absent);
    AssertAreEqual((psdImage.Layers[8].Resources[3] as BaseLayerSectionResource).Subtype, LayerSectionSubtype.NotUsed);
}

File.Delete(outFile);
```

### Zie ook

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


