---
title: "Klasse IfxsResource"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IfxsResource class. Ifxs resource voor groepslaag-effecten"
type: docs
weight: 2840
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/
---
{{< psd/tize >}}
## IfxsResource class

Ifxs resource (resource voor groepslaag-effecten)

```csharp
public sealed class IfxsResource : BaseFxResource
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [IfxsResource](ifxsresource/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DescriptorVersion](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/descriptorversion/) { get; } | Haalt de descriptorversie op. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Haalt de laagresource-sleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/length/) { get; } | Haalt de lengte van de laagresource op in bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Haalt de minimale PSD-versie op die vereist is voor laagresource. 0 geeft geen beperkingen aan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Haalt de handtekening op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/basefxresource/save/)(StreamContainer, int) | Slaat de resource op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/) | De type-tool-informatiesleutel. |

## Voorbeelden

De volgende code toont de ondersteuning van IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // Voorbeeld heeft 2 groepslagen met effecten
    // Groepslaag met één effect
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Groepslaag met meerdere effecten
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Haal het aantal effecten op en controleer hun hoeveelheid
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Eén effect in de groepslaag bevindt zich in resource 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Twee of meer effecten in een groepslaag bevinden zich in resource 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Voeg een derde schaduw toe aan een groepslaag met meerdere effecten
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Zie ook

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


