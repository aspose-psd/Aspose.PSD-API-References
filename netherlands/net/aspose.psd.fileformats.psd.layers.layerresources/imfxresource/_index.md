---
title: "Klasse ImfxResource"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ImfxResource class. Imfx resource multi-effectenresource"
type: docs
weight: 2850
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/imfxresource/
---
{{< psd/tize >}}
## ImfxResource class

Imfx resource (multi-effectenresource)

```csharp
public sealed class ImfxResource : BaseFxResource
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ImfxResource](imfxresource/)() | De standaardconstructor. |

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
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/imfxresource/typetoolkey/) | De type-tool-informatiesleutel. |

## Voorbeelden

De volgende code demonstreert ondersteuning van een multi-effecten resource.

```csharp
[C#]

// PSD-afbeelding bevat 2 Drop Shadow-effecten.
string sourceFile = "MultiExample.psd";
string outputFile1 = "export1.png";
string outputFile2 = "export2.png";
string outputFile3 = "export3.png";

using (PsdImage image = (PsdImage)Aspose.PSD.Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    // Het rendert de PSD-afbeelding met 2 Drop Shadow-effecten.
    image.Save(outputFile1, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    var blendingOptions = image.Layers[0].BlendingOptions;

    // Het voegt een derde Drop Shadow-effect toe.
    DropShadowEffect dropShadowEffect3 = blendingOptions.AddDropShadow();
    dropShadowEffect3.Color = Color.Red;
    dropShadowEffect3.Distance = 50;
    dropShadowEffect3.Angle = 0;

    // Het rendert de PSD-afbeelding met 3 Drop Shadow-effecten.
    image.Save(outputFile2, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // De imfx-resource wordt gebruikt als de laag meerdere effecten van hetzelfde type bevat.
    var imfx = (ImfxResource)image.Layers[0].Resources[0];

    // Het wist alle effecten.
    blendingOptions.Effects = new ILayerEffect[0];

    DropShadowEffect dropShadowEffect1 = blendingOptions.AddDropShadow();
    dropShadowEffect1.Color = Color.Blue;
    dropShadowEffect1.Distance = 10;

    // Het rendert de PSD-afbeelding met 1 Drop Shadow-effect (andere werden verwijderd).
    image.Save(outputFile3, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });

    // De lfx2-resource wordt gebruikt als de laag niet meerdere effecten van hetzelfde type bevat.
    var lfx2 = (Lfx2Resource)image.Layers[0].Resources[14];
}
```

### Zie ook

* class [BaseFxResource](../basefxresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


