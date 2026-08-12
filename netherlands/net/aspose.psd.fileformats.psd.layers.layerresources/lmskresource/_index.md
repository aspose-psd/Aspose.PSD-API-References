---
title: "Klasse LmskResource"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LmskResource klasse. De LMsk-resource"
type: docs
weight: 3020
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/
---
{{< psd/tize >}}
## LmskResource class

De LMsk-resource.

```csharp
public class LmskResource : LayerResource
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [LmskResource](lmskresource/)() | Initialiseert een nieuw exemplaar van de `LmskResource`-klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ColorComponent1](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent1/) { get; set; } | Haalt de kleurcomponent 1 op. |
| [ColorComponent2](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent2/) { get; set; } | Haalt de kleurcomponent 2 op. |
| [ColorComponent3](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent3/) { get; set; } | Haalt de kleurcomponent 3 op. |
| [ColorComponent4](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorcomponent4/) { get; set; } | Haalt de kleurcomponent 4 op. |
| [ColorSpace](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/) { get; set; } | Haalt de kleurenruimte op. |
| [Flag](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/flag/) { get; } | Haalt de vlag op. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Haalt de laagresource-sleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/length/) { get; } | Haalt de lengte van de laagresource op in bytes. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/opacity/) { get; set; } | Haalt de dekking op. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Haalt de minimale PSD-versie op die vereist is voor laagresource. 0 geeft geen beperkingen aan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Haalt de handtekening op. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/save/)(StreamContainer, int) | Slaat de resource op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lmskresource/typetoolkey/) | De type-tool-informatiesleutel. |

## Opmerkingen

Deze resource bevat een kleurenruimte-ID, die verwijst naar een specifiek type kleurenruimte, en 4 kleurcomponenten. Afhankelijk van de ID hebben de kleurcomponenten verschillende betekenissen. Als het type kleurenruimte geen vier waarden vereist, zijn de extra componenten ongedefinieerd en worden ze altijd als nullen geschreven. Kleurcomponenten per type kleurenruimte: RGB - de eerste drie componenten zijn rood, groen en blauw. HSB - de eerste drie componenten zijn tint, verzadiging en helderheid. CMYK - de vier componenten zijn cyaan, magenta, geel en zwart. Lab - de eerste drie componenten zijn lichtheid, a-chrominantie en b-chrominantie. Grijswaarden - de eerste component is de grijswaarde, van 0...10000.

## Voorbeelden

De volgende code demonstreert hoe je de weergaveopties van Layer Mask kunt wijzigen op 16-bit afbeeldingen door LmskResource-eigenschappen te wijzigen.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Laad 16-bit afbeelding.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Zoek LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Controleer LmskResource-eigenschappen.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Wijzig LmskResource-eigenschappen.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Sla de afbeelding op.
    image.Save(outputPsd);
}
```

### Zie ook

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


