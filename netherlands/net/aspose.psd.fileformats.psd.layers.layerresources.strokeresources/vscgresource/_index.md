---
title: "Klasse VscgResource"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.VscgResource klasse. Vector Stroke Content Data resource"
type: docs
weight: 3430
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---
{{< psd/tize >}}
## VscgResource class

Vector Stroke Content Data resource.

```csharp
public class VscgResource : LayerResource
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [VscgResource](vscgresource/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/) { get; } | Haalt op of stelt de array van structuuritems in. **Warning:** De `Items` arraywaarden moeten overeenkomen met de `KeyForData` eigenschap, die het type vullingsinstellingen bepaalt dat is opgeslagen in de structuren binnen `Items`. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Haalt de laagresource-sleutel op. |
| [KeyForData](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/keyfordata/) { get; } | Haalt de gehele sleutel op die definieert welk type vullingsinstellingen is opgeslagen in de resource: * Color - 0x536f436f - SoCoResource.TypeToolKey * Gradient - 0x4764466c - GdFlResource.TypeToolKey * Pattern - 0x5074466c - PtFlResource.TypeToolKey Waarschuwing! De waarde van eigenschap KeyForData moet overeenkomen met het type vullingsinstellingen dat is opgeslagen in Items-structuren. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/length/) { get; } | Haalt de lengte van de laagresource op in bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Haalt de minimale PSD-versie op die vereist is voor laagresource. 0 geeft geen beperkingen aan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Haalt de handtekening op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/save/)(StreamContainer, int) | Slaat de resource op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/typetoolkey/) | De type-tool-informatiesleutel. |

## Voorbeelden

De volgende code demonstreert de ondersteuning van VscgResource.

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// wijzigingen controleren
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### Zie ook

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


