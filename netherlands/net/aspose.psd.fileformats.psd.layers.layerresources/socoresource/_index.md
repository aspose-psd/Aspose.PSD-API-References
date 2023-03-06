---
title: Class SoCoResource
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SoCoResource klas. Klasse SoCoResource. Deze bron bevat informatie over Color Fill Layers
type: docs
weight: 3010
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/
---
## SoCoResource class

Klasse SoCoResource. Deze bron bevat informatie over Color Fill Layers

```csharp
public class SoCoResource : FillLayerResource
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SoCoResource](socoresource/)() | Initialiseert een nieuw exemplaar van het`SoCoResource` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/) { get; set; } | Krijgt de RGB-kleur . |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/key/) { get; } | Haalt de laagbronsleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/length/) { get; } | Haalt de resourcelengte van de laag op in bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/psdversion/) { get; } | Haalt de minimale psd-versie op die vereist is voor laagresource. 0 geeft geen beperkingen aan. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/signature/) { get; } | Haalt de handtekening van de laagbron op. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/save/)(StreamContainer, int) | Slaat de bron op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/socoresource/typetoolkey/) | De infotoets voor het typen van gereedschap. |

### Voorbeelden

Het volgende voorbeeld laat zien hoe u SoCoResource (Layer Resource for Color Fill Layer) bewerkt

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Vinden van FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Vinden van SoCoResource in Layer Resource List
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // De eigenschap SoCoResource Color instellen
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Zie ook

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* montage [Aspose.PSD](../../)


